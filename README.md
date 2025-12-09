# Machine Learning Portfolio 🚀

Bu depo, makine öğrenmesi algoritmalarını öğrenme yolculuğumda geliştirdiğim projeleri, yaptığım analizleri ve kod uygulamalarını içermektedir. Teorik bilgileri pratiğe dökmek ve "Hands-on" (uygulamalı) tecrübe kazanmak amacıyla oluşturulmuştur.

## 📂 Depo Yapısı

Projeler, makine öğrenmesi alt alanlarına göre kategorize edilmiştir:

* **01_Supervised_Learning:** Gözetimli öğrenme algoritmaları (Classification, Regression vb.)
* *(Gelecek)* **02_Unsupervised_Learning:** Gözetimsiz öğrenme (Clustering vb.)

---

## 🔬 Öne Çıkan Proje: Breast Cancer Classification with k-NN

Şu anda bu depodaki ilk proje, tıbbi bir teşhis problemini ele alan **Meme Kanseri Sınıflandırma** çalışmasıdır.

🔗 **Projeyi İncele:** [01_KNN_Breast_Cancer_Classification.ipynb](./01_Supervised_Learning/01_KNN_Breast_Cancer_Classification.ipynb)

### 📌 Proje Özeti
Bu çalışmanın amacı, **Wisconsin Breast Cancer Dataset** verilerini kullanarak tümörlerin **Malignant** (Kötü Huylu) veya **Benign** (İyi Huylu) olup olmadığını tahmin eden bir makine öğrenmesi modeli geliştirmektir.

### 🛠️ Kullanılan Teknolojiler ve Kütüphaneler
* **Dil:** Python 3.x
* **Veri Analizi:** Pandas, NumPy
* **Görselleştirme:** Matplotlib, Seaborn
* **Makine Öğrenmesi:** Scikit-learn (sklearn)

### 📊 Proje Adımları
Bu notebook içerisinde aşağıdaki veri bilimi adımları uygulanmıştır:

1.  **Exploratory Data Analysis (EDA):** Veri setinin dengesi, eksik veriler ve özellikler arasındaki korelasyonlar (Heatmap) incelendi.
2.  **Data Preprocessing:**
    * Veri seti Eğitim (%80) ve Test (%20) olarak ayrıldı (`stratify` kullanılarak).
    * k-NN uzaklık temelli bir algoritma olduğu için **StandardScaler** ile özellik ölçeklendirmesi yapıldı.
3.  **Model Training & Tuning:**
    * **k-Nearest Neighbors (k-NN)** algoritması kullanıldı.
    * En iyi sonucu veren 'k' komşu sayısını bulmak için 1'den 20'ye kadar değerler denenerek bir hiperparametre optimizasyonu yapıldı.
4.  **Evaluation:**
    * Modelin başarısı **Confusion Matrix** ve **Classification Report** ile ölçüldü.
    * Tıbbi bir konu olduğu için sadece doğruluğa (Accuracy) değil, gözden kaçan kanserli vakaları minimize etmek için **Recall** değerlerine odaklanıldı.

---

## 📬 İletişim

Sorularınız veya geri bildirimleriniz için bana ulaşabilirsiniz.

* **GitHub:** [ErenBalkis](https://github.com/ErenBalkis)
* **LinkedIn:** [ErenBalkis](https://linkedin.com/in/eren-balkis)

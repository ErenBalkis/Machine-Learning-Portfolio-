# Machine Learning Portfolio 🚀

This repository documents my learning journey in machine learning, containing projects, data analysis, and code implementations. It is designed to bridge the gap between theoretical knowledge and practical "hands-on" experience.

## 📂 Repository Structure

Projects are categorized by machine learning subfields:

* **01_Supervised_Learning:** Supervised learning algorithms (Classification, Regression, etc.)
* *(Upcoming)* **02_Unsupervised_Learning:** Unsupervised learning (Clustering, etc.)

---

## 🔬 Featured Project: Breast Cancer Classification with k-NN

This is the first project in this portfolio, addressing a medical diagnostic problem: **Breast Cancer Classification**.

🔗 **View Project:** [01_KNN_Breast_Cancer_Classification.ipynb](./01_Supervised_Learning/01_KNN_Breast_Cancer_Classification.ipynb)

### 📌 Project Summary
The goal of this project is to develop a machine learning model to predict whether a tumor is **Malignant** or **Benign** using the **Wisconsin Breast Cancer Dataset**.

### 🛠️ Technologies & Libraries Used
* **Language:** Python 3.x
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (sklearn)

### 📊 Project Steps
The following data science steps were implemented in this notebook:

1.  **Exploratory Data Analysis (EDA):** Analyzed class balance, missing values, and feature correlations (Heatmap).
2.  **Data Preprocessing:**
    * Split the dataset into Training (80%) and Test (20%) sets (using `stratify`).
    * Applied **StandardScaler** for feature scaling, as k-NN is a distance-based algorithm.
3.  **Model Training & Tuning:**
    * Implemented the **k-Nearest Neighbors (k-NN)** algorithm.
    * Performed hyperparameter optimization by testing values from 1 to 20 to find the optimal 'k' neighbors.
4.  **Evaluation:**
    * Evaluated model performance using **Confusion Matrix** and **Classification Report**.
    * Focused on **Recall** score (alongside Accuracy) to minimize false negatives (missed cancer cases), which is critical in medical diagnostics.

---

## 📬 Contact

Feel free to reach out for questions or feedback.

* **GitHub:** [ErenBalkis](https://github.com/ErenBalkis)
* **LinkedIn:** [ErenBalkis](https://linkedin.com/in/eren-balkis)

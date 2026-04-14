# 💊 Drug Classification Project

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Project Overview
This project leverages Machine Learning to predict the most suitable drug type for patients based on specific medical attributes. By analyzing factors like blood pressure, cholesterol, and electrolyte ratios, the model provides data-driven support for healthcare professionals in clinical decision-making.

### 🎯 Objectives
* **Predict** drug categories with high precision.
* **Identify** key medical features that influence prescription.
* **Develop** an end-to-end automated Machine Learning pipeline.

---

## 📊 Dataset Overview
The model is trained on a clinical dataset containing the following features:

| Feature | Description |
| :--- | :--- |
| **Age** | Patient's age |
| **Sex** | Gender (Male/Female) |
| **BP** | Blood Pressure levels (Low, Normal, High) |
| **Cholesterol** | Cholesterol levels (Normal, High) |
| **Na_to_K** | Sodium-to-Potassium ratio in the blood |
| **Drug** | **Target Variable:** The prescribed drug type |

---

## 🛠️ Tech Stack
* **Language:** Python
* **Data Handling:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (Decision Tree, Random Forest, Logistic Regression)

---

## 📉 Visualizations
> [!TIP]
> To see these images, ensure your plots are saved in a `/visualizations` folder within your repository.

| Target Distribution | Feature Relationships | Confusion Matrix |
| :---: | :---: | :---: |
| ![Target Distribution](visualizations/target_dist.png) | ![Feature Relationships](visualizations/feature_rel.png) | ![Confusion Matrix](visualizations/confusion_matrix.png) |

---

## 🚀 Project Workflow

1.  **Data Preprocessing:** Handled missing values, removed duplicates, and corrected data types.
2.  **Exploratory Data Analysis (EDA):** Analyzed feature distributions and categorical relationships.
3.  **Feature Engineering:** Encoded categorical variables (Label Encoding) and scaled numerical features.
4.  **Model Building:** Evaluated multiple algorithms including Decision Trees, Random Forests, and Logistic Regression.
5.  **Model Evaluation:** Measured performance using Accuracy, F1-Score, and Confusion Matrices.

---

## 🏆 Results & Key Learnings
* **Top Performer:** The **Random Forest** model achieved the highest accuracy.
* **Feature Importance:** The `Na_to_K` (Sodium-to-Potassium ratio) was identified as the most significant predictor.
* **Key Insight:** Robust data preprocessing and feature encoding are critical for handling medical categorical data effectively.

---

## ⚙️ How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ShitalDatascience/drug-classification.git](https://github.com/ShitalDatascience/drug-classification.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Execute the pipeline:**
    ```bash
    python main.py
    ```

---

## 📂 Project Structure
```text
drug-classification/
│
├── data/               # Raw and processed datasets
├── notebooks/          # Jupyter notebooks for EDA and testing
├── models/             # Saved model files (.pkl)
├── src/                # Source code for the ML pipeline
├── visualizations/     # Generated plots and graphs
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation

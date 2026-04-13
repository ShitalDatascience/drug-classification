**Drug Classification**

**Project Overview**

This project builds a Machine Learning model to predict the correct drug type for patients based on medical attributes like age, sex, blood pressure, cholesterol, and sodium-to-potassium ratio.

The goal is to assist healthcare professionals with data-driven drug prescription decisions.

**Objective**

- Predict drug category accurately

- Understand key influencing features

- Build an end-to-end ML pipeline

**Dataset Overview**

Feature	               Description

Age                 	Patient age

Sex	                  Male/Female

BP	                  Blood Pressure

Cholesterol	          Cholesterol Level

Na_to_K	              Sodium to Potassium ratio

Drug	                Target variable

**Visualizations**

🔹 Target Distribution




🔹 Feature Relationships




🔹 Confusion Matrix




Replace these placeholder images with your actual plots (saved as .png from your notebook)

**Tech Stack**

- Python
  
- Pandas & NumPy
  
- Matplotlib & Seaborn
  
- Scikit-learn
  
**Project Workflow**

1️⃣ Data Preprocessing

-Checked missing values

-Removed duplicates

-Converted data types

2️⃣ Exploratory Data Analysis (EDA)

- Distribution plots

- Category analysis

- Feature relationships

3️⃣ Feature Engineering

- Encoding categorical variables

- Scaling numerical features (if required)

4️⃣ Model Building

- Decision Tree 
- Random Forest 
- Logistic Regression
  
5️⃣ Model Evaluation

- Accuracy Score
- Confusion Matrix
- Classification Report
  
**Results**

- High accuracy achieved.
  
- Random Forest performed best
  
- Key influencing features:
     Na_to_K ratio (most important)
  
     Blood Pressure
  
     Cholesterol

**Feature Importance**

Feature importance was extracted using tree-based models to understand:

Which features influence predictions most.

How medical factors impact drug selection.

**How to Run**

**Clone repo**

git clone https://github.com/your-username/drug-classification.git

**Install dependencies**

pip install -r requirements.txt

**Run project**

python main.py

**Project Structure**

drug-classification/
│
├── data/
├── notebooks/
├── models/
├── src/
├── requirements.txt
└── README.md

**Future Improvements**

- Hyperparameter tuning
  
- Cross-validation
 
- Model deployment (Flask / FastAPI)
  
- Real-time prediction system

**Key Learnings**

- Data preprocessing is crucial

- Feature engineering improves performance

- Model selection impacts results

- Feature importance helps interpretation

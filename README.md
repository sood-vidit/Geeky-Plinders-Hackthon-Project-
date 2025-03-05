# 🔥 Heart Failure Readmission Prediction (AI/ML)

## 📌 Project Overview
Hospital readmission due to heart failure is a significant healthcare challenge, increasing the *risk of mortality* and *financial burden* on patients and healthcare systems. This project focuses on developing a *Machine Learning model* to predict *30-day readmission risk* for heart failure patients.

## 🏥 Problem Statement
Heart failure is a leading cause of hospital readmissions, even for patients receiving proper treatment. The goal is to predict **which patients are at higher risk** of readmission after discharge, allowing for *targeted interventions* to reduce mortality and improve healthcare outcomes.

### 🔑 Key Features
✅ *Developing an AI/ML Model* to predict heart failure readmission within *30 days*.  
✅ *MIMIC-III Dataset* is used, with a subset of relevant tables.  
✅ *Data Preprocessing & Feature Engineering*: Handling missing values, standardizing features, and selecting relevant diagnosis codes (ICD9 codes).  
✅ *Ensuring Data Integrity*: Implementing an **age cap till 2025**, ensuring that ages beyond this are **not included** in training.  
✅ *Fixing MIMIC-III Fake Dates Issue*: MIMIC-III codes sometimes **generate fake dates**, which previously caused inconsistencies. This issue has now been addressed.  

## 📊 Dataset Information
- The dataset is derived from *MIMIC-III* and contains *patient admission records, diagnoses, and demographics*.
- *Diagnosis Codes (ICD9) for Heart Failure*:
  
  '39891', '40201', '40211', '40291', '40401', '40403', '40411', '40413', '40491', 
  '40493', '4280', '4281', '42820', '42821', '42822', '42823', '42830', '42831', 
  '42832', '42833', '42840', '42841', '42842', '42843', '4289'
  

## 🛠 How to Run the Project
1. *Clone the repository*:
   bash
   git clone <https://github.com/sood-vidit/Geeky-Plinders-Hackthon-Project-.git>
   
2. *Navigate to the project folder*:
   bash
   cd <Geeky-Blinders-Hackathon-Project->
   
3. *Run the Jupyter Notebook*:
   bash
   jupyter notebook heart_failure_prediction.ipynb
   

## 🔍 Data Preprocessing Steps
1. *Handling Missing Data* – Imputation strategies applied for missing patient data.
2. *Feature Engineering* – Extracting meaningful features from patient records.
3. *Data Standardization* – Scaling features for better model performance.
4. *Age Cap Implementation* – Ensuring all patients in training data were born *before 2025*.
5. *Fixing Fake Dates* – Removing erroneous timestamps from MIMIC-III.

## 🤖 Model Training
- Models Evaluated: *XGBoost*.
- Performance Metrics: *Accuracy, AUC-ROC*.

## 📜 License
This project is *open-source* and available under the *MIT License*.

## 🤝 Contributions
We welcome contributions! Feel free to *submit issues or pull requests*.

---

🚀 *Developed for Veersa Hackathon Submission* | *Manipal University Jaipur, Batch 2025-26*

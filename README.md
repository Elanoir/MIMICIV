# 📊  MMIC-IV

## 🗃️ Dataset
- Source: https://physionet.org/content/mimiciv/2.2/
- The Medical Information Mart for Intensive Care (MIMIC)-IV 2.2 contains EHRs of over 40,000 patients admitted multiple times to the Beth Israel Deaconess Medical Center, between 2008 and 2020, performing almost 5 million entries in the database.
- This dataset is divided into two big categories: EHRs from the hospital and EHRs from the Intensive Care Unit (ICU).
- The data from the hospital contains multiple .csv tables regarding admissions (hospital stays), patients’ information (gender, age, date of death), diagnostics, services that cared for the patient, laboratory measurements, prescriptions, and unit transfers, for example. 
- The ICU category includes .csv tables regarding ICU admissions, information about administrations to patients and its ingredients, and all the medical procedures to which a patient was subjected during the ICU stay.


## 🔍 Objetives
- Health professionals are responsible for making various data-driven decisions throughout clinical processes to diagnose medical issues in patients and advise appropriate treatment.
- Patient similarity analysis can be used to support physicians' decision-making, enabling them to retrieve clusters of patients sharing patterns in medical histories, identify co-occurring diagnoses (comorbidities) through pattern mining, and predict the likelihood of events such as hospital readmission or even the possibility of death.
- Here, an exploratory analysis of the MIMIC-IV 2.2 database concerning hospital data can be found.
- Descriptive mining tasks, such as statistical analysis, clustering techniques, and pattern mining, are presented in order to find a data representation that enables fitting patients into well-defined clusters that have similar characteristics, and the identification of co-occurring diagnoses within those clusters.

## 🛠️ Tools
- Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, etc.)
- Jupyter Notebook

## 📈 Methodologies
1. **Acquisition and Data Cleaning**
2. **Exploratory Data Analysis (EDA)**
3. **Cluestering Modeling**
4. **Model Evaluation**
5. **Frequent Pattern Analysis**
6. **Discussion**

## 💡 Findings
- There was a 431231 hospital admissions from a total number of 180733 patients (average of 2.39 admissions per patient)
- Admission in-hospital mortality rate of 4.76 % (8598 patients)
- The majority of patients are: married and 'white', admited to the hospital as EW Emergency and discharged home after hospital admission
- The five most prevalent diagnosis were unspecified essential hypertension, other and unsepecified hyperlipidemia, esophageal reflux, diabetes mellitus and atrial fibrillation
- 5 clusters of patients were acessed, regarding diagnosis
- Cluster 4 has a distinct clinical pattern: young woman, pregnant, 0% mortality
- Frequent pattern analysis of Cluster 4 showed woman attending to the hospital while pregnant, return for child birth.
    



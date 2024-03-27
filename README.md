# Exploratory Data Analysis (EDA) on Heart Failure Clinical Records Dataset

This repository contains code and analysis for performing Exploratory Data Analysis (EDA) on the Heart Failure Clinical Records Dataset. The dataset contains various clinical parameters for patients with heart failure, including age, sex, blood pressure, serum creatinine, and more.

## Dataset

The dataset was collected at the Faisalabad Institute of Cardiology and the Allied Hospital in Faisalabad, Punjab, Pakistan, during the period of April to December in 2015. 

The dataset comprises medical records of 299 patients diagnosed with heart failure. These records include various clinical, body, and lifestyle information of the patients. The dataset encompasses 13 features, providing insights into the patients' health status and potential risk factors for heart failure.

### Features:
- Age: The age of the patient (numeric).
- Anaemia: Indicates the presence of anemia (binary: 0 for no, 1 for yes).
- Creatinine Phosphokinase (CPK): Level of creatinine phosphokinase enzyme in the blood (numeric).
- Diabetes: Indicates whether the patient has diabetes (binary: 0 for no, 1 for yes).
- Ejection Fraction: Percentage of blood leaving the heart at each contraction (numeric).
- High Blood Pressure: Indicates whether the patient has high blood pressure (binary: 0 for no, 1 for yes).
- Platelets: Platelet count in the blood (numeric).
- Serum Creatinine: Level of creatinine in the blood (numeric).
- Serum Sodium: Level of sodium in the blood (numeric).
- Sex: Gender of the patient (binary: 0 for female, 1 for male).
- Smoking: Indicates whether the patient smokes (binary: 0 for no, 1 for yes).
- Time: Follow-up period (in days) for the patient's condition (numeric).
- Death_Event : Indicates whether the patient died during the follow-up period (binary: 0 for no, 1 for yes).


## Contents

- `dataset/heart_failure_clinical_records_dataset.csv`: CSV file containing the dataset.
- `heart_failure_clinical_data_eda.ipynb`: Jupyter Notebook containing the code for EDA.
- `README.md`: This README file providing an overview of the repository.

## Data Analysis & Findings

The EDA focuses on understanding the distribution and relationships between various clinical parameters in the dataset. Key aspects of the analysis include:

- Data cleaning and preprocessing.
- Univariate analysis to understand the distribution of individual features.
- Bivariate analysis to explore relationships between pairs of features.
- Visualization of findings using plots such as histograms, box plots, and scatter plots.

### Findings
1. What is the distribution of age among heart failure patients in the dataset ?
2. How does the death rate vary with age?
3. What is the percentage of male and female patients in the dataset?
4. How does the platelet count vary among different age groups ?
5. Is there a correlation beteeen creatinine and sodium levels in the blood
6. How does the prevalence of high blood pressure differ between male and Female patients
7. What is the relationship between smoking habits and the occurrence on heart failure
8. Are there any noticeable patterns in the distribution on death events across different age groups
9. Is there any significant difference in ejection fraction between patients with and without diabetes
10. How does the serum creatinine level vary between patients who survived and those who did not?

## Requirements

To run the analysis, you need Python 3.x along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

You can install the required libraries using pip:
```
pip install pandas numpy matplotlib seaborn jupyter
```


## Usage

1. Clone the repository:

```
git clone https://github.com/sateeshfrnd/EDA-on-Heart-Failure-Clinical-Data.git
```

2. Navigate to the project directory:
```
cd EDA-on-Heart-Failure-Clinical-Data
```

3. Launch Jupyter Notebook:
```
jupyter notebook
```

4. Open and run the `heart_failure_clinical_data_eda.ipynb` notebook to perform EDA on the dataset.

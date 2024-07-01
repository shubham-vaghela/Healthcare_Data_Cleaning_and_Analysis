# Healthcare Data Analysis

## Overview

This project involves analyzing a healthcare dataset to uncover insights regarding patient demographics, medical conditions, hospitalizations, billing, and treatment outcomes. The analysis aims to identify patterns, trends, and potential areas for improvement in patient care and hospital management.

## Dataset

The dataset contains the following columns:
- Name (string)
- Age (integer)
- Gender (string)
- Blood Type (string)
- Medical Condition (string)
- Date of Admission (string)
- Doctor (string)
- Hospital (string)
- Insurance Provider (string)
- Billing Amount (float)
- Room Number (integer)
- Admission Type (string)
- Discharge Date (string)
- Medication (string)
- Test Results (string)

Total Entries: 55,500
Columns: 15

## Objectives

1. Identify the common medical conditions and their distribution among patients.
2. Analyze the correlation between patient demographics (age, gender, blood type) and medical conditions and treatment outcomes.
3. Determine the average billing amount for different medical conditions and hospitals.
4. Examine the variations in admission types and discharge dates across different hospitals and medical conditions.
5. Identify the most commonly prescribed medications and analyze the test results.

## Visualizations

### 1. Age and Gender Distribution for Each Medical Condition
![Age and Gender Distribution for Each Medical Condition](./Age_and_Gender_Distribution_for_Each_Medical_Condition.png)

### 2. Average Billing Amount for Each Medical Condition
![Average Billing Amount for Each Medical Condition](./Average_Billing_Amount_for_Each_Medical_Condition.png)

### 3. Correlation Matrix
![Correlation Matrix](./Correlation_Matrix.png)

### 4. Distribution of Billing Amounts Across Different Insurance Providers
![Distribution of Billing Amounts Across Different Insurance Providers](./Distribution_of_Billing_Amounts_Across_Different_Insurance_Providers.png)

### 5. Distribution of Gender
![Distribution of Gender](./Distribution_of_Gender.png)

### 6. Distribution of Medical Condition
![Distribution of Medical Condition](./Distribution_of_Medical_Condition.png)

### 7. Distribution of Test Results for Different Medical Conditions
![Distribution of Test Results for Different Medical Conditions](./Distribution_of_Test_Results_for_Different_Medical_Conditions.png)

### 8. Most Commonly Prescribed Medications
![Most Commonly Prescribed Medications](./Most_Commonly_Prescribed_Medications.png)

### 9. Average Billing Amount for Each Hospital
![Average Billing Amount for Each Hospital](./Average_Billing_Amount_for_Each_Hospital.png)

### 10. Correlation Between Medications and Test Results
![Correlation Between Medications and Test Results](./Correlation_Between_Medications_and_Test_Results.png)

### 11. Distribution of Admission Types
![Distribution of Admission Types](./Distribution_of_Admission_Types.png)

### 12. Distribution of Blood Type
![Distribution of Blood Type](./Distribution_of_Blood_Type.png)

### 13. Distribution of Hospital Length of Stay
![Distribution of Hospital Length of Stay](./Distribution_of_Hospital_Length_of_Stay.png)

### 14. Distribution of Medical Conditions Across Different Hospitals
![Distribution of Medical Conditions Across Different Hospitals](./Distribution_of_Medical_Conditions_Across_Different_Hospitals.png)

### 15. Frequency of Each Medical Condition
![Frequency of Each Medical Condition](./Frequency_of_Each_Medical_Condition.png)

### 16. Trends in Admission and Discharge Dates Over Time
![Trends in Admission and Discharge Dates Over Time](./Trends_in_Admission_and_Discharge_Dates_Over_Time.png)

## Analysis

The analysis is conducted using the Jupyter notebook `Healthcare_Project.ipynb`, which includes the code to generate the above visualizations and perform detailed data analysis.

## Instructions to Run

1. Ensure you have Python and Jupyter Notebook installed.
2. Install the required libraries by running:
    ```bash
    pip install pandas matplotlib seaborn
    ```
3. Open the Jupyter notebook:
    ```bash
    jupyter notebook Healthcare_Project.ipynb
    ```
4. Run the cells in the notebook to perform the analysis and generate the visualizations.

## Conclusion

This project provides comprehensive insights into healthcare data, helping to understand patient demographics, medical conditions, billing, and treatment outcomes. The visualizations assist in identifying patterns and trends, aiding in better hospital management and patient care.

## Files

- `Healthcare_Project.ipynb`: Jupyter notebook containing the data analysis and visualization code.
- `healthcare_dataset_cleaned.csv`: Cleaned dataset used for analysis.
- Various PNG files containing the generated visualizations.

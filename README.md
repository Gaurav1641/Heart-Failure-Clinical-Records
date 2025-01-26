# Heart Failure Dataset Analysis

This project analyzes a dataset of heart failure patients, focusing on understanding patterns, correlations, and distributions of various medical factors contributing to heart failure. The dataset contains clinical, body, and lifestyle information of 299 patients collected in Faisalabad, Pakistan.

## Dataset Details
- **Source:** Faisalabad Institute of Cardiology and Allied Hospital
- **Time Period:** April to December 2015
- **Features:** 13 clinical and lifestyle attributes including:
  - `age`: Age of the patient (numeric)
  - `anaemia`: Presence of anemia (binary: 0 = No, 1 = Yes)
  - `creatinine_phosphokinase`: Level of creatinine phosphokinase enzyme (numeric)
  - `diabetes`: Presence of diabetes (binary: 0 = No, 1 = Yes)
  - `ejection_fraction`: Percentage of blood leaving the heart at each contraction (numeric)
  - `high_blood_pressure`: Presence of hypertension (binary: 0 = No, 1 = Yes)
  - `platelets`: Platelet count in blood (numeric)
  - `serum_creatinine`: Creatinine levels in blood (numeric)
  - `serum_sodium`: Sodium levels in blood (numeric)
  - `sex`: Gender of the patient (binary: 0 = Female, 1 = Male)
  - `smoking`: Smoking status (binary: 0 = No, 1 = Yes)
  - `time`: Follow-up period (numeric)
  - `DEATH_EVENT`: Survival status (binary: 0 = Alive, 1 = Deceased)

## Questions Explored

1. **What is the distribution of age among heart failure patients?**
   - A histogram visualizes the age distribution with a kernel density estimate for better insights.

2. **How does the death rate vary with age?**
   - A line plot showcases the death rate across different age groups.

3. **What is the percentage of male and female patients in the dataset?**
   - The gender distribution is calculated and displayed as percentages.

4. **How does the platelet count vary among different age groups?**
   - Mean platelet count is analyzed and visualized for defined age groups.

5. **Is there a correlation between creatinine and sodium levels in the blood?**
   - The Pearson correlation coefficient is calculated to identify the relationship.

6. **How does the prevalence of high blood pressure differ between male and female patients?**
   - The proportion of patients with high blood pressure is compared between genders.

7. **What is the relationship between smoking habits and the occurrence of heart failure?**
   - Death rates are compared between smokers and non-smokers.

8. **Are there patterns in the distribution of death events across different age groups?**
   - A bar plot illustrates the number of death events by age.

9. **Is there a significant difference in ejection fraction between diabetic and non-diabetic patients?**
   - Average ejection fraction values are compared between the two groups.

10. **How does the serum creatinine level vary between survivors and non-survivors?**
    - Mean serum creatinine levels are analyzed based on survival status.

## Usage
The analysis is implemented in Python using the following libraries:
- **Pandas** for data manipulation
- **Matplotlib** and **Seaborn** for visualizations

To execute the analysis:
1. Update the `file_path` variable with the path to the dataset.
2. Run the script in a Python environment.
3. Review the visualizations and printed results to answer the questions above.

## Visualizations
Each question is accompanied by a relevant visualization, such as histograms, line plots, or bar charts, placed directly after the code block that generates them.

## Key Insights
- Death rates increase significantly with age.
- High blood pressure is slightly more prevalent in males compared to females.
- Diabetic patients have a marginally lower average ejection fraction compared to non-diabetic patients.
- Non-survivors exhibit higher serum creatinine levels on average compared to survivors.

## Conclusion
The analysis highlights critical factors associated with heart failure outcomes and provides a foundation for further exploration. The insights gained can help medical professionals better understand the risks and trends in heart failure patients.



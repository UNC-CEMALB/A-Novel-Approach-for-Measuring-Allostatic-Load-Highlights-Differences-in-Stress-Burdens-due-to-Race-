# A Novel Approach for Measuring Allostatic Load Highlights Differences in Stress Burdens due to Race, Sex and Smoking Status

Script that associates with "A Novel Approach for Measuring Allostatic Load Highlights Differences in Stress Burdens due to Race, Sex and Smoking Status", currently under review.

> The goal of this project was to compare physiological markers of stress using primary and secondary mediator biomarkers across various demographic groups (ie. sex, race, and smoking status).

In the instance that the files are unable to rendered on Github the files can be viewed using NBViewer [here](https://nbviewer.org/github/UNC-CEMALB/A-Novel-Approach-for-Measuring-Allostatic-Load-Highlights-Differences-in-Stress-Burdens-due-to-Race-/tree/main/).

# 1. Mediator Score Calculation
- Imputed missing data using the Quantile Regression Imputation of Left-Censored (QRILC) technique
- Performed a min-max normalization to calculate the mediator scores

# 2. Allostatic Load Calculation (Figures 1-3, Table S1)
- Calculated allostatic load (AL) scores for each subject which serves as a measure of stress (combines acute and chronic stress)
- t tests were run to test for statistical difference in acute stres, chronic stress, and AL across race, sex, and smoking status groups
- ANOVA and post hoc t tests were run to test for differences in subjects further stratified within those demographic groups

# 3. Mediator Distribtion Analysis (Table S4-S6)
- Ran t tests to test for statistical differences in mediators across race, sex, and smoking status groups

#Results Summary
##Exploratory Analysis
*Benign samples were more frequent than malignant, indicating mild class imbalance in the dataset.
*Malignant tumors showed consistently higher values of radius_mean and concavity_mean compared to benign tumors.
##Statistical Testing
*Radius_mean differed significantly between malignant and benign tumors (Mann–Whitney U test, p < 0.001).
*The effect size was large (Cliff’s delta > 0.47), indicating strong separation between groups.
##Model Performance
*The baseline logistic regression model achieved excellent discrimination (ROC-AUC ≈ 0.98–0.99).
*The confusion matrix showed high sensitivity and specificity with few misclassifications.

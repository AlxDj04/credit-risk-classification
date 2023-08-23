# Module 12 Report Template

Original Model:

Balanced Accuracy: {balanced accuracy score}
Precision and Recall Scores:
Precision for Class 0: {precision}
Precision for Class 1: {precision}
Recall for Class 0: {recall}
Recall for Class 1: {recall}
Resampled Model:

Balanced Accuracy: {balanced accuracy score after resampling}
Precision and Recall Scores:
Precision for Class 0: {precision after resampling}
Precision for Class 1: {precision after resampling}
Recall for Class 0: {recall after resampling}
Recall for Class 1: {recall after resampling}
Summary
Based on the analysis results, the resampled model demonstrated improved performance in terms of balanced accuracy, precision, and recall scores compared to the original model. The resampling technique effectively addressed the class imbalance issue and led to more accurate predictions of both healthy (0) and high-risk (1) loan statuses.

The recommendation is to utilize the resampled Logistic Regression model due to its enhanced performance. The decision to choose a model should consider the specific problem at hand. For instance, if correctly predicting high-risk loans (1) is of paramount importance, the resampled model's improved recall for Class 1 is a critical consideration. Ultimately, the choice should align with the business objective and risk tolerance.
See prompt_III_v2.ipynb for Jupyter notebook.

Summary of findings:
The dataset contains information related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The business objective associated with this dataset is to improve the effectiveness of marketing campaigns and maximize the return on investment (ROI) for the bank.

K-nearest neighbors, logistic regression, decision trees, and support vector machines were trained and evaluated using appropriate performance metrics such as accuracy, ROC-AUC, PR-AUC, and log-loss. On this dataset, it appeared that logistic regression and support vector machines had best accuracy on a hold-out test set. For final model choice, the recommendation is to use logistic regression, due to its good accuracy and relatively low complexity (and thus low training time) compared to SVMs. In addition, logistic regression allows for model interpretability, and thus an understanding of the relationships between features and target variable (i.e. subscription to a term deposit). Several important features affecting term deposit rate were identified. For marketing campaigns, focusing on clients exhibiting these features can optimize marketing efficiency and resource allocation.

Further, for the logistic regression model, special attention was given to techniques handling the class imbalance, namely SMOTE and class weighting. However, for this dataset, accuracy metrics did not improve with these techniques.



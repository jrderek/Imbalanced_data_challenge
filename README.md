# Imbalanced_data_challenge

This task was geared towards performing a multiclass classification task on an imbalanced multiclass data with large amount of columns thats also needs to be reduce.

Python libraries such as Seaborn, Matplotlib, Pandas, Numpy and Sci-kit learn were fully utilized for this project.

SUMMARY OF BUILDING A MULTICLASS CLASSIFIER

The aim of this task was to perform a multiclass classification task on a dataset that comprised of both categorical and numeric columns and that is also imbalanced.

The following steps were carried out to accomplish the task:

• Data Exploration – this was done to perform statistical summary on the training data and further check the class and data distribution.

• Data pre-processing – this was done to prepare that training data for dimensionality reduction. Basically, here the categorical data were one-hot encoded into binary columns and thereafter, the entire independent features were standardized to have mean of zero and standard deviation of One.

• Dimensionality Reduction – this was performed by Principal Component Analysis (PCA) which is basically used to reduce the dimensionality of the training dataset while preserving its original structure and relationships so that machine learning models can still learn from them and be used to make accurate predictions.

• Creation of a Baseline Model – this model was used as the basis of comparison to other optimized model results.

• Implementation of Oversampling Method and Machine Learning Algorithm: • Approach 1 – Oversampling of the imbalanced dataset (Borderline – SMOTE) and Implementation of Random Forest Classifier (RDF) – here, Borderline SMOTE was used to oversample the minority class in our data, thereafter, exhaustive grid search was done on RDF to get the best hyperparameter for this multiclass classification.

• Approach 2 – Implementation of Cost Sensitive RDF – Here, exhaustive grid search was done on Weighted RDF to get the best hyperparameters for this multiclass classification task, but the outcome was not different from the baseline model.

• Approach 3 - Oversampling of the imbalanced dataset (Borderline – SMOTE) and Implementation of Linear Discriminant Analysis (LDA) the combination of these two after exhaustive grid search gave better evaluation performance than the baseline on the training dataset.

• Prediction on Test Data – The best model which is Borderline -SMOTE + Random Forest were used to make predictions on the test data. • Save the Test Data in a CSV format – The test data was save into a csv format file. • Evaluation metrics used were recall, precision, f1-score, accuracy and confusion matrix

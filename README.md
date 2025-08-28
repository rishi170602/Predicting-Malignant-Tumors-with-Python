Project Overview
This project focuses on building and comparing machine learning models to classify breast tumors as either Benign (B) or Malignant (M). The analysis is based on a well-known dataset and demonstrates a complete machine learning workflow from data preparation to model evaluation.

Key Project Components
Dataset: The project uses the Breast Cancer Wisconsin (Diagnostic) dataset. This dataset contains 569 instances, each with 30 real-valued features that describe characteristics of cell nuclei from a digitized image of a breast mass. The target variable is the diagnosis, with 357 cases being benign and 212 being malignant.

Data Preprocessing:
The project first checks for missing values in the dataset and confirms there are none.
To prepare the data for the models, it uses StandardScaler to normalize the features. This step is crucial for models like SVM and Logistic Regression, which are sensitive to the scale of the input data.The data is then split into an 80% training set and a 20% testing set to ensure the models are evaluated on unseen data.
Models Trained: You trained and evaluated three different supervised machine learning algorithms for this classification task:
Logistic Regression
Support Vector Machine (SVM) with a linear kernel
Random Forest Classifier

Results and Model Performance
The models were evaluated based on their accuracy on the test set.
Logistic Regression: Achieved an accuracy of 96.49%.
SVM: Also achieved an accuracy of 96.49%.
Random Forest Classifier: This model performed the best, with the highest accuracy of 97.37%. 

The classification report for the Random Forest model provides a more detailed breakdown of its performance:
Precision (Benign): 96%
Recall (Benign): 100%
F1-Score (Benign): 98%
Precision (Malignant): 100%
Recall (Malignant): 93%
F1-Score (Malignant): 96%
Overall Accuracy: 97%
This demonstrates that the Random Forest model was highly effective at correctly identifying both benign and malignant cases, with a perfect precision for predicting malignant tumors.

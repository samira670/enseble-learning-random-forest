# Iris Species Classification Using Random Forest

This script demonstrates the use of a RandomForestClassifier to classify iris species based on the Iris dataset from scikit-learn. The Iris dataset includes measurements like sepal length, sepal width, petal length, and petal width for three species of iris.

## Detailed Explanation

### Data Loading and Preparation
- The Iris dataset is loaded from `sklearn.datasets`.
- The data is then converted into a Pandas DataFrame for ease of manipulation.
- The target labels (species) are extracted and assigned to a separate DataFrame.

### Initial Data Exploration
- The first five records of the features and labels are printed to verify the data loading.

### Data Integrity Check
- The script checks for any missing values in the dataset to ensure data quality.

### Data Distribution
- A count of each species type in the dataset is printed to understand the balance of the dataset.

### Data Splitting
- The data is split into training and testing sets with 20% of the data reserved for testing, ensuring the model is evaluated on unseen data.

### Model Training
- A RandomForestClassifier with 200 trees is trained on the training dataset.

### Prediction and Evaluation
- The trained model is used to predict species on the test set.
- The model's performance is evaluated using precision, recall, and F1-score for each class, which provides insights into the model's accuracy and ability to generalize.

### Outputs
- Both the actual and predicted labels for the test data are printed to compare the model's predictions against the true values.

## Conclusion
The script effectively demonstrates the process of training a machine learning model with scikit-learn, evaluating its performance, and interpreting the results.

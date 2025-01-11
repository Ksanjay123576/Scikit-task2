Name: K SANJAY

Company: CODTECH IT SOLUTIONS

ID: CT6WECF

Domain: Python programming

Duration: Dec 17 2024 to Jan 17 2025

Mentor: N.SANTHOSH

**overview of the code:**

**Key Steps:**

Dataset Loading:

The Iris dataset, included in scikit-learn, is loaded.

**It contains 150 samples, with each sample having:** 4 features: Sepal length, Sepal width, Petal length, Petal width.
1 target: The species of the flower (Setosa, Versicolor, or Virginica).

**Data Preparation:**

The data is split into features (X) and target (y).
X contains the flower dimensions.
y contains numeric labels corresponding to the species (0 = Setosa, 1 = Versicolor, 2 = Virginica).
The data is split into training (80%) and testing (20%) sets using train_test_split.

**Model Training:**

A Random Forest Classifier (an ensemble learning algorithm) is used to train the model on the training data.
Random Forest works by constructing multiple decision trees and outputting the majority class prediction.

**Model Testing and Evaluation:**

The model predicts the species for the testing data.

**Metrics evaluated:**

Accuracy: The percentage of correct predictions.

Classification Report: Precision, recall, and F1-score for each class.
Confusion Matrix: A matrix showing the true vs. predicted class counts.

**Prediction Example:**

A sample input [5.1, 3.5, 1.4, 0.2] is passed to the trained model.
The model predicts the species based on this input.
Key Libraries and Functions

**scikit-learn:**

load_iris: Loads the Iris dataset.
train_test_split: Splits data into training and testing sets.
RandomForestClassifier: A machine learning algorithm for classification tasks.
accuracy_score: Measures the overall accuracy of the model.
classification_report: Provides a detailed performance breakdown.
confusion_matrix: Displays true vs. predicted labels in a matrix format.

**pandas:**

Used to create a DataFrame from the dataset for easier understanding and processing.
Outputs

**Accuracy Score** A numeric value showing how well the model performed on the test data.

**Classification Report:** A detailed breakdown of the model's performance for each class (precision, recall, F1-score).

**Confusion Matrix:** A summary of the prediction results.

**Sample Prediction:** The species predicted for a given set of flower dimensions.
Highlights

**Simplicity:** The Iris dataset is small and easy to understand, making it ideal for learning classification.

**Versatility:** The code can be adapted to any other dataset or model (e.g., SVM, KNN).

**Evaluation:** Provides both numeric and visual insights into the model's performance.

![Screenshot (80)](https://github.com/user-attachments/assets/ad922b00-fc34-4b72-b8c7-6bc7beb192e2)

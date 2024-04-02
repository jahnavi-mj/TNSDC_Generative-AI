# Churn Prediction in Telecom Industry using CNN

Overview
This project aims to predict customer churn in the telecom industry using a Convolutional Neural Network (CNN) algorithm. The dataset used in this project contains various features related to customer behavior and usage patterns.

# Modelling

1.Data Preparation: Prepare the dataset, including cleaning, preprocessing, and splitting
into training, validation, and test sets.

2.Model Architecture: Design a CNN architecture suitable for the churn prediction task,
considering factors like convolutional layers, pooling layers, and dense layers.

3.Model Compilation: Compile the model with an appropriate loss function (e.g., binary
crossentropy) and optimizer (e.g., Adam).

4.Model Training: Train the CNN model using the training data, specifying the number of
epochs and batch size.

5.Model Evaluation: Evaluate the trained model using the validation set to assess its
performance and adjust hyperparameters if necessary.

6.Final Model Selection: Select the best-performing model based on the validation results.
7.Model Testing: Test the selected model using the test set to evaluate its performance on
unseen data.

8.Performance Evaluation: Evaluate the model's performance using metrics such as
accuracy, precision, recall, F1 score, and ROC-AUC score

# Results

1.Accuracy: The percentage of correctly predicted churn and non-churn
instances. A higher accuracy indicates better overall performance.

2.Precision: The proportion of correctly predicted churn cases among all
predicted churn cases. High precision means that when the model
predicts a customer will churn, it's likely correct.

3.Recall: The proportion of correctly predicted churn cases among all
actual churn cases. High recall means the model is good at capturing
most of the churn cases.

4.F1 Score: The harmonic mean of precision and recall. It provides a
balance between precision and recall.

5.ROC-AUC Score: The area under the Receiver Operating Characteristic
(ROC) curve. It measures the model's ability to distinguish between
churn and non-churn cases. A higher ROC-AUC score indicates better
performance.

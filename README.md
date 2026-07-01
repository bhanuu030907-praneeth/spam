# spam
# Spam Email Detection Using Machine Learning

## Project Overview

This project implements a Spam Email Detection System using Machine Learning and Natural Language Processing (NLP). The objective of the project is to classify messages as either **Spam** or **Ham (Not Spam)** using the Naive Bayes classification algorithm.

The system preprocesses text data, converts textual information into numerical features using CountVectorizer, trains a machine learning model, and predicts whether a given message is spam or not.

---

## Objectives

* To understand the fundamentals of Natural Language Processing.
* To preprocess and analyze text data.
* To implement a spam detection system using Machine Learning.
* To evaluate the performance of the classification model.
* To predict whether a user-provided message is spam or legitimate.

---

## Dataset Information

The project uses the SMS Spam Collection Dataset containing 5,572 messages categorized into:

* **Ham (Not Spam):** 4,825 messages
* **Spam:** 747 messages

The dataset consists of two columns:

* **Label:** Spam or Ham
* **Message:** Text content of the message

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Machine Learning Techniques Used

### Text Processing

* CountVectorizer

### Classification Algorithm

* Multinomial Naive Bayes

### Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## Project Workflow

1. Import required libraries.
2. Load the spam dataset.
3. Perform data preprocessing.
4. Convert labels into numerical values.
5. Split the dataset into training and testing sets.
6. Convert text messages into numerical vectors.
7. Train the Naive Bayes classifier.
8. Evaluate model performance.
9. Predict custom messages.

---

## Results

* Model Accuracy: Approximately 98%–99%
* Successfully classified spam and legitimate messages.
* Generated confusion matrix and classification report.

---

## Sample Prediction

### Input Message

Congratulations! You have won a free iPhone. Click here to claim your prize.

### Output

SPAM

---

## Applications

* Email filtering systems
* SMS spam detection
* Cybersecurity applications
* Fraud detection systems
* Text classification systems

---

## Conclusion

The Spam Email Detection System successfully demonstrates the application of Machine Learning and Natural Language Processing techniques for text classification tasks. The Multinomial Naive Bayes classifier achieved high accuracy and effectively distinguished spam messages from legitimate messages.

---

## Author

Bhanu Praneeth Bonumaddi

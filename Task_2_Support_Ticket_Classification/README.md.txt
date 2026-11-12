# Customer Support Ticket Classification using Machine Learning

## 1. Project Overview

This project uses Machine Learning and Natural Language Processing (NLP) to automatically classify customer support tickets and assign priority levels.

The system helps businesses organize customer complaints, identify issue categories and prioritize support requests.

## 2. Objectives

- Automatically classify customer support tickets.
- Identify ticket categories.
- Predict ticket priority levels.
- Apply NLP techniques to text data.
- Evaluate machine learning model performance.

## 3. Technologies Used

- Python
- Jupyter Notebook
- Pandas and NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorization
- Matplotlib and Seaborn

## 4. Dataset

Customer Support Ticket Dataset downloaded from Kaggle.

Dataset features include:
- Ticket Description
- Ticket Subject
- Ticket Type
- Ticket Priority
- Ticket Status
- Customer Information

## 5. Data Preprocessing

The following preprocessing techniques were applied:

- Removal of missing values.
- Removal of duplicate records.
- Conversion of text into lowercase.
- Removal of punctuation and numbers.
- Stopword removal.
- Combining ticket subject and description.

## 6. Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) was used to convert textual ticket information into numerical features suitable for machine learning.

## 7. Machine Learning Models

Two classification tasks were implemented:

**Category Classification**
- Logistic Regression
- Linear Support Vector Classification (LinearSVC)

**Priority Classification**
- Logistic Regression
- Linear Support Vector Classification (LinearSVC)

## 8. Model Evaluation

Final LinearSVC evaluation results:

| Classification Task | Accuracy |
|---|---:|
| Ticket Category | 20.25% |
| Ticket Priority | 25.15% |

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The achieved performance is close to the class-frequency baseline. This indicates that the dataset's text features have limited predictive information for the supplied labels. Further dataset investigation and improved feature engineering are needed.

## 9. Business Applications

This system can help businesses:

- Organize incoming customer support tickets.
- Identify different customer issues.
- Assist support teams in prioritizing requests.
- Reduce manual ticket sorting.
- Improve support workflow management.

Predictions should be reviewed by support staff before being used for operational decisions.

## 10. Project Limitations

- Model accuracy is currently low.
- Ticket descriptions may not contain sufficient information to predict the labels.
- More informative and consistently labelled training data is required.
- Further model improvement is necessary before real-world deployment.

## 11. Conclusion

This project demonstrates an NLP-based machine learning approach for customer support ticket classification and priority prediction.

It covers text preprocessing, TF-IDF feature extraction, classification model training and model evaluation.

The results highlight the importance of dataset quality in developing reliable machine learning systems.
ss
## 12. Author

Developed as part of the Future Interns Machine Learning Internship.

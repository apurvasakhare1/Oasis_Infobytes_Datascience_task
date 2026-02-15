🌸 Email Spam Detection using SVM - 

This project implements a Machine Learning solution to classify SMS or email messages as either Ham (legitimate) or Spam. 
It utilizes Natural Language Processing (NLP) for text representation and Support Vector Machines (SVM) for high-accuracy classification.

📌 Project Overview
Spam detection is a critical component of modern communication platforms. This project automates the filtering process by analyzing 
word patterns and frequencies to identify malicious or unwanted content.

📂 Dataset
The project uses the SMS Spam Collection Dataset, which consists of:
Target: label (Ham/0 or Spam/1)

Feature: message (The raw text of the email/SMS)
🛠️ Technologies Used
Python: Core logic and scripting.
Pandas: Data cleaning and manipulation.
Scikit-learn: For TF-IDF Vectorization and SVM Modeling.
Matplotlib & Seaborn: For visualizing the confusion matrix and data distribution.

🤖 Machine Learning Workflow
Data Preprocessing: Handled latin-1 encoding and renamed columns for clarity.
Feature Extraction: Used TF-IDF (Term Frequency-Inverse Document Frequency) to convert text into numerical vectors.
Model Selection: Implemented Support Vector Machine (SVM) with a linear kernel, known for its superior performance in text classification 
tasks.
Evaluation: Measured performance using Accuracy, Precision, Recall, and a Confusion Matrix.

🚀 How to Run
Clone the repository:
bash
git clone https://github.com
Use code with caution.

Install dependencies:
bash
pip install pandas scikit-learn matplotlib seaborn
Use code with caution.

Execute the script:
bash
python spam_detection.py
Use code with caution.

📊 Results
Accuracy: Typically achieves ~98% on the test set.
Robustness: Highly effective at identifying spam keywords while minimizing "false positives" (legitimate emails marked as spam).

🏁 Conclusion
The project highlights the strength of SVM in handling high-dimensional text data. By converting raw language into mathematical features, we can build a robust system capable of protecting users from digital noise and phishing threats.

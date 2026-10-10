**Phishing Email Detection System:**



**Project Overview:**

This project uses Machine Learning and Natural Language Processing (NLP) to classify emails as phishing or legitimate. It applies TF-IDF (Term Frequency–Inverse Document Frequency) for text feature extraction and a Random Forest classifier for email classification.



The goal is to explore how machine learning can support phishing email detection and help identify potentially malicious messages.



**Objectives:**

\- Explore and preprocess email text data.

\- Convert email text into numerical features using TF-IDF.

\- Train a Random Forest classification model.

\- Evaluate the model's ability to distinguish phishing emails from legitimate emails.



**Technologies Used:**

\- Python

\- Jupyter Notebook

\- Pandas

\- NumPy

\- Scikit-learn

\- Natural Language Processing (NLP)

\- TF-IDF Vectorization

\- Random Forest Classifier



**Repository Contents:**

|**File**|**Description**|
|-|-|
|phishing\_email\_detection.ipynb|Notebook containing the machine learning workflow|
|cleaned\_phishing\_emails.csv|Cleaned email dataset|
|phishing\_validation\_emails.csv|Email validation dataset|
|.gitignore|Specifies files Git should ignore|



**How It Works:**

1\. Load and explore the email dataset.

2\. Preprocess the email text.

3\. Extract numerical text features using TF-IDF.

4\. Train a Random Forest classifier.

5\. Evaluate the classification results.



**Getting Started:**



**1.Clone the repository:**



```bash

git clone https://github.com/shreyapradhan-alt/phishing-email-detection-system.git

cd phishing-email-detection-system

```



**2.Install the required libraries:**



```bash

pip install pandas numpy scikit-learn jupyter

```



**3.Launch Jupyter Notebook:**



jupyter notebook



Open phishing\_email\_detection.ipynb and run the notebook cells in order.



**Project Status:**

This repository contains the initial machine learning implementation. Evaluation metrics and further improvements can be documented after reviewing the notebook's actual results.



**Disclaimer:**

This project is intended for educational and research purposes. Its predictions should not be treated as a substitute for professional email security tools.



Author

Shreya Pradhan

GitHub: shreyapradhan-alt


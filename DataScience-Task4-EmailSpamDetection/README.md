# Email Spam Detection using Machine Learning

**Oasis Infobyte Data Science Internship (OIBSIP) – Task 4**

## Project Overview

This project focuses on building an Email Spam Detection system using Natural Language Processing (NLP) and Machine Learning techniques. The objective is to classify SMS messages as **Spam** or **Ham (Not Spam)** by preprocessing the text, extracting meaningful features using TF-IDF Vectorization, and training multiple classification models.

---

## Objective

- Perform text preprocessing and cleaning.
- Convert text data into numerical features using TF-IDF.
- Train multiple machine learning models for spam classification.
- Evaluate model performance using standard classification metrics.
- Compare different models to identify the best-performing classifier.

---

## Project Structure

```
DataScience-Task4-EmailSpamDetection/
│
├── dataset/
│   └── spam.csv
│
├── Email_Spam_Detection.ipynb
├── requirements.txt
└── README.md
```

---

## Dataset

**Dataset:** SMS Spam Collection Dataset

| Column | Description |
|--------|-------------|
| label | Message category (Spam or Ham) |
| message | SMS message content |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- WordCloud
- Jupyter Notebook

---

## Methodology

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Text Preprocessing
5. TF-IDF Feature Extraction
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Word Cloud Visualization
10. Model Comparison

---

## Machine Learning Models

The following classification algorithms were implemented and compared:

- Multinomial Naive Bayes
- Logistic Regression
- Linear Support Vector Machine (Linear SVM)

---

## Evaluation Metrics

The models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

---

## Visualizations

The project includes the following visualizations:

- Class Distribution
- Confusion Matrix
- Word Cloud for Ham Messages
- Word Cloud for Spam Messages
- Model Performance Comparison

---

## Results

- Successfully classified SMS messages into Spam and Ham categories.
- Achieved high classification performance using TF-IDF features.
- Compared multiple machine learning models to determine the most effective approach.
- Demonstrated the effectiveness of NLP techniques for text classification tasks.

---

## Future Enhancements

- Implement Deep Learning models such as LSTM or BERT.
- Deploy the model using Flask or Streamlit.
- Train on larger and more diverse datasets.
- Develop a real-time spam detection application.

---

## Installation

Clone the repository and install the required dependencies.

```bash
git clone https://github.com/<your-username>/OIBSIP.git
cd DataScience-Task4-EmailSpamDetection
pip install -r requirements.txt
```

---

## Author

**Biswajit Senapati**

B.Tech in Computer Science and Engineering  
ITER, Siksha 'O' Anusandhan (Deemed to be University)

---

## Acknowledgement

This project was completed as part of the **Oasis Infobyte Data Science Internship (OIBSIP)**.

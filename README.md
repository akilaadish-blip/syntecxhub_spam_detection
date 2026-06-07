📩 Spam Detection System

A modern Machine Learning + NLP Spam Detection Dashboard built using HTML, CSS, JavaScript, Chart.js, and Scikit-Learn concepts. This project demonstrates the complete workflow of spam message classification, from text preprocessing and vectorization to model evaluation and live prediction.

⸻

🚀 Project Overview

This project simulates a production-style spam detection system capable of classifying SMS or email messages as:

* ✅ Ham (Legitimate Message)
* 🚨 Spam (Unwanted Message)

The dashboard provides:

* Interactive project overview
* NLP processing pipeline visualization
* Exploratory Data Analysis (EDA)
* Model comparison metrics
* Feature importance analysis
* Live spam detection simulator

⸻

📊 Dataset

The project is based on the SMS Spam Collection Dataset.

Dataset Statistics

Metric	Value
Total Messages	5,572
Ham Messages	4,825
Spam Messages	747
Vocabulary Size	8,692
Missing Values	0

⸻

🧠 Machine Learning Pipeline

1. Data Loading

* Load SMS dataset
* Encode labels:
    * Ham → 0
    * Spam → 1

2. Text Preprocessing

* Lowercasing
* Removing punctuation
* Stopword removal
* Tokenization
* Optional stemming / lemmatization

3. Feature Engineering

* CountVectorizer
* TF-IDF Vectorization
* Unigrams & Bigrams

4. Model Training

* Multinomial Naive Bayes
* Logistic Regression
* Linear SVM
* Random Forest

5. Evaluation

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

6. Deployment Ready Pipeline

* Pipeline Serialization
* Joblib/Pickle Support
* Reusable Prediction API

⸻

📈 Model Performance

Model	Accuracy	Precision	Recall	F1 Score
Multinomial Naive Bayes	98.4%	99.1%	95.6%	97.3%
Logistic Regression	97.9%	97.8%	94.2%	96.0%
SVM (LinearSVC)	98.0%	98.2%	93.8%	95.9%
Random Forest	97.2%	99.4%	87.6%	93.1%

🏆 Best Performing Model: Multinomial Naive Bayes

⸻

📉 Exploratory Data Analysis

The dashboard includes:

Class Distribution

* Ham vs Spam ratio

Message Length Analysis

* Character count distribution

Word Count Distribution

* Token count comparison

Spam Keyword Frequency

Examples:

* free
* win
* claim
* prize
* urgent
* cash
* offer

⸻

🔍 Top Spam Indicators

Word	Importance
free	92%
win	89%
claim	87%
prize	85%
urgent	83%
click here	81%
txt stop	80%
cash	78%
guaranteed	76%
offer	74%

⸻

✅ Top Ham Indicators

Word	Importance
ok	88%
going	84%
will	82%
tomorrow	80%
come	78%
home	76%
love	74%
sorry	72%
good	70%
thanks	68%

⸻

⚡ Live Spam Detector

The project contains an interactive detector that analyzes:

* Spam keywords
* Capitalized words
* Phone numbers
* Currency symbols
* URLs / Click prompts
* Message length
* Exclamation count

Example Spam Message

Congratulations! You've won a FREE prize.
Click here to claim your £1000 reward now.
Call 08000 now! URGENT!

Output:

Prediction: SPAM
Confidence: 97.3%

⸻

🛠 Technologies Used

Frontend

* HTML5
* CSS3
* JavaScript (ES6)

Visualization

* Chart.js

Machine Learning Concepts

* Scikit-Learn
* TF-IDF
* CountVectorizer
* Naive Bayes
* Logistic Regression
* SVM
* Random Forest

NLP

* NLTK
* Tokenization
* Stopword Removal
* Stemming
* Lemmatization

⸻

📂 Project Structure

Spam-Detection-System/
│
├── index.html
├── README.md
│
├── assets/
│   ├── screenshots/
│   └── images/
│
├── data/
│   └── spam.csv
│
├── models/
│   └── spam_classifier.pkl
│
└── notebooks/
    └── spam_detection.ipynb

⸻

🎯 Key Features

✔ Modern Cyberpunk Dashboard UI

✔ Interactive Navigation

✔ Dynamic Charts & Analytics

✔ NLP Workflow Visualization

✔ Confusion Matrix Analysis

✔ Feature Importance Tracking

✔ Live Spam Classification Simulator

✔ Responsive Design

⸻

Future Improvements

* Real model integration with Flask/FastAPI
* Email spam detection support
* Deep Learning (LSTM/BERT)
* Real-time API prediction
* User authentication dashboard
* Deployment on Render/Vercel

⸻

👨‍💻 Author

Akil Aadish

Built as part of the SyntecxHub Machine Learning Project Series.

⸻

⭐ Support

If you found this project useful:

* Star the repository ⭐
* Fork the project 🍴
* Share feedback 🚀

Happy Coding
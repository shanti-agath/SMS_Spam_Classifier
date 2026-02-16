📩 SMS Spam Classifier
-------
This project is a Machine Learning based SMS Spam Detection system that classifies messages as Spam or Ham (Not Spam) using Natural Language Processing (NLP) techniques and a Naive Bayes classifier.

🚀 Project Objective

To build a model that can automatically detect whether an SMS message is spam or not, helping reduce unwanted and fraudulent messages.

🧠 Technologies Used

Python

Pandas, NumPy

Scikit-learn

NLTK

TF-IDF Vectorizer

Multinomial Naive Bayes

Jupyter Notebook

📂 Project Structure
SMS_Spam_Classifier/
│
├── data/
│   └── sms_spam.csv
│
├── notebooks/
│   └── SMS_Spam_Classifier.ipynb
│
├── models/
│   └── spam_model.pkl
│   └── tfidf_vectorizer.pkl
│
├── scripts/
│   └── (future scripts)
│
├── requirements.txt
└── README.md

📊 Dataset

SMS Spam Collection Dataset

Contains labeled SMS messages (spam or ham)

Stored in data/sms_spam.csv

⚙️ How It Works

Load and clean the SMS dataset

Preprocess text (lowercase, remove symbols, remove stopwords, stemming)

Convert text into numerical features using TF-IDF Vectorizer

Split data into training and testing sets

Train model using Multinomial Naive Bayes and Logistic Regression

Evaluate model using accuracy and classification report

Predict spam or ham for new SMS messages

🧪 Model Performance

Accuracy: ~97%

High precision for spam detection

Good recall for ham messages

📝 Example Prediction
test_msgs = [
    "Congratulations! You won a free ticket",
    "Hey, are we meeting today?",
    "Win cash prize now!!!"
]


Output:

ham
ham
spam

▶️ How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/shanti-agath/SMS_Spam_Classifier.git

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Open notebook
jupyter notebook notebooks/SMS_Spam_Classifier.ipynb

4️⃣ Run all cells
🎯 Use Cases

SMS filtering systems

Fraud detection

Email spam detection

NLP learning project

📌 Future Improvements

Create a web app using Flask or Streamlit

Add deep learning model (LSTM)

Improve preprocessing (lemmatization)

Deploy model

👩‍💻 Author

Shanti Agath
Final Year Computer Engineering Student
Interested in AI/ML & Data Science

GitHub: https://github.com/shanti-agath

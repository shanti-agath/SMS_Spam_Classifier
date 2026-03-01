
# 📩 SMS Spam Classifier

This project is a Machine Learning based SMS Spam Detection system that classifies messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and a **Naive Bayes** classifier. 

---

## 🚀 Project Objective

To build a model that can automatically detect whether an SMS message is spam or not, helping reduce unwanted and fraudulent messages. 

---

## 🧠 Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- NLTK  
- TF-IDF Vectorizer  
- Multinomial Naive Bayes  
- Jupyter Notebook   

---

## 📂 Project Structure

```
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
```

---

## 📊 Dataset

- SMS Spam Collection Dataset  
- Contains labeled SMS messages (`spam` or `ham`)  
- Stored in `data/sms_spam.csv`

---

## ⚙️ How It Works

1. Load and clean the SMS dataset 
2. Preprocess text (lowercase, remove symbols, remove stopwords, stemming)  
3. Convert text into numerical features using **TF-IDF Vectorizer**  
4. Split data into training and testing sets  
5. Train model using **Multinomial Naive Bayes** and **Logistic Regression**  
6. Evaluate model using accuracy and classification report  
7. Predict spam or ham for new SMS messages 

---

## 🧪 Model Performance

- Accuracy: **~97%**
- High precision for spam detection  
- Good recall for ham messages  

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/shanti-agath/SMS_Spam_Classifier.git
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Open notebook
```bash
jupyter notebook notebooks/SMS_Spam_Classifier.ipynb
```

### 4️⃣ Run all cells

---

## 🎯 Future Improvements

- Build a web app using Flask or Streamlit  
- Add deep learning model  
- Deploy model  

---

## 👩‍💻 Author

**Shanti Agath**  
Final Year Computer Engineering Student  
Interested in AI/ML & Data Science

GitHub: https://github.com/shanti-agath

# 📧 Spam Email Detection using Machine Learning

A Machine Learning project that classifies SMS or email messages as **Spam** or **Ham (Not Spam)** using **TF-IDF Vectorization** and the **Multinomial Naive Bayes** algorithm.

The model is trained on the SMS Spam Collection dataset and achieves approximately **97–99% accuracy**.

---

## 📌 Project Overview

Spam emails and messages are one of the biggest challenges in digital communication. This project uses Natural Language Processing (NLP) techniques to automatically classify incoming messages as spam or legitimate.

---

## 🚀 Features

- Load and preprocess SMS spam dataset
- Data visualization using Matplotlib
- Text preprocessing using TF-IDF
- Spam classification using Multinomial Naive Bayes
- Model evaluation using Accuracy Score
- Confusion Matrix
- Classification Report
- Save trained model using Pickle
- Load saved model
- Predict custom SMS or email messages

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Pickle

---

## 📂 Project Structure

```
Spam-Email-Detection/
│
├── spam.csv
├── spam_email_detection.py
├── spam_model.pkl
├── vectorizer.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Dataset

Dataset Name:

**SMS Spam Collection Dataset**

Dataset Details

- Total Messages: 5572
- Spam Messages: 747
- Ham Messages: 4825
- Language: English

Dataset Columns

| Column | Description |
|--------|-------------|
| v1 | Message Label (Spam/Ham) |
| v2 | SMS/Email Message |

---

## ⚙️ Machine Learning Workflow

1. Load Dataset
2. Remove Unnecessary Columns
3. Label Encoding
4. Train-Test Split
5. TF-IDF Feature Extraction
6. Train Multinomial Naive Bayes Model
7. Predict Spam Messages
8. Evaluate Performance
9. Save Model
10. Predict Custom Messages

---

## 📈 Model Performance

Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report

Typical Accuracy

```
98%+
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Spam-Email-Detection.git
```

Move into the project folder

```bash
cd Spam-Email-Detection
```

Install required packages

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python spam_email_detection.py
```

---

## 💬 Example Prediction

```
Enter Email/SMS:

Congratulations!
You have won ₹50,000.
Click here to claim.

Prediction : SPAM
Confidence : 99.12%
```

```
Enter Email/SMS:

Hi Rahul,
Meeting starts at 10 AM tomorrow.

Prediction : HAM
Confidence : 98.87%
```

---

## 📦 Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn
- pickle

---

## 🔮 Future Improvements

- Logistic Regression Model
- Support Vector Machine (SVM)
- Random Forest Classifier
- Streamlit Web Application
- Flask API
- Deep Learning (LSTM)
- Email Integration

---

## 🤝 Contributing

Contributions are welcome.

Feel free to fork the repository, improve the project, and create a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sanjay Gandhi**

GitHub: https://github.com/SANJAYGANDHI67

---
⭐ If you found this project helpful, don't forget to star the repository.

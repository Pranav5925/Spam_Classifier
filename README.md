# Spam Email Classifier 📧🚫

## 📌 Project Overview
This project is a Machine Learning-based spam detection system that classifies messages as **Spam** or **Not Spam (Ham)** using Natural Language Processing techniques.

A Naive Bayes classifier is trained on a real-world SMS dataset.

---

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- NLP (Bag of Words)
- Google Colab

---

## 📂 Dataset
- SMS Spam Collection Dataset (`spam.csv`)
- Columns:
  - `label` → spam / ham
  - `message` → text content

---

## ⚙️ Workflow
1. Loaded and cleaned text data
2. Converted text into numerical features using Bag of Words
3. Split data into training and testing sets
4. Trained a Naive Bayes classifier
5. Evaluated model accuracy
6. Tested predictions on custom messages

---

## 📈 Model Performance
- Accuracy: ~97%

---

## ▶️ How to Run
1. Open `spam_classifier.ipynb` in Google Colab
2. Upload `spam.csv`
3. Run all cells

---

## 🧪 Example Prediction
**Input:**  
> "Congratulations! You won a free prize"

**Output:**  
> Spam

---

## 📌 Author
Pranav Suresh Rokade

# 🧠 Fake Job Posting Detection using Machine Learning

## 📌 Project Overview
This project aims to detect fraudulent job postings using Machine Learning techniques.  
It is a **binary classification problem** where:
- 0 → Legitimate Job  
- 1 → Fraudulent Job  

The model analyzes textual data such as job descriptions, requirements, and company profiles to identify suspicious patterns.

---

## 🎯 Objectives
- Detect fake job postings automatically  
- Apply Natural Language Processing (NLP) techniques  
- Convert text into numerical features using TF-IDF  
- Train and compare multiple classification models  
- Build a real-world prediction system  

---

## 📊 Dataset
- Source: Hugging Face  
- Dataset: fake_job_postings_balanced_en  
- Contains job postings with labels (real/fake)  
- Balanced dataset (equal fake and real jobs)

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLP (Text Processing)  

---

## 🔄 Project Workflow

1. Data Loading  
2. Exploratory Data Analysis (EDA)  
3. Data Cleaning & Preprocessing  
4. Feature Engineering (TF-IDF)  
5. Train-Test Split  
6. Model Training:
   - Logistic Regression  
   - Naive Bayes  
7. Model Evaluation  
8. Model Comparison  
9. Prediction System  

---

## 🤖 Models Used

### 🔹 Logistic Regression
- Baseline classification model  
- Predicts probability of fake or real job  

### 🔹 Naive Bayes
- Based on probability theory  
- Works well for text classification  

---

## 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

> Recall is especially important because missing a fake job can be risky.

---

## 🚀 How to Run the Project

### Option 1: Google Colab
1. Open the notebook in Colab  
2. Run all cells in order  
3. View results and predictions  

---

### Option 2: Run Locally

#### Step 1: Clone Repository
```bash
git clone https://github.com/lakshmi-bhuvana/fake-job-detection.git
cd fake-job-detection

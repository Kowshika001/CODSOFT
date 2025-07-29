# CODSOFT  
Data Science Internship Task  

## Credit Card Fraud Detection  

### 📌 Project Overview  
This project detects fraudulent credit card transactions using machine learning.  
Due to the highly imbalanced dataset, SMOTE (Synthetic Minority Oversampling Technique) was used to balance the classes.

---

### 🛠️ Steps Followed  
1. **Loaded dataset** from CSV file  
2. **Checked class distribution** (extremely imbalanced)  
3. **Applied SMOTE** to balance classes  
4. **Trained Logistic Regression model**  
5. **Evaluated model performance** using confusion matrix and classification report  

---

### 📊 Model Results  
- **Accuracy:** ~99%  
- **Precision (Fraud):** ~12%  
- **Recall (Fraud):** ~90%  
- **F1-score (Fraud):** ~22%  

---

### 📂 Files  
- `Credit_Card_Fraud_Detection.ipynb` → Jupyter Notebook with code  
- `creditcard.csv` → Dataset  
- `README.md` → Project documentation  

---

### 🚀 How to Run  
1. Open Jupyter Notebook  
2. Run all cells in `Credit_Card_Fraud_Detection.ipynb`  
3. View accuracy, precision, recall, and F1-score in the output

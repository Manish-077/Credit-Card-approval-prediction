# 💳 Credit Card Approval Prediction
 Demo video link :- https://drive.google.com/file/d/1_JP_3FsO2bLfdcJI2VVeInONvxS64PEp/view?usp=sharing
## 📂 Dataset Information
The project uses two datasets:

### 1️⃣ Application Dataset (`application_record.csv`)
Contains applicant demographic and financial information.

**Features include:**
- Gender  
- Income  
- Occupation  
- Education  
- Family Status  
- Housing Type  
- Number of Children  
- Family Members  
- Employment Duration  

### 2️⃣ Credit Dataset (`credit_record.csv`)
Contains historical credit information.

**Features include:**
- Customer ID  
- Credit Status  
- Monthly Balance Records  

---

## ⚙️ Data Preprocessing
The following preprocessing techniques were applied:
- Handling missing values  
- Duplicate removal  
- Feature engineering  
- Label encoding  
- One‑hot encoding  
- Outlier treatment  
- Feature scaling  

**Generated features:**
- Family Size  
- Income Per Family  
- Employment Flag  

---

## 🤖 Machine Learning Models Used
Three machine learning algorithms were evaluated:

- **Logistic Regression** → Accuracy: **56.25%**  
- **Decision Tree** → Accuracy: **78.82%**  
- **Random Forest** → Accuracy: **83.83%** ✅ *Selected for deployment*

---

## 📊 Model Evaluation Metrics
Metrics used:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

**Results:**

| Model               | Accuracy | Precision | Recall | F1 Score |
|----------------------|----------|-----------|--------|----------|
| Logistic Regression  | 56.25%   | 13.58%    | 50.69% | 21.43%   |
| Decision Tree        | 78.82%   | 31.07%    | 65.61% | 42.17%   |
| Random Forest        | 83.83%   | 37.31%    | 55.01% | 44.47%   |

---

## 🖥 User Interface
The application was developed using **Gradio** and contains:
- Applicant Information Form  
- Prediction Button  
- Approval Status Display  
- SmartBridge Branding  
- White Professional Theme  

**Example outputs:**
- ✅ Credit Card Approved  
- ❌ Credit Card Rejected  

---

## 🛠 Technologies Used
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit‑learn, Matplotlib, Gradio  
- **Environment:** Google Colab  
- **Deployment:** Gradio Public Share Link  

---

## 📈 Results
Random Forest was selected as the final production model due to best performance.

---

## 🔮 Future Enhancements
- SMOTE for class imbalance handling  
- Deep Learning models  
- Explainable AI integration  
- Banking API integration  
- Cloud deployment (AWS, Render, Railway, Hugging Face Spaces)  
- User authentication  
- Multi‑language support  

---

## 👥 Team Members
- Manish Charak  
- Khushi Koul  

---

## 🎯 Objectives Achieved
✅ Automated credit card approval prediction  
✅ Reduced manual verification effort  
✅ Improved consistency in decision making  
✅ Faster application processing  
✅ Interactive web deployment  

# 🧠 AI-Based Medical Diagnosis System for Coronary Artery Disease Detection

This project uses **Artificial Intelligence (AI)** and **Machine Learning (ML)** techniques to predict **Coronary Artery Disease (CAD)** based on patient medical data.  
It demonstrates how AI can assist healthcare professionals in **early diagnosis** and **decision support** using multiple predictive models.

---

## 📋 Project Overview

Coronary Artery Disease (CAD) is one of the leading causes of heart-related illnesses worldwide.  
This project applies AI algorithms such as **Logistic Regression**, **Decision Tree**, and **Random Forest** to analyze patient data and predict the likelihood of CAD.

The system helps identify at-risk patients early, potentially saving lives through timely medical intervention.

---

## 🎯 Objectives

- To develop an **AI-based medical diagnosis system** for CAD detection.
- To preprocess medical data for accurate model training.
- To apply and compare multiple AI algorithms.
- To evaluate model performance using accuracy metrics.

---

## 🧩 Features

- Uses **Three AI algorithms** for prediction.
- **Numerical dataset** with 1,025 patient records.
- Data **preprocessing, cleaning, and scaling** included.
- Provides **accuracy comparison** among models.
- **Easily extendable** to other diseases in the future.

---

## 📂 Dataset Details

- **Dataset Name:** Heart Disease Dataset (Kaggle – JohnSmith88)
- **Total Records:** 1,025
- **Total Attributes:** 14
- **Target Variable:** `target` → (1 = Heart Disease Present, 0 = Not Present)

**Key Features:**
`age`, `sex`, `cp`, `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`, `target`

**📦 Dataset Source:**
[https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

---

## ⚙️ Technologies Used

- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:**
  - pandas
  - numpy
  - scikit-learn
  - matplotlib

---

## 🧠 Algorithms Used

| Algorithm               | Description                                                 |
| ----------------------- | ----------------------------------------------------------- |
| **Logistic Regression** | Binary classification algorithm for disease prediction.     |
| **Decision Tree**       | Splits data based on health attributes for prediction.      |
| **Random Forest**       | Ensemble model that improves accuracy using multiple trees. |

---

## 🚀 How to Run This Project

Follow these simple steps to run the project on your system:

### **1. Clone this repository**

```bash
git clone https://github.com/HafizaDeveloper/AI-Project_AI-Based-Medical-Diagnosis-System.git
```

### **2. Navigate to the project folder**

```bash
cd AI-Project_AI-Based-Medical-Diagnosis-System
```

### **3. Install required dependencies**

Make sure you have **Python 3.x** installed. Then run:

```bash
pip install -r requirements.txt
```

If you don’t have a `requirements.txt` file, install manually:

```bash
pip install pandas numpy scikit-learn matplotlib
```

### **4. Open the project**

Use **Jupyter Notebook** or **VS Code** to open the file:

```bash
AI Project & Presentation_Coronary Heart Disease.ipynb
```

### **5. Run all cells**

Run the notebook step-by-step:

- Load dataset
- Preprocess data
- Train models
- View accuracy and predictions

---

## 🧾 Folder Structure

```
Medical-Diagnosis-System---Group-05---Mahnoor---Dua-Kulsoom/
│
├── heart.csv # Dataset file
├── AI Project & Presentation_Coronary Heart Disease.ipynb # Jupyter Notebook (main project code file)
├── AI Presentation-Medical Diagnosis System.pptx # Presentation (PowerPoint) file
├── Report as Lab Manual_AI Project-Medical Diagnosis System.docx # Project documentation/Detailed Project Report
├── README.md # User guide
└── requirements.txt # List of required Python libraries
```

---

## 🩺 Model Prediction Output

After training, the model can make predictions based on the given medical input parameters.

**Output:**

```bash
1. Logistic Regression Accuracy: 0.809756
2. Decision Tree Accuracy: 0.873171
3. Random Forest Accuracy: 0.926829
```

> 🧠 _Patient likely to have Coronary Artery Disease (Yes/No)_  
> Based on features such as age, chest pain type, cholesterol level, blood pressure, and heart rate.

---

## 📈 Results

| **Model**           | **Accuracy (%)** |
| ------------------- | ---------------- |
| Logistic Regression | ~81%             |
| Decision Tree       | ~87%             |
| Random Forest       | ~92%             |

**✅ Random Forest** achieved the **highest accuracy (92%)**.

---

## 📚 Future Enhancements

- Include more diseases like **Diabetes**, **Liver Disease**, etc.
- Integrate **Deep Learning** models for better performance.
- Build a **web-based interface** using **Streamlit** or **Flask**.
- Use larger and more diverse datasets for improved generalization.

---

## 👩‍💻 Authors

**Dua Kulsoom (37)**  
**Mahnoor M. Ayub (57)**  
_BBSUL - BSCS – 6th Semester, Section A, 14th Batch_  
Department of Computer Science

---

## 🪙 License

This project is created for **academic and learning purposes**.  
Feel free to use it for **educational projects** or extend it for **research** with proper credit.

---

### 🌟 If you like this project, give it a ⭐ on GitHub!

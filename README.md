# **❤️ Detect Heart Disease using Machine Learning**  

## 📌 **Project Overview**  
This project predicts whether a patient has heart disease using machine learning models trained on clinical patient data. The dataset contains various health parameters such as blood pressure, cholesterol levels, and ECG results.  

---

## **🛠 Features**  
✅ **Loads dataset from GitHub automatically**  
✅ **Exploratory Data Analysis (EDA) with visualizations**  
✅ **Data preprocessing (handling missing values, feature scaling)**  
✅ **Trains a Random Forest model for classification**  
✅ **Displays model performance metrics (accuracy, confusion matrix, classification report)**  

---

## **🔹 Technologies Used**  
- **Python** → Data processing and model training  
- **Pandas & NumPy** → Data manipulation  
- **Matplotlib & Seaborn** → Data visualization  
- **Scikit-Learn** → Machine learning model training and evaluation  

---

## **📂 Dataset**  
The dataset is sourced from the GitHub repository:  
🔗 [Dataset CSV](https://raw.githubusercontent.com/ujjwalr03/detect-heart-disease/main/dataset.csv)  

### **Columns Description:**  
| Feature                 | Description | Data Type |  
|-------------------------|------------|-----------|  
| age                     | Age in years | Numeric |  
| sex                     | 0 = Female, 1 = Male | Binary |  
| chest pain type         | 1 = Typical Angina, 2 = Atypical Angina, 3 = Non-Anginal Pain, 4 = Asymptomatic | Nominal |  
| resting blood pressure  | Resting BP (mm Hg) | Numeric |  
| serum cholesterol       | Cholesterol (mg/dL) | Numeric |  
| fasting blood sugar     | 1 = >120 mg/dL, 0 = Normal | Binary |  
| resting ECG results     | 0 = Normal, 1 = ST-T abnormality, 2 = LVH | Nominal |  
| max heart rate achieved | 71–202 BPM | Numeric |  
| exercise induced angina | 0 = No, 1 = Yes | Binary |  
| oldpeak                | ST depression | Numeric |  
| ST slope               | 1 = Up, 2 = Flat, 3 = Down | Nominal |  
| **class target**        | 0 = Normal, 1 = Heart Disease | Binary |  

---

## **💻 How to Run the Project**  

### **1️⃣ Run Locally**  
#### **Clone the Repository**  
```bash
git clone https://github.com/ujjwalr03/detect-heart-disease.git
cd detect-heart-disease
```
#### **Install Dependencies**  
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
#### **Run the Python Script**  
```bash
python detect-heart-disease.py
```

---

### **2️⃣ Run on Google Colab**  
Click the button below to open the notebook in Google Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ujjwalr03/detect-heart-disease/blob/main/detect-heart-disease-colab.ipynb)  

### **Steps in Google Colab**  
1. Click **"Open in Colab"** above.  
2. Run all cells sequentially.  
3. The dataset loads automatically from GitHub.  
4. The model is trained and evaluated in real time.  

---

## **📜 License**  
This project is open-source under the **MIT License**.  

---

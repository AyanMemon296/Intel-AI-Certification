
# 🎯 Predictive Lead Conversion AI
📁 Project Folder under `Intel-AI-Certification`  
👨‍💻 Created by: Ayan Memon

---

## 📌 Project Objective

This project uses metadata such as user behavior, engagement patterns, and demographic signals to predict whether a lead will convert (i.e., become a customer). The model helps optimize marketing strategies and decision-making by focusing on leads with higher conversion potential.

---

## 📂 Folder Structure

```

Predictive-Lead-Conversion-AI/
├── 01_Data_Exploration.ipynb
├── 02_Data_Preprocessing.ipynb
├── 03_Model_Training.ipynb
├── 04_Model_Evaluation.ipynb
├── 05_Model_Deployment.ipynb
├── 06_Prediction_Demo.ipynb
├── lead_model.pkl
├── model.joblib
├── model_columns.pkl
├── leads.csv
├── requirements.txt
└── README.md

````

---

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Joblib / Pickle

---

## ✅ Steps Performed

### 1. Data Exploration (`01_Data_Exploration.ipynb`)
- Loaded and visualized sample dataset
- Understood patterns between features like `Time on Site`, `Device`, and `Conversion`

### 2. Data Preprocessing (`02_Data_Preprocessing.ipynb`)
- Dropped unnecessary columns
- Applied one-hot encoding to categorical features
- Handled missing values

### 3. Model Training (`03_Model_Training.ipynb`)
- Trained a **Logistic Regression** model
- Split the data into train and test sets

### 4. Model Evaluation (`04_Model_Evaluation.ipynb`)
- Evaluated using:
  - Accuracy
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)

### 5. Model Deployment (`05_Model_Deployment.ipynb`)
- Saved trained model to disk as:
  - `lead_model.pkl` (Pickle format)
  - `model.joblib` (Joblib format)
- Also saved the column names as `model_columns.pkl`

### 6. Prediction Demo (`06_Prediction_Demo.ipynb`)
- Loaded saved model and column names
- Entered new lead data
- Got prediction as: ✅ "Converted" or ❌ "Not Converted"

---

## 🧪 Example Prediction Output

If the following input is provided:

```python
{
  'Time on Site (min)': 10,
  'Pages Visited': 6,
  'Source_Google Ads': 1,
  'Source_Linkedin': 0,
  'Source_Referral': 0,
  'Device_Mobile': 1
}
````

➡️ The model might predict:
**Predicted Conversion: Yes**

---

## 📚 Use Case

Businesses can use this AI model to:

* Score leads based on conversion probability
* Improve campaign targeting
* Focus sales efforts on high-potential leads

---

## 🔐 Note

This is a basic simulation project using dummy metadata for academic demonstration under the **Intel® AI for Manufacturing** course. It can be extended to real CRM datasets and more advanced models.

---

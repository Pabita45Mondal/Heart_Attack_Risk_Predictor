
# ❤️ Heart Attack Risk Prediction using AutoML (EvalML)

This project predicts the likelihood of a heart attack using **AutoML** techniques powered by **EvalML**.
It automates the end-to-end machine learning workflow — from data preprocessing to model selection, training, and evaluation — enabling efficient, accurate predictions with minimal manual tuning.

---

## 🚀 Project Overview

Heart disease remains one of the leading causes of death worldwide. Early detection through data-driven insights can significantly improve patient outcomes.
This project leverages **AutoML** to build a predictive model that identifies individuals at risk of a heart attack based on clinical and demographic attributes.

The model automatically:

* Handles data preprocessing
* Selects the best ML algorithms
* Tunes hyperparameters
* Evaluates performance metrics

---

## 🧠 Key Features

* Automated Machine Learning with **EvalML**
* Data preprocessing and feature engineering
* Multiple model comparisons
* Performance evaluation using accuracy, F1-score, and ROC-AUC
* Visualization of predictions and model performance
* Easy-to-extend notebook for future improvements

---

## 📊 Dataset

**File:** `heart.csv`
**Description:** Contains clinical and health-related data for individuals.
Each record includes various attributes such as age, sex, cholesterol level, and more.

**Key Features:**

| Feature  | Description                                    |
| -------- | ---------------------------------------------- |
| age      | Age of the individual                          |
| sex      | Gender (1 = male, 0 = female)                  |
| cp       | Chest pain type                                |
| trestbps | Resting blood pressure                         |
| chol     | Serum cholesterol in mg/dl                     |
| fbs      | Fasting blood sugar > 120 mg/dl                |
| restecg  | Resting electrocardiographic results           |
| thalach  | Maximum heart rate achieved                    |
| exang    | Exercise induced angina                        |
| oldpeak  | ST depression induced by exercise              |
| slope    | Slope of the peak exercise ST segment          |
| ca       | Number of major vessels colored by fluoroscopy |
| thal     | Thalassemia type                               |
| target   | 1 = Heart attack risk, 0 = No risk             |

---

## 🧩 Project Structure

```
Heart Attack Prediction - AutoML
│
├── Project Code and Files/
│   ├── heart.csv                            # Dataset
│   └── Heart_Attack_Risk_Predictor with Eval ML.ipynb   # Main notebook
│
└── README.md                                # Project documentation
```

---

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/heart-attack-prediction-automl.git
cd heart-attack-prediction-automl
```

### 2. Install dependencies

It is recommended to use a virtual environment:

```bash
pip install -r requirements.txt
```

If you don’t have a requirements file yet, install manually:

```bash
pip install pandas numpy matplotlib seaborn evalml scikit-learn jupyter
```

### 3. Launch the notebook

```bash
jupyter notebook "Project Code and Files/Heart_Attack_Risk_Predictor with Eval ML.ipynb"
```

---

## 📈 Model Evaluation

The AutoML pipeline automatically compares multiple models and selects the one with the best performance.
Metrics such as:

* **Accuracy**
* **Precision / Recall / F1-score**
* **ROC-AUC**
  are used to evaluate the model.

You can view evaluation outputs directly in the notebook.

---

## 🔍 Results Summary

* The best-performing model was selected automatically by EvalML.
* The model achieved strong accuracy in predicting heart attack risk.
* Insights derived from feature importance indicate which medical parameters most influence predictions.

*(Detailed performance metrics and visualizations can be found in the notebook.)*

---

## 💡 Future Improvements

* Integrate the trained model into a web app using **Streamlit** or **Flask**
* Add real-time prediction API endpoints
* Extend dataset with more patient data for improved generalization
* Deploy the model to cloud services (AWS, GCP, or Azure)

---

## 🧑‍💻 Author

**Developed by:** *[Your Name]*
**GitHub:** [https://github.com/Pabita45Mondal]

---

## 📜 License

This project is licensed under the **MIT License** — see the LICENSE file for details.
?


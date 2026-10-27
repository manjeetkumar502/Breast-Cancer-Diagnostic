# 🩺 Breast Cancer Diagnostic System
### Machine Learning · Python · Streamlit

A machine learning web application for classifying breast tumor measurements as **Benign** or **Malignant**. This project demonstrates supervised learning, model evaluation, and interactive data exploration using Streamlit.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Streamlit-Web%20App-FF4B4B?logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Scikit--learn-Machine%20Learning-F7931E?logo=scikitlearn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Status-Educational%20Project-success" alt="Project status" />
</p>

---

## 📌 Overview

Breast cancer classification is a binary classification task that uses tumor measurements to predict whether a tumor is benign or malignant.

This project uses the Breast Cancer Wisconsin dataset available through Scikit-learn. It trains and compares machine learning models and presents results through an interactive Streamlit dashboard.

### Project Workflow
- Dataset loading and exploration
- Data preprocessing
- Machine learning model training
- Performance evaluation
- Interactive dashboard development

## ✨ Key Features

| Feature | Description |
|---|---|
| 🖥️ Interactive Dashboard | Explore the project using Streamlit |
| 🔬 Tumor Classification | Predict benign or malignant categories |
| 🤖 Multiple ML Models | Compare Logistic Regression, Decision Tree, and Random Forest |
| 📊 Model Analytics | Review model evaluation metrics |
| 🗂️ Dataset Explorer | Explore dataset features and observations |
| 💾 Saved Models | Load trained models without retraining every time |
| 📈 Evaluation Metrics | Review accuracy, precision, recall, F1-score, and ROC-AUC |

## 🛠️ Tech Stack

- **Language:** Python
- **Web Application:** Streamlit
- **Machine Learning:** Scikit-learn
- **Data Processing:** Pandas, NumPy
- **Model Persistence:** Joblib
- **Version Control:** Git and GitHub

## 🧠 Machine Learning Models

| Model | Purpose |
|---|---|
| Logistic Regression | Baseline classification |
| Decision Tree | Learns decision rules from feature values |
| Random Forest | Combines multiple decision trees for prediction |

### 📊 Evaluation Metrics

- **Accuracy:** Percentage of predictions that are correct.
- **Precision:** Proportion of predicted malignant cases that are actually malignant.
- **Recall:** Proportion of actual malignant cases correctly identified.
- **F1-score:** Combines precision and recall.
- **ROC-AUC:** Measures how well a model separates the two classes across classification thresholds.

> **Important:** Evaluation metrics do not establish clinical safety or diagnostic reliability.



## 📂 Project Structure

```text
Breast-Cancer-Diagnostic/
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── models/
│   ├── all_models.joblib
│   ├── best_model.joblib
│   ├── feature_names.joblib
│   ├── model_comparison.csv
│   └── test_metrics.csv
│
└── screenshots/
```

## 🚀 Getting Started

### 1. Open the project folder

Open this project folder in VS Code.

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows Command Prompt:

```cmd
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Launch the application

```bash
streamlit run app.py
```

Open the local address displayed in the terminal. The default address is `http://localhost:8501`.

### 5. Retrain the models (optional)

```bash
python train_model.py
```

The training script should regenerate model artifacts and evaluation results in the `models/` directory, as implemented in the project.

## 🔍 How It Works

1. **Load the dataset:** Use the Breast Cancer Wisconsin dataset from Scikit-learn.
2. **Prepare the data:** Separate input features and target labels.
3. **Train models:** Fit the supported classification algorithms.
4. **Evaluate performance:** Compare models using the implemented evaluation methods.
5. **Select a model:** Use the model-selection criteria in the training script.
6. **Explore predictions:** Interact with the Streamlit dashboard.

## 🎯 Learning Outcomes

This project provides practical experience with:

- Supervised machine learning and binary classification
- Data preprocessing and feature handling
- Cross-validation and train-test evaluation
- Comparing models using multiple metrics
- Saving and loading trained models with Joblib
- Building interactive applications with Streamlit
- Managing code using Git and GitHub

## 🔮 Future Improvements

- Deploy the application online
- Add automated tests
- Improve input validation and error handling
- Add model interpretability and visualizations
- Evaluate models on additional independent datasets

## 👨‍💻 Author

**Manjeet Kumar**

- **GitHub:** https://github.com/manjeetkumar502

**Project credit:** Acknowledgment to the original project contributor and any code or resources reused from the original repository. Add your own improvements and contributions here.

## ⚠️ Medical Disclaimer

This project is intended for educational and demonstration purposes only. It is not a medical device and has not been established as clinically validated. Predictions may be incorrect and must not be used for diagnosis, screening, treatment, or medical decisions. Consult a qualified healthcare professional for medical advice.

---

<p align="center">
  Built with Python, Scikit-learn, and Streamlit.
</p>

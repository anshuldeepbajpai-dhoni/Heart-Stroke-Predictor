# ❤️ Heart Disease Predictor

A Machine Learning web application that predicts the likelihood of heart disease based on clinical and cardiovascular parameters entered by the user.

The project demonstrates an end-to-end Machine Learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, model serialization, and deployment through an interactive web interface.

> **Disclaimer:** This project is intended for educational and demonstration purposes only. Its predictions should not be considered medical advice or a clinical diagnosis.

---

## 🚀 Features

- Interactive web interface for heart disease risk prediction
- Machine Learning-based prediction
- User-friendly input controls
- Supports multiple cardiovascular health parameters
- Fast prediction from user-provided data
- Dark-themed responsive interface
- End-to-end ML workflow from data analysis to deployment

---

## 📋 Input Parameters

The prediction system uses clinical features such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak (ST Depression)
- ST Slope

---

## 🧠 Machine Learning Workflow

The project follows a standard Machine Learning pipeline:

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Preprocessing
5. Model Training
6. Model Evaluation
7. Model Serialization
8. Web Application Integration
9. User Input Prediction

---

## 🛠️ Technologies Used

### Programming
- Python

### Data Analysis
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Plotly
- SheryAnalysis

### Machine Learning
- Scikit-learn

### Web Application
- Streamlit

### Development Tools
- Jupyter Notebook
- VS Code
- Git
- GitHub

---

## 📂 Project Structure

```text
Heart-Disease-Predictor/
│
├── app.py
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── heart_disease_analysis.ipynb
│
└── models/
    └── model.pkl
```

> The exact structure may vary depending on the current version of the project.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/anshuldeepbajpai-dhoni/Heart-Disease-Predictor.git
cd Heart-Disease-Predictor
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

For a Streamlit application:

```bash
streamlit run app.py
```

The application will open in your browser.

Enter the required patient parameters and click **Predict** to generate the model prediction.

---

## 📊 Example Inputs

The application accepts values such as:

```text
Age: 40
Sex: M
Chest Pain Type: ATA
Resting Blood Pressure: 120
Cholesterol: 200
Fasting Blood Sugar: 0
Resting ECG: Normal
Max Heart Rate: 150
Exercise-Induced Angina: Y
Oldpeak: 1.0
ST Slope: Up
```

---

## 🔮 Future Improvements

- Compare multiple ML algorithms
- Hyperparameter tuning
- Cross-validation
- Prediction probability/confidence display
- Model explainability using SHAP
- Improved dashboard and visualizations
- Cloud deployment
- Prediction history
- REST API integration

---

## 👨‍💻 Author

**Anshul Deep Bajpai**

GitHub: `anshuldeepbajpai-dhoni`

---

## ⭐ Support

If you find this project useful, consider giving the repository a star.
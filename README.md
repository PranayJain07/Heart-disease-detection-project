#  Heart Disease Prediction using Machine Learning

This project focuses on predicting the presence of heart disease using machine learning techniques.  
The model is trained on a structured healthcare dataset and aims to assist in early detection by analyzing key medical parameters.  
Such predictive systems can support medical professionals in identifying high-risk patients at an early stage.

---

##  Project Structure
```
Heart-Disease-Prediction
│
├── Heartdisease.ipynb # Jupyter Notebook with EDA, preprocessing & model training
├── heart.csv # Dataset used for training and testing
└── README.md # Project documentation

```

---
##  Dataset Information

The dataset contains medical attributes commonly used to detect heart disease.  
Each record represents a patient with multiple health indicators.

**Key features include:**
- Age  
- Sex  
- Chest pain type  
- Resting blood pressure  
- Cholesterol level  
- Fasting blood sugar  
- Resting ECG results  
- Maximum heart rate achieved  
- Exercise-induced angina  
- ST depression  
- Number of major vessels  

**Target Variable:**
- `0` → No heart disease  
- `1` → Presence of heart disease  

---

##  Technologies Used

- Python  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  

---

##  Machine Learning Workflow

1. **Data Loading**  
   - Loaded the dataset using Pandas and inspected its structure.

2. **Exploratory Data Analysis (EDA)**  
   - Analyzed feature distributions and correlations.  
   - Visualized trends using plots and charts.

3. **Data Cleaning & Preprocessing**  
   - Handled missing values and outliers.  
   - Encoded categorical variables and scaled numerical features.

4. **Feature Selection**  
   - Selected relevant features to improve model performance.

5. **Model Training**  
   - Trained multiple machine learning models on the dataset.

6. **Model Evaluation**  
   - Evaluated models using standard classification metrics.

7. **Prediction & Results**  
   - Compared model outputs to identify the best-performing approach.

---

##  Models Implemented

- Logistic Regression  
- Decision Tree  
- Random Forest  

**Evaluation Metrics Used:**
- Accuracy  
- Confusion Matrix  
- Classification Report  

---

##  Results

The trained models successfully predict heart disease with good accuracy.  
Among all the implemented models, **Random Forest** delivered the best overall performance in terms of accuracy and prediction stability.

---

##  How to Run the Project

1. Clone the repository
```

git clone https://github.com/your-username/heart-disease-prediction.git

```

2. Navigate to the project directory
```

cd heart-disease-prediction

```
3. Open the Jupyter Notebook
```

jupyter notebook Heartdisease.ipynb

```
---

##  Future Scope

- Hyperparameter tuning to further improve accuracy  
- Deployment using Flask or Streamlit  
- Integration with real-time patient data  
- Experimenting with additional ML models  

---

##  Acknowledgements

- Dataset sourced from publicly available healthcare datasets  
- Inspired by real-world medical diagnosis and prediction problems  

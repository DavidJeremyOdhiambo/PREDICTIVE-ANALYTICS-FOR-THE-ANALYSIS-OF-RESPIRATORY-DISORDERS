# Predictive Analytics for the Diagnosis of Respiratory Diseases

## Project Overview

This project focuses on developing a machine learning-based predictive system for the early detection and diagnosis of respiratory diseases using patient medical data.

The system applies data preprocessing, exploratory data analysis (EDA), class balancing techniques, and Support Vector Machine (SVM) classification to predict respiratory conditions accurately.

Additionally, the project includes a graphical user interface (GUI) built using Tkinter for real-time disease prediction.

---

## General Objective

To utilize machine learning algorithms in developing a predictive model that performs early detection and diagnosis of respiratory disorders.

---

## Specific Objectives

1. Collect relevant patient medical data and symptoms.
2. Identify important features for improved prediction accuracy.
3. Evaluate model performance using classification metrics.
4. Develop a predictive model capable of diagnosing respiratory diseases.

---

## Dataset Information

Dataset Used:
- Exasens Dataset

Features Included:
- Imagery Part Minimum
- Imagery Part Average
- Real Part Minimum
- Real Part Average
- Gender
- Age
- Smoking Status

Target Variable:
- Diagnosis

Diagnosis Categories:
- Asthma
- COPD
- Healthy Control (HC)
- Infected

---

## Technologies Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
- Tkinter
- joblib
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection and Loading
- Imported dataset using pandas
- Inspected dataset structure
- Checked missing values and data types

### 2. Data Cleaning and Preprocessing
- Filled missing numerical values using median imputation
- Filled categorical missing values using mode imputation
- Encoded diagnosis labels
- Standardized numerical features

### 3. Exploratory Data Analysis (EDA)
Performed:
- Histograms
- Boxplots
- Correlation heatmaps
- Pairplots
- Class distribution analysis

### 4. Handling Imbalanced Data
Used:
- SMOTETomek

Purpose:
- Balance diagnosis classes
- Improve model performance

### 5. Model Development
Implemented:
- Support Vector Machine (SVM)

Kernel Used:
- Radial Basis Function (RBF)

### 6. Model Evaluation
Evaluation metrics:
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 7. GUI Deployment
Developed a graphical user interface using Tkinter to:
- Accept patient inputs
- Validate user input
- Predict respiratory disease diagnosis

---

## Model Performance

### Accuracy
```text
Accuracy: 1.0000
```

### Classification Results
The model achieved:
- 100% Accuracy
- Perfect Precision
- Perfect Recall
- Perfect F1-Score

The model successfully classified:
- Asthma
- COPD
- Healthy Control
- Infected cases

---

## Visualizations Included

- Histograms
- Boxplots
- Correlation Heatmaps
- Pairplots
- Confusion Matrix

---

## Files Included

- Jupyter Notebook
- Dataset
- Trained SVM model (.pkl)
- Scaler object (.pkl)
- GUI application
- Visualizations
- README documentation

---

## How to Run the Project

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/respiratory-disease-prediction.git
```

### 2. Install Required Libraries
```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook
Open the notebook and execute all cells.

### 4. Run GUI Application
Execute the GUI script to launch the respiratory disease predictor interface.

---

## Future Improvements

- Deploy using Streamlit or Flask
- Integrate deep learning techniques
- Use larger medical datasets
- Improve real-world clinical validation
- Add cloud deployment support

---

## Research Relevance

This project aligns with research in:
- Machine Learning in Healthcare
- Predictive Analytics
- Medical Diagnosis Systems
- Artificial Intelligence in Healthcare

---

## Author

David Jeremy Odhiambo

Data Science Graduate | Machine Learning Enthusiast | AI Researcher

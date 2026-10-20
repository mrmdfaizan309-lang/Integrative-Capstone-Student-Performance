# Student Performance Prediction and Analysis using Data Science

## 📌 Project Overview

This project is an Integrative Capstone Project developed as part of the Data Science with Python internship. The project demonstrates a complete data science workflow using the UCI Student Performance dataset.

The main objective is to analyse student academic performance, identify important patterns, predict final grades using supervised machine learning, and group students using unsupervised learning techniques.

## 🎯 Objectives

- Acquire a publicly available student performance dataset.
- Clean and preprocess the dataset.
- Analyse data quality and identify potential issues.
- Perform Exploratory Data Analysis (EDA).
- Create meaningful visualizations.
- Prepare features for machine learning.
- Predict final student grades using regression models.
- Compare Linear Regression and Random Forest Regression.
- Apply K-Means clustering to identify student groups.
- Evaluate model performance using appropriate metrics.
- Generate insights and practical recommendations.

## 📊 Dataset

The project uses the UCI Student Performance dataset.

- Dataset: Student Performance Dataset
- Subject: Mathematics
- Records: 395 students
- Original columns: 33
- Target variable: G3
- Previous grades: G1 and G2

The dataset contains academic, demographic, family, behavioural, and school-related information about students.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code
- Git
- GitHub

## 🔄 Project Workflow

```text
Data Acquisition
       ↓
Data Cleaning
       ↓
Data Preprocessing
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Supervised Learning
       ↓
Model Evaluation
       ↓
Unsupervised Learning
       ↓
Student Clustering
       ↓
Insights & Recommendations
```

## 🤖 Machine Learning Models

### Supervised Learning

The following regression models were implemented:

1. Linear Regression
2. Random Forest Regression

The target variable for prediction is the final student grade `G3`.

### Unsupervised Learning

K-Means Clustering was used to group students based on their numerical academic and behavioural characteristics.

PCA was used to visualize the resulting clusters in two dimensions.

## 📈 Model Evaluation

The best performing supervised model was Random Forest Regression.

| Metric | Random Forest |
|---|---:|
| MAE | 1.174 |
| RMSE | 1.964 |
| R² Score | 0.812 |

The R² score of 0.812 indicates that the model explains approximately 81.2% of the variation in final grades on the test dataset.

## 🔍 Key Findings

- Student academic performance can be analysed using multiple academic and behavioural variables.
- Previous grades provide important predictive information for final performance.
- Study behaviour and attendance-related variables provide useful analytical signals.
- Random Forest performed strongly for final-grade prediction.
- K-Means identified three groups of students with similar numerical characteristics.
- Feature importance analysis helped identify influential variables used by the Random Forest model.

## 💡 Recommendations

- Encourage students to maintain consistent study habits.
- Monitor students with high absence levels.
- Identify students who may need additional academic support.
- Use student clusters to develop different support strategies.
- Use predictive models as decision-support tools rather than as the sole basis for educational decisions.
- Collect additional longitudinal educational data for future model improvement.

## 📁 Project Structure

```text
Integrative_Capstone/
│
├── data/
│   ├── student-mat.csv
│   ├── student_performance_cleaned.csv
│   └── student_performance_clustered.csv
│
├── notebooks/
│   └── Week6_Capstone.ipynb
│
├── outputs/
│   ├── charts/
│   └── model_results/
│
├── src/
│
├── requirements.txt
├── README.md
└── Week6_Integrative_Capstone_Report.docx
```

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project

```bash
cd Integrative_Capstone
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/Week6_Capstone.ipynb
```

### 5. Run the notebook

Run the notebook cells from top to bottom to reproduce the data cleaning, analysis, machine learning, clustering, and evaluation results.

## 📌 Limitations

The dataset contains a relatively limited number of student records and represents a specific educational context. The Random Forest model also uses previous grades G1 and G2, which are highly informative for predicting G3.

For early academic prediction, future experiments should evaluate models without G1 and G2.

## 🚀 Future Scope

- Hyperparameter tuning
- Cross-validation
- Additional regression algorithms
- Early-warning prediction without G1 and G2
- Pass/fail classification
- Larger educational datasets
- Web-based prediction dashboard
- Deployment of the trained model

## 👨‍💻 Author

**MD FAIZAN KURAISHI**

Computer Science Engineering  
Data Science with Python Internship

## 📌 Project Status

**Completed ✅**
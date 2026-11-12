# Supply Chain Analysis & Late Delivery Risk Prediction

## 📌 Project Overview

This project focuses on analyzing supply chain operations and predicting late delivery risks using Data Analytics and Machine Learning.

The goal is to identify factors affecting delivery delays, analyze business performance, and build a machine learning model to predict late delivery risks.

## 🎯 Business Objectives

- Analyze order and delivery performance.
- Identify key factors responsible for late deliveries.
- Analyze profitability and operational performance.
- Understand delivery trends across regions and shipping modes.
- Build a machine learning model to predict late delivery risks.
- Support better supply chain and shipping decisions.

## 📊 Dataset

**Dataset:** DataCo Smart Supply Chain Dataset

**Source:** [Kaggle – DataCo Smart Supply Chain](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

Note: The dataset CSV is not included in this repository because of its large file size. Download it from Kaggle and place it in the project folder before running the notebook.

## 🛠️ Technologies & Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

## 🔍 Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Delivery Delay Analysis
5. Profitability Analysis
6. Feature Engineering
7. Model Training and Evaluation
8. Handling Class Imbalance using SMOTE
9. Random Forest Classification

## 🤖 Machine Learning Model

**Algorithm:** Random Forest Classifier

**Target Variable:** Late_delivery_risk

**Techniques Used:**
- Frequency Encoding
- Train-Test Split
- SMOTE for handling class imbalance
- Model Evaluation using Accuracy, Precision, Recall and Classification Report

## 📁 Project Structure

```text
Supply-chain-project/
│
├── Supply_Chain_Analysis.ipynb
├── .gitignore
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/Arjun8595/Supply-chain-project.git
```

2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter
```

3. Download the dataset from Kaggle.

4. Place `DataCoSupplyChainDataset.csv` in the project folder.

5. Open the notebook:

```bash
jupyter notebook
```

6. Run `Supply_Chain_Analysis.ipynb`.

## 👨‍💻 Author

**Arjun**

B.Tech – Production & Industrial Engineering  
Delhi Technological University (DTU)

- [GitHub](https://github.com/Arjun8595)

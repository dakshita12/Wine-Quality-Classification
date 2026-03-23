# Wine Quality Classification



## Overview
This project is a complete implementation of a machine learning pipeline to classify the quality of red wine based on its physicochemical properties. It demonstrates the application of data preprocessing, exploratory data analysis (EDA), feature engineering, and classification models using Scikit-learn.
The goal is to build a reliable model that can predict wine quality and help understand the factors influencing it.


## Features
🔹 Data Analysis & Preprocessing
Handling real-world dataset (winequality-red.csv)
Data cleaning and preparation
Feature exploration and correlation analysis
🔹 Exploratory Data Analysis (EDA)
Visualization using Seaborn and Matplotlib
Understanding relationships between features and target variable
Identifying important features affecting wine quality
🔹 Machine Learning Model
Classification-based approach
Model training using Scikit-learn
Performance evaluation using metrics like accuracy

## Tech Stack
= Language
Python
= Libraries
Pandas (Data manipulation)
NumPy (Numerical operations)
Matplotlib & Seaborn (Visualization)
Scikit-learn (Machine Learning)
= Tools
Jupyter Notebook
VS Code
Virtual Environment (venv)

## Project Structure
Wine-Quality-Classification/
│── winequality-red.csv                                         # Dataset (1,599 rows × 12 features)
│── requirements.txt                                            # Python dependencies
│── Lab 22-Wine Quality Classification by Scikit-Learn.ipynb   # Main notebook
│── README.md

## Setup Instructions
- Clone the repository
git clone https://github.com/dakshita12/Wine-Quality-Classification.git
cd Wine-Quality-Classification
- Create virtual environment
python -m venv wine_quality
wine_quality\Scripts\activate
- Install dependencies
pip install -r requirements.txt

## How to Run
1. Launch Jupyter Notebook: jupyter notebook
2. Open the notebook: Lab 22-Wine Quality Classification by Scikit-Learn.ipynb
3. Select kernel: Python (wine_quality)
4. Run all cells: Kernel → Restart & Run All

## Machine Learning Workflow
- Data Loading
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Model Training
- Model Evaluation

## Acknowledgement
This project uses the Wine Quality dataset available on Kaggle:
- Dataset: Wine Quality Dataset  
- Source: https://www.kaggle.com/datasets/yasserh/wine-quality-dataset  
Special thanks to the dataset contributor for making this data publicly available for learning and research purposes.

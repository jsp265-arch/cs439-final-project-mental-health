# cs439-final-project-mental-health
CS439 Intro to Data Science final project: Predicting student mental health risk using academic and lifestyle indicators.

# CS439 Final Project: Student Mental Health Risk Prediction

This repository contains my final project for CS439: Intro to Data Science at Rutgers University.  
The goal of the project is to predict student mental health risk using academic, lifestyle, and stress-related features from the Student Depression Dataset.

## Contents
- `student_mental_health_analysis.ipynb` — Main notebook with all code  
- `Intro_To_Data_Science_Final_Project.pdf` — Final written report  
- `requirements.txt` — Python libraries needed to run the notebook  

##  Methods
This project follows the full data science workflow:
- Data cleaning and preprocessing with Pandas  
- Feature engineering (sleep deficit, academic score, stress-study ratio, etc.)  
- SQL database creation with multiple linked tables  
- Exploratory data analysis using Matplotlib and Seaborn  
- Machine learning models: Logistic Regression and Random Forest  
- Model evaluation using accuracy, precision, recall, and feature importance  

##  Key Results
- Logistic Regression achieved the highest accuracy (~83 percent)  
- Random Forest identified the most influential features  
- Top predictors included suicidal thoughts, academic score, CGPA, and academic pressure  

## ▶️ How to Run
Install dependencies:
```bash
pip install -r requirements.txt

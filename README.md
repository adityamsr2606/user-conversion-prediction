User Conversion Prediction

>>>About the Project
This project focuses on understanding user behavior on an e-commerce website and predicting whether a user will make a purchase or not. 

The idea is simple: based on how a user interacts with the website (pages visited, time spent, bounce rate, etc.), can we predict if they will buy something?

##  Objective
To build a machine learning model that predicts:
- 1 → User will purchase  
- 0 → User will not purchase  

## Dataset
I used the **Online Shoppers Intention Dataset** from Kaggle.  
It contains real user session data like:
- Number of pages visited  
- Time spent on different pages  
- Bounce rate and exit rate  
- Visitor type (new or returning)

##  What I Did

### 🔹 Data Cleaning & Preprocessing
- Converted categorical data into numerical form  
- Prepared the dataset for machine learning models  

### 🔹 Exploratory Data Analysis (EDA)
- Explored patterns in user behavior  
- Visualized relationships between features  

### 🔹 Model Building
- Started with **Logistic Regression** as a baseline  
- Used **Random Forest** for better performance  

### 🔹 Evaluation
- Measured performance using accuracy and classification metrics  

## Key Insights
- Users who spend more time on product pages are more likely to buy  
- High bounce and exit rates usually mean lower chances of purchase  
- Returning visitors tend to convert more than new users  

## Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

##  How to Run

1. Install required libraries:

User Conversion Prediction

>>>This project focuses on understanding user behavior on an e-commerce website and predicting whether a user will make a purchase or not. 

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

## Interactive Visualizations
- Feature Importance: [View Interactive](images/feature_importance_interactive.html)

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

1. Install required libraries:pip install pandas numpy matplotlib seaborn scikit-learn
2. Open the notebook:main.ipynb

## Results
- Logistic Regression achieved an accuracy of 87.06%, serving as the baseline model.

- Decision Tree achieved an accuracy of 85.73%, which is approximately 1.33% lower than Logistic Regression, indicating possible overfitting and instability.

- Random Forest achieved the highest accuracy of 88.97%, outperforming Logistic Regression by approximately 1.91% and Decision Tree by approximately 3.24%.

- The improved performance of Random Forest is due to its ensemble approach, which combines multiple decision trees to capture complex patterns and reduce overfitting.

- Overall, Random Forest proved to be the most effective model for predicting user conversion in this dataset.

 ## Final Insights
- User behavior features such as PageValues, BounceRates, and ProductRelated_Duration play a key role in predicting purchase decisions.

- Lower bounce rates are associated with higher conversion probability, suggesting that improving initial user engagement can increase sales.

- Returning users are more likely to convert, highlighting the importance of retention strategies.

- The superior performance of Random Forest shows that ensemble models are better suited for handling complex user behavior data.

- This model can be used to identify high-intent users and optimize targeted marketing campaigns.

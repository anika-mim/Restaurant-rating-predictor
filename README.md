# Restaurant-rating-predictor

 1. Problem Statement:
The goal is to predict restaurant review ratings based on key business features such as cost, table booking availability, online delivery, and price range. This can help restaurant platforms or businesses understand factors influencing customer ratings.

2. Tech Stack:
Component	Tool
Programming	Python
Libraries	pandas, numpy, sklearn, joblib
Model	SVR / DecisionTree / etc. (based on your notebook)
App Framework	Streamlit
Deployment	Local (can be hosted later via Streamlit Cloud or Heroku)

3. Model Training Summary:
•	Performed EDA and feature encoding
•	Used StandardScaler for feature scaling
•	Trained a regression model to predict review rating
•	Tuned hyperparameters using GridSearchCV
•	Saved model as mlmodel.pkl and scaler as scaler.pkl using joblib

4. Web App Features (Streamlit):
In app.py:
•	Users input:
o	Average cost
o	Table booking (Yes/No)
o	Online delivery (Yes/No)

o	Price range (1 to 4)
•	Backend transforms inputs, scales them, and passes to model
•	App returns a rating category like:
o	Poor, Average, Good, Very Good, or Excellent

Output:
![Output](https://github.com/user-attachments/assets/b8ab8943-688d-4bf2-8c92-ce71ffd4530a)

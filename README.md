# Health_Insurance_Cross_Sell_Prediction

The aim of the project is to ensure that people who have already purchased health insurance are also likely to buy vehicle insurance. Health insurance serves as a form of compensation provided by the company in the event of death, illness, or accidents in exchange for a premium. This project employs a classification model that focuses on understanding the target variables by examining whether people respond with 'yes' or 'no.' It considers various demographics such as age, gender, the age of the vehicle, possession of a driving license, and the amount of annual premium they pay, all of which can influence the responses.

I conducted Exploratory Data Analysis (EDA) by creating various charts, including count plots, bar plots, pie charts, to visualize the relationships between the target variable and independent variables. I showcased the bivariate analysis of the project. Following EDA, I performed feature manipulation and generated a feature importance chart to assess the importance of each feature. Additionally, I plotted a correlation heatmap to better understand the relationships between variables.

Regarding machine learning algorithms, I employed the following:

Logistic Regression
Decision Tree
Random Forest
XGBoost
I trained the dataset using all these algorithms after addressing the imbalance in the relationship of the target variables through oversampling techniques.

The major evaluation metrics I utilized include:

Accuracy
Recall
Precision
F1 Score
ROC-AUC

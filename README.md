# Sky-Insights
The objective of this project is to uncover trends, patterns, and factors influencing air travel behaviors.The project's insights hold potential to inform decision-making processes for airlines, airports, and policymakers, ultimately enhancing efficiency and planning in the aviation industry.
This project follows a supervised learning approach, specifically regression, as historical flight data with labeled ticket prices is available for training the model.

**Data Science Approach**
This project follows a supervised learning approach, specifically regression, as historical flight data with labeled ticket prices is available for training the model.

***Machine Learning Model - End to End***

**Exploratory Data Analysis (EDA)**
Perform exploratory data analysis using Pandas to understand the dataset:
  Display the first few rows.

**Data Visualization (Using SweetViz)**
Create various visualizations to understand data patterns, relationships, and trends.

**Data Preprocessing**
Split the data into training, validation, and test sets to prevent data leakage.
Handle missing values and outliers.

**Data Encoding**
Encode categorical features using techniques like one-hot encoding or label encoding. Scale numerical features using standard scaling.

**Machine Learning Model Selection**
Choose an appropriate machine learning model. In this case, XGBoost is selected for regression.

**Model Training and Evaluation**
Train the selected model using the training dataset. Evaluate the model's performance using metrics such as Root Mean Squared Error (RMSE).

**Conclusion**
The model's RMSE score is 12.5, indicating the accuracy of flight ticket price predictions.

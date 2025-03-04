# Classification-and-Logistic-Regression
 Classification and Logistic Regression: A Case Study on Social Network Ads

Abstract:
This thesis explores the application of logistic regression for binary classification using a dataset from social network advertisements. The objective is to classify users based on their likelihood of purchasing a product given their age. The research details dataset preprocessing, exploratory data analysis, model implementation, performance evaluation, and future improvements in classification models.

1. Introduction
Classification is a fundamental task in machine learning, widely used in applications ranging from medical diagnosis to spam detection. One of the simplest yet effective classification techniques is logistic regression, which models the probability of a binary outcome based on input features. This thesis focuses on applying logistic regression to a dataset containing user age and purchase behavior from social network ads.

2. Dataset and Preprocessing
The dataset contains user information, including Age, Gender, Estimated Salary, and Purchase behavior. However, for simplicity and model efficiency, only the Age feature is considered. The preprocessing steps include:

Removing unnecessary features (Gender, Estimated Salary, and User ID)

Handling missing values (if any)

Splitting data into training and testing sets

3. Exploratory Data Analysis (EDA)
To understand the dataset’s distribution, scatter plots are used to visualize the relationship between age and purchase behavior. The analysis reveals that younger users are less likely to make purchases, whereas older users have a higher probability.

4. Model Implementation
Logistic Regression is implemented using the sklearn library. The steps include:

Splitting data into training (80%) and testing (20%) sets.

Initializing and fitting the logistic regression model.

Predicting outputs and measuring accuracy.

5. Results and Performance Evaluation
The model's accuracy is evaluated using:

Accuracy Score: The percentage of correctly classified instances.

Confusion Matrix: Shows true positives, true negatives, false positives, and false negatives.

Precision, Recall, and F1-score: Measures of classification effectiveness.

The model achieved a reasonable accuracy, showing that logistic regression is effective for binary classification tasks, though improvements can be made with feature engineering.

6. Conclusion and Future Work
This study demonstrates the feasibility of using logistic regression for classifying purchase behavior based on age. Future improvements include:

Adding more features for better classification.

Using advanced models such as decision trees or neural networks.

Applying feature scaling and polynomial regression for improved performance.

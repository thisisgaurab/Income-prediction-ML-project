  # Income Prediction Project
- This project aims to predict income levels based on a dataset containing various features such as age, education, occupation, and more. I use machine learning techniques, specifically a Random Forest Classifier, to make predictions. I have taken the dataset from kaggle for this.

  # Introduction
- In this project, I tackle the problem of predicting income levels based on demographic and employment-related features. The goal is to create a predictive model that can classify individuals into income groups based on their characteristics.

  ## Dataset
- I use the 'income.csv' dataset, which contains the columns such as:
- Age
- Education
- Occupation
- Workclass
- Marital Status
- Relationship
- Race
- Native Country
- Gender
- Income (target variable)
The dataset was obtained from kaggle.

  ## Data Preprocessing
- I preprocess the data to prepare it for machine learning. This includes:
- One-hot encoding of categorical variables.
- Transforming 'gender' and 'income' into binary values (0 or 1).
- Dropping irrelevant or highly correlated features.

   ## Exploratory Data Analysis (EDA)
- I perform EDA to understand the data better. This includes data visualization using libraries such as Matplotlib and Seaborn. I also generate correlation matrices and visualize important relationships in the data.

    ## Machine Learning
- I apply a Random Forest Classifier to build a predictive model. I also use GridSearchCV to tune hyperparameters for better model performance.

    ## Results
- I evaluate the model's performance on a test dataset and report relevant metrics. Additionally, I determine feature importance using the Random Forest model.
  The model achieved an accuracy of 0.86 on the test dataset.
  Here are the top 5 most important features for income prediction:
1. age
2. educational-num
3. capital-gain
4. marital-status
5. hours per week

   ## Contributing
Contributions to this project are welcome! If you would like to contribute, please follow these steps:
1. Fork this repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add feature'`.
4. Push to your branch: `git push origin feature-name`.
5. Create a pull request explaining your changes.

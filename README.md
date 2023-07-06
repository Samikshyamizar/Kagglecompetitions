<h1 style="color: #1f8dd6; text-align: center;">My Machine Learning Journey</h1>
<p style="text-align: center;">This repository documents my personal machine learning journey, mostly including the Kaggle competitions I have attended, along with some notes and projects. It serves as a record of my progress and growth in the field of machine learning.</p>

<p style="text-align: center;"><img alt="coding" width="400" src="https://media.giphy.com/media/iPj5oRtJzQGxwzuCKV/giphy.gif"></p>

<h1 style="color: #1f8dd6; text-align: center;">List of Competitions</h1>

<ol>
    <h2>1. House Price Prediction-Advanced Regression</h2>
    <p>
      <strong>Description:</strong> The House Price Advanced Regression competition aimed to predict the sale prices of residential homes based on various features such as area, number of bedrooms, location, etc. The objective was to develop a regression model that could accurately estimate the sale price of a house given its characteristics.
    </p>
    <p>
      <strong>Dataset:</strong> The competition provided a dataset containing a wide range of features for each house, including numerical, categorical, and ordinal variables. The dataset included both training and testing sets, with the target variable being the sale price. Unfortunately, I do not have a specific link to the dataset as it was hosted on Kaggle's competition page.
    </p>
    <p>
      <strong>Approach:</strong> To tackle the problem, I followed a systematic approach. Here is a summary of the key steps I took:
    </p>
    <ol>
      <li>Data Exploration and Preprocessing: I started by exploring the dataset, examining the distribution of variables, identifying missing values, and understanding the relationships between features. I performed necessary data preprocessing steps, such as handling missing values, encoding categorical variables, and addressing outliers.</li>
      <li>Feature Engineering: I performed feature engineering techniques to enhance the predictive power of the model. This involved creating new features, transforming variables, and considering interactions between variables. I also applied log transformations to skewed numerical features to achieve a more normal distribution.</li>
      <li>Model Selection and Training: I experimented with various regression models, including linear regression, decision trees, random forests, and gradient boosting algorithms. I trained each model using cross-validation techniques to evaluate their performance. Hyperparameter tuning was performed to optimize the selected models.</li>
      <li>Model Evaluation and Fine-tuning: I evaluated the models based on common regression metrics such as mean squared error (MSE), root mean squared error (RMSE), and R-squared. I analyzed the performance of different models and iteratively fine-tuned them to achieve the best results.</li>
    </ol>
    <p>
      <strong>Results:</strong> The performance of the models varied, but the best-performing model achieved an RMSE of 0.1, indicating a relatively accurate prediction of house sale prices. Notable findings from the competition included the importance of feature engineering in improving model performance and the effectiveness of ensemble methods for regression tasks.
    </p>
  </li>
</ol>
<h2>2. Titanic Dataset</h2>

<p>The Titanic Kaggle competition is inspired by the tragic sinking of the RMS Titanic in 1912. The dataset used in the competition contains information about Titanic passengers, including their age, sex, cabin class, fare, and whether they survived or not. The objective of the competition is to create a predictive model that accurately determines the survival outcome of passengers based on these features.</p>

<h3>Dataset</h3>

<p>The dataset provided for the competition is divided into two parts: a training set (<code>train.csv</code>) and a test set (<code>test.csv</code>). The training set consists of labeled data, where each passenger's survival outcome is provided. On the other hand, the test set contains passenger information without the survival labels. Participants are required to train their models on the training set and make predictions on the test set for evaluation.</p>

<h3>Evaluation</h3>

<p>The performance of the predictive models is evaluated using accuracy, which measures the percentage of correctly predicted survival outcomes. Participants are expected to submit their predictions for the test set to the Kaggle platform, where the accuracy of their models will be calculated and ranked on the competition leaderboard.</p>

<h3>Dependencies</h3>

<p>The notebook relies on the following libraries and dependencies:</p>

<ol>
  <li>Python 3.x</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>scikit-learn</li>
  <li>matplotlib</li>
  <li>seaborn</li>
</ol>


Zomato Restaurant Rating Prediction
Project Overview

This project focuses on predicting restaurant ratings using the Zomato Bangalore dataset. The goal is to analyze restaurant features such as cuisines, cost, location, and customer engagement to predict the restaurant rating (/5) using Machine Learning and Deep Learning models.

The project also includes data preprocessing, feature engineering, model training, and performance comparison between ML and DL models.

Dataset
"https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants"

The dataset contains information about restaurants listed on Zomato in Bangalore.

Main features include:

Restaurant name and address

Location and restaurant type

Cuisines served

Online ordering and table booking availability

Number of votes and ratings

Approximate cost for two people

Customer reviews and liked dishes

 Technologies Used
Programming Language

Python

Libraries

pandas

numpy

matplotlib

seaborn

scikit-learn

TensorFlow

Keras

Development Environment

Jupyter Notebook

Project Workflow

Data Collection

Zomato Bangalore restaurant dataset

Data Preprocessing

Handling missing values

Removing duplicates

Cleaning rating values

Encoding categorical variables

Exploratory Data Analysis (EDA)

Restaurant distribution by location

Popular cuisines

Relationship between cost and ratings

Feature Engineering

Encoding cuisine types using MultiLabelBinarizer

Transforming categorical variables

Model Building

Machine Learning Model (Random Forest)

Deep Learning Model (Neural Network)

Model Evaluation

Comparing predictions with actual ratings

Evaluating model accuracy

 Models Used
Machine Learning

Random Forest Regressor

Deep Learning

Artificial Neural Network (ANN)

 Results

Both ML and DL models were trained to predict restaurant ratings.

Random Forest model produced predictions closer to the actual ratings.

Deep Learning model also performed well but slightly less accurate for this structured dataset.

Conclusion:
Tree-based models like Random Forest often perform better for tabular datasets, while deep learning models usually require larger datasets and more complex features.


Future Improvements

Implement restaurant recommendation system

Use NLP for customer review analysis

Deploy the model using Flask or Streamlit

Add interactive dashboards

Author

Swathy E

AI / Machine Learning Enthusiast
Passionate about building AI-driven solutions and data-driven insights.

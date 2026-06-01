Kaggle data set link - https://www.kaggle.com/datasets/boiniabhiram/sonar-data-for-rock-vs-mine-prediction/data

# Rock vs Mine Prediction using Sonar Data

## Project Overview

This is a beginner-friendly Machine Learning project that predicts whether an object is a **Rock** or a **Mine** using sonar signal data.

The project was completed as a revision exercise to strengthen the basic machine learning workflow, including data loading, preprocessing, model training, model evaluation, and prediction.

## Dataset

The dataset contains sonar signal readings. Each row represents sonar signals bounced off an object.

* The first 60 columns are numerical sonar signal values.
* The last column is the target label.

Target labels:

* `R` = Rock
* `M` = Mine

## Objective

The goal of this project is to build a machine learning model that can classify an object as either a rock or a mine based on sonar signal values.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* GitHub

## Machine Learning Workflow

The project follows these steps:

1. Import required libraries
2. Load the sonar dataset
3. Explore and understand the data
4. Separate features and target labels
5. Split the data into training and testing sets
6. Train a machine learning model
7. Evaluate the model using accuracy score
8. Make predictions on new input data

## Model Used

The model used in this project is:

* Logistic Regression

Logistic Regression is a simple and effective classification algorithm, especially useful for binary classification problems like this one.

## Model Evaluation

The model was evaluated using accuracy score on both training and testing data.

Model evaluation helps us understand how well the model performs on data it has already seen and on new unseen data.

## Prediction

After training the model, a new sonar input can be given to the model. The model predicts whether the object is:

* Rock
* Mine

## Project Structure

```text
Rock-Vs-Mine-Prediction-Machine_learning-
│
├── Data/
│   └── Copy of sonar data.csv
│
├── notebook/
│   └── sonar_rock_vs_mine.ipynb
│
└── README.md
```

## How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/ananthumangalan/Rock-Vs-Mine-Prediction-Machine_learning-.git
```

2. Open the project folder.

3. Install the required libraries:

```bash
pip install pandas numpy scikit-learn
```

4. Open the Jupyter Notebook:

```text
notebook/sonar_rock_vs_mine.ipynb
```

5. Run the notebook cells step by step.

## What I Learned

Through this project, I revised:

* How to work with a dataset
* How to separate features and labels
* How to split data for training and testing
* Why stratified splitting is useful
* How to train a classification model
* How to evaluate model performance
* How to make predictions using trained models
* How to upload and maintain a project on GitHub

## Conclusion

This project helped me revise the fundamentals of machine learning using a simple binary classification problem. It is a good starting point before moving into more advanced datasets, algorithms, and model improvement techniques.

## Author

**Ananthu Mangalan**

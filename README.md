# 🌍 Happiness Index Prediction using Machine Learning

## Overview

This project uses machine learning to predict a country's **Happiness Score** based on socioeconomic indicators from the **World Happiness Report 2019** dataset.

The notebook walks through the complete machine learning workflow, including:

* Defining the machine learning problem
* Loading and exploring the dataset
* Selecting features and target variables
* Splitting data into training and testing sets
* Training a regression model
* Evaluating model performance
* Visualizing predictions

This project was completed as part of a machine learning lab assignment focused on the end-to-end ML pipeline.

---

## Dataset

The project uses the **World Happiness Report 2019** dataset, which contains country-level metrics related to quality of life and well-being.

Example features include:

* GDP per Capita
* Social Support
* Healthy Life Expectancy
* Freedom to Make Life Choices
* Generosity
* Perceptions of Corruption

**Target Variable**

* Happiness Score (Life Ladder)

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Machine Learning Workflow

1. Import required libraries
2. Load and inspect the dataset
3. Perform exploratory data analysis (EDA)
4. Define the prediction target
5. Select input features
6. Split the dataset into training and testing sets
7. Train a regression model
8. Generate predictions
9. Evaluate model performance using regression metrics
10. Visualize actual vs. predicted results

---

## Repository Structure

```
happinessindex/
│
├── DefineAndSolveMLProblem - Lab 8.ipynb
├── 2019.csv
└── README.md
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/annikabhatia/happinessindex.git
cd happinessindex
```

### Install dependencies

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
DefineAndSolveMLProblem - Lab 8.ipynb
```

---

## Learning Objectives

Through this project, I practiced:

* Building an end-to-end machine learning pipeline
* Data preprocessing and feature selection
* Training regression models with Scikit-learn
* Evaluating predictive performance
* Applying supervised learning to a real-world dataset

---

## Results

The trained regression model predicts a country's happiness score based on socioeconomic factors. Model performance is evaluated using standard regression metrics, allowing comparison between predicted and actual happiness scores.

---

## Future Improvements

* Compare multiple regression algorithms
* Perform feature engineering
* Tune hyperparameters using GridSearchCV
* Apply cross-validation
* Create interactive visualizations using Plotly

---


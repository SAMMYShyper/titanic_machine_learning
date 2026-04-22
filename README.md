# Titanic: Machine Learning from Disaster

This repository contains a solution for the [Kaggle Titanic challenge](https://www.kaggle.com/c/titanic). The goal of this project is to build a predictive model that answers the question: "What sorts of people were more likely to survive?" using passenger data (ie. name, age, gender, socio-economic class, etc.).

## Project Overview

The project is implemented in a Jupyter Notebook and follows a standard data science workflow:
1.  **Data Exploration:** Initial analysis using `pandas` (head, tail, info, describe) to understand the dataset structure and identify missing values.
2.  **Data Insights:** Categorical and numerical analysis to identify patterns in survival rates (e.g., survival by class, gender, and age).
3.  **Preprocessing:** Handling missing data and preparing features for classification models.
4.  **Modeling:** Building a classification model to predict passenger survival.

## Dataset Description

The dataset consists of two CSV files:
-   `train.csv`: The training set used to build your machine learning models.
-   `test.csv`: The test set used to see how well your model performs on unseen data.

### Features
| Attribute | Definition | Key |
| :--- | :--- | :--- |
| **Survived** | Survival | 0 = No, 1 = Yes |
| **Pclass** | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
| **Sex** | Gender | |
| **Age** | Age in years | |
| **SibSp** | # of siblings / spouses aboard | |
| **Parch** | # of parents / children aboard | |
| **Ticket** | Ticket number | |
| **Fare** | Passenger fare | |
| **Cabin** | Cabin number | |
| **Embarked** | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton |

## Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/SAMMYShyper/titanic_machine_learning.git
    ```
2.  **Install dependencies:**
    Ensure you have Python installed, then install the required libraries:
    ```bash
    pip install pandas jupyter
    ```
3.  **Run the Notebook:**
    ```bash
    jupyter notebook Project_Classification_Titanics.ipynb
    ```

## Repository Structure
- `.ipynb_checkpoints/`: Jupyter Notebook checkpoints.
- `Project_Classification_Titanics.ipynb`: The main notebook containing the analysis and model.
- `train.csv` / `test.csv`: The Kaggle dataset files.
- `LICENSE`: Project license.

## Author
- **SAMMYShyper answering class project CAI4002**
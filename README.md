# Introduction-to-Data-Science
Hier sind ein paar Projekte, bei denen ich Datensätze analysiert habe.
# Titanic Data Analysis and Prediction

## Overview
In this project, we analyzed a dataset of the Titanic and used machine learning models to predict whether an individual would survive the Titanic disaster if it happened today.

## Project Description
During this internship, we focused on the Titanic dataset, performing various data analysis tasks and building machine learning models to make predictions about survival. The goal was to predict whether a person would survive the Titanic catastrophe based on different features such as age, gender, ticket class, etc.

## Dataset
The dataset contains information about passengers on the Titanic, including:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp (Number of siblings/spouses aboard the Titanic)
- Parch (Number of parents/children aboard the Titanic)
- Ticket
- Fare
- Cabin
- Embarked (Port of Embarkation)

## Analysis and Model Building
We performed the following steps in our analysis:
1. **Data Cleaning**: Handling missing values, converting categorical variables into numerical ones, and normalizing the data.
2. **Exploratory Data Analysis (EDA)**: Understanding the relationships between different features and the target variable (Survived).
3. **Feature Engineering**: Creating new features or modifying existing ones to improve the predictive power of the models.
4. **Model Training**: Using various machine learning algorithms to build models that predict survival, including:
   - Logistic Regression
   - Decision Trees
   - Random Forest
   - Support Vector Machines (SVM)
   - Neural Networks
5. **Model Evaluation**: Comparing model performances using metrics such as accuracy, precision, recall, and the F1 score.

## Results
Our models provided insights into which factors were most significant in determining survival chances. For instance, we found that women and children had higher survival rates, while lower-class passengers had a lower chance of survival.

## Conclusion
This project provided a comprehensive understanding of data analysis and machine learning techniques. The models built can predict the survival chances of Titanic passengers with reasonable accuracy, demonstrating the effectiveness of machine learning in historical data analysis.

## Usage
To run the project locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-data-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd titanic-data-analysis
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook to see the analysis and predictions:
   ```bash
   jupyter notebook Titanic_Survival_Prediction.ipynb
   ```

## Acknowledgements
We would like to thank the contributors of the Titanic dataset and the open-source community for their valuable resources and support.

---

Feel free to customize this README file to better match your project structure and additional details.

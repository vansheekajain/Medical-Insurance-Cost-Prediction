# Medical Insurance Cost Prediction using Multiple Linear Regression

## Objective

The objective of this project is to develop a Multiple Linear Regression model to predict medical insurance charges based on a customer's personal and health-related information. The project demonstrates the complete machine learning workflow, including data preprocessing, model training, prediction, and performance evaluation.

---

## Dataset

**Medical Cost Personal Insurance Dataset**

Kaggle Dataset Link:
https://www.kaggle.com/datasets/mirichoi0218/insurance

**Dataset Features:**

- Age
- Sex
- BMI
- Children
- Smoker
- Region
- Charges (Target Variable)

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Methodology

1. Loaded the dataset using Pandas.
2. Displayed the first five records and understood the dataset.
3. Identified numerical and categorical features.
4. Checked for missing values.
5. Encoded categorical variables (Sex, Smoker, Region) using Label Encoding.
6. Split the dataset into 80% training data and 20% testing data.
7. Built a Multiple Linear Regression model using Scikit-learn.
8. Trained the model on the training dataset.
9. Predicted insurance charges for the testing dataset.
10. Evaluated the model using:
    - Mean Absolute Error (MAE)
    - Mean Squared Error (MSE)
    - R² Score
11. Visualized the results using an Actual vs Predicted scatter plot.

---

## Features Used

- Age
- Sex
- BMI
- Children
- Smoker
- Region

### Target Variable

- Charges

---

## Results

The model was evaluated using the following performance metrics:

- Mean Absolute Error (MAE): 4186.508898366432
- Mean Squared Error (MSE): 33635210.431178406
- R² Score: 0.7833463107364539

The Actual vs Predicted scatter plot shows that the model predicts insurance charges reasonably well, although some prediction errors exist for certain customers.

---

## Observations

- Smoking status has a significant impact on medical insurance charges.
- Age and BMI also influence insurance costs.
- The model explains a large portion of the variation in insurance charges using the selected features.

---

## Conclusion

This project successfully developed a Multiple Linear Regression model to predict medical insurance charges using customer information such as age, sex, BMI, number of children, smoking status, and region. The dataset was preprocessed by checking for missing values and encoding categorical variables before splitting it into training and testing datasets. The model achieved satisfactory prediction performance based on MAE, MSE, and R² Score. Among all the features, smoking status had the greatest influence on insurance charges, followed by age and BMI. One limitation of Multiple Linear Regression is that it assumes a linear relationship between the independent variables and the target variable, which may not capture complex real-world patterns.

---

## Repository Structure

```
Medical-Insurance-Cost-Prediction/
│── Assignment-1.ipynb
│── README.md
```

---

## Author

**Name:** Vansheeka Jain

Assignment: Assignment-1

Machine Learning Internship
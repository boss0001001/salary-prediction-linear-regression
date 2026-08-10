**# Salary Prediction using Linear Regression

A beginner-friendly Machine Learning project that predicts salary based on years of experience using Linear Regression.

## 📌 Project Overview

This project demonstrates the basic Machine Learning workflow:

- Loading and exploring a dataset
- Data preprocessing
- Splitting data into training and testing sets
- Training a Linear Regression model
- Making predictions
- Evaluating model performance
- Visualizing the results

## 📊 Dataset

The dataset contains information about:

- **YearsExperience** — Years of professional experience
- **Salary** — Salary corresponding to the experience

The dataset is stored in:

`Salary_dataset.csv`

## 🧠 Machine Learning Model

The project uses:

**Linear Regression**

The model learns the relationship between years of experience and salary and uses that relationship to predict salary for new experience values.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Structure

```text
salary-prediction-linear-regression/
│
|__.gitignore
├── model.ipynb
**├── Salary_dataset.csv
├── README.md
├── requirements.txt
 Results

The Linear Regression model was trained to predict salary based on years of experience.

### Model Parameters

| Parameter | Value |
|---|---:|
| Intercept | 24,848.20 |
| Slope | 9,449.96 |

The slope indicates that the predicted salary increases by approximately **9,449.96** salary units for each additional year of experience.

### Model Evaluation

| Metric | Result |
|---|---:|
| Mean Squared Error (MSE) | 31,270,951.72 |
| Root Mean Squared Error (RMSE) | 5,592.04 |

### Example Prediction

For an employee with **6 years of experience**, the model predicted:

**Predicted Salary: 81,547.98**


# House Price Prediction using Linear Regression

## Project Overview
This project uses Machine Learning to predict house prices based on available housing features. It applies Linear Regression to understand relationships between input variables and house prices and evaluates the model's predictive performance.

## Objectives
- Explore and preprocess the housing dataset.
- Handle categorical variables using One-Hot Encoding.
- Train a Linear Regression model.
- Evaluate performance using R² and Adjusted R² scores.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load and explore the dataset.
2. Perform data preprocessing and feature preparation.
3. Encode categorical variables where required.
4. Split the data into training and testing sets.
5. Train the Linear Regression model.
6. Evaluate model performance using R² and Adjusted R².

## Model Evaluation
The model achieved the following preliminary results:

- **R² Score:** Approximately 0.620
- **Adjusted R² Score:** Approximately 0.571

These scores provide an indication of how well the model explains variation in house prices. Further evaluation using MAE and RMSE can provide additional insight into prediction errors.

## Repository Structure
```text
house-price-prediction-linear-regression/
├── HousePricePrediction.csv
├── LR_ASSIGNMENT.ipynb
└── README.md
```

## How to Run
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `LR_ASSIGNMENT.ipynb` and run the cells.

## Key Learnings
- Data exploration and preprocessing
- Categorical feature encoding
- Training regression models
- Evaluating model performance
- Understanding R² and Adjusted R²

## Conclusion
This project demonstrates the application of Linear Regression to a house price prediction problem and provides practical experience with the end-to-end Machine Learning workflow.

---
**Project Type:** Supervised Machine Learning — Regression

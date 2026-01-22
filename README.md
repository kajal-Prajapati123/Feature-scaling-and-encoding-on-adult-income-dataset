# Feature-scaling-and-encoding-on-adult-income-dataset

Dataset Name: Adult Income Dataset
Source: UCI Machine Learning Repository
Rows: ~48,000
Target Variable: income

## Feature Engineering Strategy
## Numerical Features

age
education-num
hours-per-week
capital-gain
capital-loss

## Categorical Features

workclass
marital-status
occupation
relationship
race
sex
native-country

## Preprocessing Steps

Load dataset using pandas
Separate target variable (income)
Identify numerical and categorical columns
Apply label encoding on education
Apply one-hot encoding on nominal categorical features
Split data into train and test sets
Train Logistic Regression model before scaling
Scale numerical features using StandardScaler
Train Logistic Regression model after scaling
Save the fully processed dataset as CSV

## Model Used

Logistic Regression

### Reason:

Sensitive to feature scale
Ideal for demonstrating impact of scaling

## Impact of Scaling

Prevents dominance of large-range features
Improves gradient descent convergence
Stabilizes model coefficients
Often improves model accuracy

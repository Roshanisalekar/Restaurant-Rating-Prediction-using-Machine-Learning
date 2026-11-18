# Restaurant Rating Prediction using Machine Learning

## About the Project

This project was completed as part of my **Data Science Internship at Cognifyz Technologies**.

The objective of this task was to predict the **Aggregate Rating** of restaurants using Machine Learning based on available restaurant-related features.

## Dataset

The dataset contains restaurant information such as:

- Country Code
- City
- Longitude
- Latitude
- Cuisines
- Average Cost for Two
- Currency
- Table Booking
- Online Delivery
- Price Range
- Votes
- Aggregate Rating

## Project Workflow

### 1. Data Loading
The dataset was loaded using **Pandas**.

### 2. Data Preprocessing
- Checked the dataset structure and missing values.
- Handled missing values in the `Cuisines` column using the mode.
- Removed unnecessary columns.

### 3. Feature and Target Selection

The target variable was:

**Aggregate Rating**

The remaining selected columns were used as input features.

### 4. Categorical Feature Encoding

Categorical features were converted into numerical form using **One-Hot Encoding** with `pd.get_dummies()`.

### 5. Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

### 6. Machine Learning Models

Two regression models were trained:

- Linear Regression
- Decision Tree Regression

### 7. Model Evaluation

The models were evaluated using:

- Mean Squared Error (MSE)
- R² Score

## Model Results

| Model | MSE | R² Score |
|---|---:|---:|
| Linear Regression | 1.4117 | 0.3798 |
| Decision Tree Regression | 0.1089 | 0.9521 |

Based on the test results, **Decision Tree Regression performed better** than Linear Regression, with a lower MSE and higher R² Score.

## Feature Importance

Feature importance from the Decision Tree showed that **Votes** was the most influential feature in the model, followed by features such as Longitude, Latitude, and Average Cost for Two.

## Conclusion

The project provided practical experience in:

- Data preprocessing
- Missing value handling
- Categorical feature encoding
- Train-test splitting
- Regression algorithms
- Model evaluation
- Model comparison
- Feature importance analysis

The Decision Tree Regression model achieved an **R² Score of approximately 0.952** and an **MSE of approximately 0.109** on the test data.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Machine Learning

## Internship

**Data Science Internship – Cognifyz Technologies**
<img width="1920" height="1080" alt="result" src="https://github.com/user-attachments/assets/87a5ae22-b4d1-4ac4-93f3-faf6437f56bf" />

# 🏠 Housing Price Prediction using Linear Regression

This project implements a **Linear Regression model** to predict housing prices based on various features such as area, number of bedrooms, presence of amenities, and more. The dataset used is `Housing.csv`.

---

## 📂 Dataset

The dataset consists of housing details with 545 entries and the following features:

- **Numerical Features**:
  - `area`, `bedrooms`, `bathrooms`, `stories`, `parking`, `price`
- **Categorical Features**:
  - `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`

Target Variable: `price`

---

## ⚙️ Workflow

### 1. Import Libraries
Essential Python libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, and `sklearn` are imported.

### 2. Load and Explore Data
- Load the `Housing.csv` file.
- Inspect data types, missing values, and basic statistics.

### 3. Preprocessing
- **One-Hot Encoding** for categorical variables.
- **Feature-target separation** (`X` and `y`).
- No missing values or scaling required for basic linear regression.

### 4. Train-Test Split
- Split the data into training and testing sets (80% train / 20% test).

### 5. Model Training
- Fit a **Linear Regression** model using `sklearn.linear_model.LinearRegression`.

### 6. Model Evaluation
Metrics used:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

### 7. Visualization
- Scatter plot of **Actual vs Predicted Prices**.
- Regression diagnostics via residual plots (optional).
- Coefficients interpretation to assess feature importance.

---

## 📁 Files Included

- `Housing.csv`: The input dataset
- `Task3.ipynb`: Jupyter notebook with complete workflow
- `README.md`: This project documentation


# ML Project 5: Linear Regression

## 📊 Project Overview
This project implements Linear Regression to predict California housing prices using the median income as a predictor variable. The project demonstrates fundamental machine learning concepts including data loading, preprocessing, model training, evaluation, and visualization.

## 🎯 Objective
Predict median house values in California using median income data through Linear Regression modeling, showcasing the relationship between income levels and housing prices.

## 📁 Dataset
- **Source**: California Housing Dataset (from scikit-learn)
- **Target Variable**: MedHouseVal (Median House Value)
- **Feature Variable**: MedInc (Median Income)
- **Type**: Regression problem

## 🛠️ Technologies Used
- **Python 3.x**
- **NumPy**: Numerical operations and array handling
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization and plotting
- **Scikit-learn**: Machine learning library for:
  - Dataset loading
  - Data splitting
  - Linear Regression model
  - Performance metrics

## 📋 Project Structure
```
ML-project-5-LinearRegression/
│
├── Task1_LinearRegression.ipynb    # Main Jupyter notebook with implementation
└── README.md                       # Project documentation
```

## 🚀 Implementation Steps

### 1. Data Loading and Exploration
- Load the California housing dataset
- Display first 5 rows to understand data structure
- Check for missing values
- Generate basic statistical summary

### 2. Data Preparation
- Select median income (MedInc) as the feature variable
- Select median house value (MedHouseVal) as the target variable
- Split data into training (80%) and testing (20%) sets

### 3. Model Training
- Initialize Linear Regression model
- Train the model using training data
- Fit the linear relationship between income and house value

### 4. Model Evaluation
- Make predictions on test data
- Calculate performance metrics:
  - **Mean Squared Error (MSE)**: Measures average squared differences
  - **R² Score**: Coefficient of determination (model accuracy)

### 5. Visualization
- Create scatter plot of actual vs predicted values
- Display regression line showing the linear relationship
- Add labels, title, and legend for clarity

## 📈 Results
The model establishes a linear relationship between median income and median house value, providing insights into how income levels correlate with housing prices in California.

## 🔧 How to Run

### Prerequisites
```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

### Execution
1. Clone this repository:
```bash
git clone https://github.com/Mostafa-Faisal/ML-project-5-LinearRegression.git
```

2. Navigate to the project directory:
```bash
cd ML-project-5-LinearRegression
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook Task1_LinearRegression.ipynb
```

4. Run all cells in sequence to execute the complete analysis

## 📊 Key Insights
- Linear Regression provides a simple yet effective approach for understanding relationships between variables
- The model demonstrates how median income can be used as a predictor for housing values
- Visualization helps in understanding the linear relationship and model performance

## 🎓 Learning Outcomes
- Understanding of Linear Regression fundamentals
- Data preprocessing and exploration techniques
- Model evaluation using MSE and R² metrics
- Data visualization with Matplotlib
- Hands-on experience with scikit-learn library

## 👨‍💻 Author
**Mostafa Faisal**

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

---
*This project is part of a Machine Learning internship series focusing on fundamental ML algorithms and their practical applications.*

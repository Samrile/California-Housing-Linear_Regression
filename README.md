# **California Housing Price Prediction Using Linear Regression**

This project implements a **Linear Regression Model** to predict housing prices based on various features such as median income, house age, and population density, using the **California Housing Dataset**. The project demonstrates data preprocessing, feature selection, model training, and performance evaluation, making it a perfect beginner-friendly project for data science enthusiasts.

---

## **Table of Contents**

1. [Overview](#overview)  
2. [Dataset Description](#dataset-description)  
3. [Installation](#installation)  
4. [Project Workflow](#project-workflow)  
5. [Results](#results)  
6. [Future Enhancements](#future-enhancements)  
7. [Contributing](#contributing)  
8. [License](#license)  

---

## **Overview**

Housing price prediction is a classic problem in data science. This project uses the California Housing dataset to:
- Explore the dataset through visualizations and statistical summaries.
- Perform feature selection based on correlation.
- Build a Linear Regression model to predict housing prices as well as used Ridge and Lasso.
- Evaluate the model's performance using metrics like R², Mean Squared Error, and Mean Absolute Error.

This project serves as an introduction to **Machine Learning** concepts, focusing on regression analysis and model evaluation.

---

## **Dataset Description**

The **California Housing Dataset** contains information collected in the 1990 U.S. Census. The target variable is the median value of houses (`PRICE`), which is predicted based on features such as:
- `MedInc`: Median income in the area.
- `HouseAge`: Median age of the houses in the area.
- `AveRooms`: Average number of rooms per house.
- `AveOccup`: Average number of people per household.
- And more...

### Dataset Source:
The dataset is loaded from `scikit-learn` using `fetch_california_housing`.

---


## **Project Workflow**

The project follows these steps:

### **Data Loading**
- The California Housing dataset is loaded into a Pandas DataFrame.

### **Exploratory Data Analysis (EDA)**
- Visualizations are created to understand the distribution of house prices and relationships between features.

### **Feature Selection**
- Correlation analysis is performed to select the most relevant features for prediction.

### **Data Splitting**
- The dataset is split into training (80%) and testing (20%) sets.

### **Model Training**
- A Linear Regression model is trained on the selected features.

### **Model Evaluation**
- Metrics such as R², Mean Squared Error (MSE), and Mean Absolute Error (MAE) are computed.
- Residual analysis and scatter plots of actual vs predicted prices are generated.

### **Feature Importance**
- Coefficients of the regression model are analyzed to determine the impact of each feature.

---

## **Results**

### **Performance Metrics**
- **R² Score**: Measures how well the model explains variability in house prices.
- **MSE**: Average squared difference between actual and predicted prices.
- **MAE**: Average absolute difference between actual and predicted prices.

### **Visual Insights**
- Scatter plot showing the relationship between actual and predicted prices.
- Residual analysis to evaluate the distribution of errors.

---

## **Future Enhancements**
1. Add support for advanced regression techniques (e.g., Ridge, Lasso).
2. Include cross-validation for robust model evaluation.
3. Explore hyperparameter tuning to optimize the model.
4. Deploy the model as a web application using Flask or Streamlit.

---

## **Contributing**

Contributions are welcome! If you'd like to improve this project:
1. Fork the repository.
2. Create a new branch for your changes.
3. Submit a pull request with a clear description of the modifications.

---

## **License**

This project is licensed under the **MIT License**. Feel free to use and modify the code for personal and professional purposes.

---

## **Acknowledgments**
- **Dataset**: Provided by scikit-learn.
- **Libraries**: [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/), [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/), and [Scikit-learn](https://scikit-learn.org/).

## **Installation**

Follow these steps to set up the project locally:

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/linear-regression-housing.git
cd linear-regression-housing


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
- Build a Linear Regression model to predict housing prices.
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

## **Installation**

Follow these steps to set up the project locally:

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/linear-regression-housing.git
cd linear-regression-housing

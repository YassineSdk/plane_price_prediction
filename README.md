# **Model Evaluation**

In the machine learning part of the project, we used two models: **Random Forest** and **XGBoost Regressor**. Here's why these models were chosen:

## **1. Random Forest**
- Random Forest is an ensemble learning method that constructs multiple decision trees during the training process and outputs either the mode (classification) or the average (regression) of the individual trees.
- It is robust against overfitting and performs well on a variety of datasets, making it a reliable choice for our regression task.

## **2. XGBoost (Extreme Gradient Boosting)**
- XGBoost is another ensemble technique that focuses on boosting. It builds decision trees sequentially, with each tree correcting the errors of the previous one.
- It is particularly effective for improving accuracy and handling complex datasets.

---

## **Performance Metrics**

### **Density Plot**
We plotted the density distribution of predicted values versus actual values to visualize how well the models predicted house prices. The plots showed a good alignment between predicted and actual values, indicating that our models performed well.

### **Mean Absolute Error (MAE)**
The average error between predicted and actual prices was **$145,061**, meaning that, on average, our model's predictions deviated from the true prices by this amount.

### **R² Score**
Both models achieved an **R² score of 0.95**, which indicates that they explained 95% of the variance in the dataset. This high score demonstrates that the models are highly effective at capturing the underlying patterns in the data.

---

## **Conclusion**
Both Random Forest and XGBoost proved to be robust and accurate for predicting house prices, with minimal error and strong explanatory power. These results highlight their suitability for regression tasks in this domain.


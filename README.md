# DSS5104_GroupProject

# Deep Learning for Tabular Data

This repository explores the application of modern deep learning models to tabular datasets and compares their performance with traditional machine learning baselines such as Random Forest and XGBoost. Five real-world case studies are included across both classification and regression tasks.

## Project Structure

Each subfolder corresponds to a specific dataset and contains relevant code, visualizations, and evaluation outputs:

- **Airline Passenger Satisfaction**  
  Classification task predicting customer satisfaction based on demographics, flight details, and service ratings.

- **House Loan Analysis**  
  Classification task to predict loan default likelihood using customer financial and demographic data.

- **Optiver Realized Volatility Prediction**  
  Regression task focused on forecasting financial market volatility based on high-frequency trading data.

- **Predictive Maintenance**  
  Classification task identifying machine failures using industrial sensor and operational data.

- **UK Used Car Price**  
  Regression task for predicting the sale price of Audi vehicles in the UK from car features.

## Models Compared

The following models were evaluated on each dataset:

- **Random Forest**
- **XGBoost (Extreme Gradient Boosting)**
- **TabNet**
- **NODE (Neural Oblivious Decision Ensemble)**
- **FT-Transformer**

## Evaluation Metrics

Performance was assessed using appropriate metrics for each task:

- **Classification**: Accuracy, Precision, Recall, F1-score, Training Time
- **Regression**: RMSPE, MAE, RMSE, R², Training Time

## Visual Summary

Each dataset includes radar charts and performance tables to visualize and compare model performance across multiple metrics.

## Conclusion

This project demonstrates that while deep learning models such as FT-Transformer and TabNet show potential in complex or high-dimensional tabular settings, classical models like XGBoost often remain highly competitive, especially in terms of training efficiency and generalization on structured data.

---

Feel free to contribute or open an issue if you'd like to explore additional datasets or model variants!

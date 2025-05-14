# Car Price Prediction Model

**Car Price Prediction Model** is the first project from `machine-learning-practices`. It is also my first project written entirely in English, aiming to **improve my analytical and documentation skills in English language**. This project also aims to **improve my understanding about machine learning regression models**, and how to **compare each models performance using evaluation metrics**.

## ☁ Cloud Storage

To keep this repository optimal, the dataset, trained models, and scalers are shared on **MEGA**:  
[Access on MEGA](https://mega.nz/folder/Y5gVmJBS#oI8kpLvRF0y3MpEe8YnmQg/folder/RlJSXRZK)

## 📁 Dataset Origin

The dataset was originally sourced from Kaggle. Unfortunately, the exact link is **currently unavailable**.

## 📝 Model Result

| Model Name | MAE | MAE % | MSE | RMSE | R2 % |
| --- | ---: | ---: | ---: | ---: | ---: |
| Linear Regression |  19.385 |  0.219 |  4,168.446 |  64.564 |  99.955 |
| Decision Tree |  418.167 |  4.723 |  294,343.377 |  542.534 |  96.796 |
| Random Forest |  213.082 |  2.407 |  76,310.606 |  276.244 |  99.169 |
| Support Vector Machine |  124.658 |  1.408 |  23,453.053 |  153.144 |  99.745 |
| Gradient Boost |  169.548 |  1.915 |  46,943.369 |  216.664 |  99.489 |
| XGBoost |  168.758 |  1.906 |  47,246.280 |  217.362 |  99.486 |

🏆 **The Best**: Linear Regression

For more information about model performance summary, please check the [notebook](./notebook.ipynb) in **E. Conclusion** section.
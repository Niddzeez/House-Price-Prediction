# 🏠 House Price Prediction using Linear Regression

This project uses machine learning techniques to predict the sale prices of houses based on various features like location, size, quality, and more. The dataset used is inspired by the popular Kaggle competition: **House Prices - Advanced Regression Techniques**.

---

## 📂 Project Structure

- `House-Price-Prediction.ipynb` — Main Jupyter notebook containing data preprocessing, model training, evaluation, and results.
- `train.csv` / `test.csv` — Dataset files (if added).
- `README.md` — You're reading it!

---

## 🔍 Problem Statement

Predict the final price of homes based on a variety of explanatory variables describing every aspect of residential homes in Ames, Iowa.

---

## 🧹 Data Preprocessing

Key preprocessing steps included:

- Handling missing values via median/mode imputation
- Dropping irrelevant or sparse columns
- Encoding categorical variables (ordinal and nominal)
- Feature scaling (if applicable)
- Train-test split for validation

---

## 🤖 Model Used

- **Linear Regression**
  - Simple and interpretable
  - Trained on cleaned and encoded features
  - Evaluated using:
    - RMSE (Root Mean Squared Error)
    - R² Score
    - MAPE (Mean Absolute Percentage Error)
    - Percentage of predictions within ±10% of actual values

---

## 📈 Evaluation Metrics

| Metric                        | Description                                            |
|------------------------------|--------------------------------------------------------|
| RMSE                         | Average magnitude of error                             |
| R² Score                     | How well the model explains variance in target         |
| MAPE                         | Average percent error in predictions                   |
| % Predictions within ±10%    | Robustness of model for practical use                  |

---

## 🚀 Future Work

- Try advanced models: Ridge, Lasso, XGBoost, Random Forest
- Feature engineering to improve performance
- Hyperparameter tuning for optimization
- Cross-validation and ensembling

---

## 🙌 Acknowledgements

- Dataset from [Kaggle House Prices Challenge](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- Inspired by real-world real estate valuation tasks

---

## 🧠 Author

- **Nidhi Lodha**  
  *CSE, VNIT Nagpur*

---

## 📜 License

This project is open-source and free to use under the MIT License.

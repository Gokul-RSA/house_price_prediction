# house_price_prediction
i created a house price prediction(ml model) using python libraries and functions .Here i get the dataset from kaggle website . In this model , it predicts  house price based on no of bedroom ,square feet of the house and no of bathroom .It is a linear  regression model which predicts the best fit line. It scored 0.27% in kaggle submission.

# 🏡 House Price Prediction - Kaggle Competition

This is my first machine learning project where I built a model to predict housing prices using data from the [Kaggle House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/) competition.

---

## 📌 Overview

The goal of this project is to predict the final price of homes based on various features like square footage, number of bathrooms, bedrooms, etc., using a **Linear Regression** model.

---

## 🚀 Project Steps

1. **Loaded and explored the dataset (`train.csv`)**
2. **Selected key features**:  
   - `GrLivArea`, `BedroomAbvGr`, `FullBath`
3. **Trained a Linear Regression model**
4. **Evaluated performance using**:
   - R² Score: ~0.63  
   - RMSE: ~₹52,973
5. **Generated predictions for the test set (`test.csv`)**
6. **Submitted predictions to Kaggle**
   - **Kaggle Score**: `0.27724` (RMSLE)

---

## 📂 Files in This Repository

| File Name              | Description                               |
|------------------------|-------------------------------------------|
| `train.csv`            | Training dataset with house prices        |
| `test.csv`             | Test dataset for predictions              |
| `sample_submission.csv`| Kaggle submission format                  |
| `my_submission.csv`    | My predicted prices (final submission)    |
| `HousePricePredictor.ipynb` | Jupyter/Colab notebook with all code  |
| `README.md`            | Project documentation (this file)         |

---

## 🛠️ Tools & Libraries Used

- Python 🐍
- Pandas
- NumPy
- scikit-learn
- Google Colab
- Matplotlib / Seaborn (optional for visualizations)

---

## 📈 Model Details

- Algorithm: **Linear Regression**
- Features used:
  - `GrLivArea`: Ground Living Area (sqft)
  - `BedroomAbvGr`: Number of bedrooms
  - `FullBath`: Number of full bathrooms
- No categorical encoding or feature engineering (yet)

---

## 📉 Future Improvements

- Add more meaningful features (e.g. `TotalBsmtSF`, `GarageCars`)
- Handle missing values with better strategies
- Try advanced models (Random Forest, XGBoost)
- Use log transformation for `SalePrice`
- Use cross-validation for better accuracy estimates

---

## 🙋‍♂️ Author

**Gokul S**  
Beginner in ML & Python — learning through real-world datasets and Kaggle challenges!

---

## 📜 License

This project is for learning purposes. Feel free to fork and use for educational or practice purposes.


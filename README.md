This project aims to predict individual **medical insurance charges** using personal information like age, BMI, number of children, smoking status, and region. It's a classic regression problem using the **Medical Cost Personal Datasets** available on [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance).

---

### 🔢 Dataset Description

The dataset consists of **1,338 entries** and **7 features**:

| Column Name | Description                                                                     |
| ----------- | ------------------------------------------------------------------------------- |
| `age`       | Age of the primary beneficiary                                                  |
| `sex`       | Gender of the beneficiary (`male`, `female`)                                    |
| `bmi`       | Body Mass Index (BMI), a measure of body fat                                    |
| `children`  | Number of dependents covered by insurance                                       |
| `smoker`    | Whether the person smokes (`yes`, `no`)                                         |
| `region`    | Residential area in the US (`northeast`, `northwest`, `southeast`, `southwest`) |
| `charges`   | Medical insurance cost (target variable)                                        |

---

### 🛠️ Tools & Technologies

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn (Linear Regression, train/test split, metrics)

---

### 🧠 Problem Statement

> Predict the **insurance charges (`charges`)** based on personal attributes using **Linear Regression** and evaluate the model using **R² score** and **RMSE**.

---

### 📊 Key Steps

* Data loading & exploration
* Data preprocessing:

  * Handling categorical variables using `pd.get_dummies()`
  * BMI categorization (optional)
* Train-test split
* Model training (`LinearRegression`)
* Performance evaluation (`r2_score`, `mean_squared_error`)
* Visualization of actual vs predicted charges

---

### 📈 Sample Output

```python
R² Score: 0.80
RMSE: 6000.23
```

---

### ✅ Possible Extensions

* Try **Ridge** or **Lasso Regression**
* Apply **Polynomial Regression**
* Use **Feature Scaling** for better model performance
* Compare with **Random Forest Regressor**

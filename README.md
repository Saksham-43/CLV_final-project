# Customer Lifetime Value Prediction & Segmentation

**📌 Overview:**
This project focuses on predicting Customer Lifetime Value (CLV) using multiple regression models and segmenting customers based on purchasing behavior. It aims to help businesses understand their customers better and take data-driven decisions for retention and growth.

**📌 Project Objectives:**
* Predict Customer Lifetime Value (CLV) using various regression algorithms.<br>
* Compare the performance of different models.<br>
* Segment customers into meaningful categories to enable targeted marketing strategies.<br>

**🧠 Machine Learning Models Used:** <br>

The following regression models were trained and evaluated for CLV prediction:
* Linear Regression
* Ridge Regression
* Random Forest Regressor
* XGBoost Regressor

**📌Each model was compared based on performance metrics such as:**

* 📉 Mean Squared Error (MSE)<br>
* 📈 R² Score

**👥 Customer Segmentation:** <br>
Customers were segmented using RFM analysis and clustering techniques into the following categories:
| Segment            | Description                                                             |
| ------------------ | ----------------------------------------------------------------------- |
| 🟢 Champions       | High-value, frequent, and recent buyers. Best customers.                |
| 🔁 Loyal Customers | Regular and consistent buyers. Good for upselling and loyalty programs. |
| 🟡 Regulars        | Average activity. Can be nurtured with offers or reminders.             |
| 🔴 Churned         | Long inactive or low-value customers. May need win-back strategies.     |

**⚙️ Technologies Used:**

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

**📊 Results Summary:**

### 📈 Model Performance Comparison(2009-2010):

| Model                   | Mean Squared Error (MSE) | R² Score |
|-------------------------|--------------------------|----------|
| Linear Regression       | 0.914556                 | 0.455169 |
| Ridge Regression        | 0.914559                 | 0.455167 |
| Random Forest Regressor | 0.610156                 | 0.636510 |
| XGBoost Regressor       | 0.481818                 | 0.712965 |


### 📊 Model Performance Comparison (2010–2011):

| Model                   | Mean Squared Error (MSE) | R² Score |
|-------------------------|--------------------------|----------|
| Linear Regression       | 0.861313                 | 0.462751 |
| Ridge Regression        | 0.861321                 | 0.462746 |
| Random Forest Regressor | 0.635012                 | 0.603908 |
| XGBoost Regressor       | 0.508037                 | 0.683109 |


* **XGBoost Regressor**  performed the best among all models with the lowest MSE and highest R².

* Customer segmentation revealed valuable insights for personalized marketing and retention strategies.









## Sarah Scolnik - Capstone: Airbnb

## Executive Summary:  
**Problem:**  
Build a model to predict prices for Airbnb listings based on various features and identify the most influential features, with the goal of identifying strategies for Airbnb hosts to maximize profit.

**Data, methods & models:**  
- Data: Used data scraped from Airbnb by Inside Airbnb (http://insideairbnb.com/get-the-data.html). 
- Model: Linear regression with regularization (Lasso). 
- Feature Engineering: Data was cleaned, a subset of relevant features was selected, and interaction features were created.
- Python packages used: NumPy, Pandas, Matplotlib.pyplot, Seaborn
- Scikit-learn modules used: 
    - from sklearn.model_selection: train_test_split
    - from sklearn.preprocessing: StandardScaler, PolynomialFeatures
    - from sklearn.linear_model: LinearRegression, RidgeCV, LassoCV
    - from sklearn.dummy: DummyRegressor
    - from sklearn.metrics: mean_squared_error, mean_absolute_error

**Metrics:**
- R^2 (coefficient of determination), RMSE (root mean squared error), MAE (mean absolute error)
- Goal: better than baseline (predicting mean price for all)
- Stretch Goal: model that is useful for estimating a price for an Airbnb listing (+/- 10% error)

**Findings:**

**Assumptions & Limitations:**
- Inside Airbnb data is accurate. 
- Listings are active
- LINEI assumptions for linear regression  

### Data source

http://insideairbnb.com/get-the-data.html  
Inside Airbnb scraped data for Washington DC on these dates:
- 11/15/18
- 10/12/18
- 9/14/18
- 8/18/18
- 7/20/18
- 5/18/18
- 4/15/18
- 5/10/17
- 3/10/17
- 10/3/15

Calendar/price data starts on date scraped

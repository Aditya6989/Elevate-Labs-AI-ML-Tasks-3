🏡 Housing Price Prediction using Linear Regression
This project uses linear regression to predict house prices based on various features such as area, number of bedrooms, availability of amenities, and furnishing status.

📌 Features of the Project
Load and preprocess a real-world housing dataset

Encode categorical variables using one-hot encoding

Train-test split for model evaluation

Fit a Linear Regression model using scikit-learn

Evaluate using MAE, MSE, and R²

Visualize feature importance via regression coefficients

📊 Dataset
The dataset contains features like:

area, bedrooms, bathrooms, stories, parking (numerical)

mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus (categorical)

price (target)

🧪 Evaluation Metrics
MAE (Mean Absolute Error): Average absolute difference between predicted and actual prices.

MSE (Mean Squared Error): Similar to MAE but penalizes larger errors more.

R² Score: Proportion of variance in target explained by the model (closer to 1 is better).

📈 Regression Coefficients
The model's coefficients show how each feature influences price:

Positive values: Increase the price

Negative values: Decrease the price

⚠️ Assumptions of Linear Regression
Linearity

Independence of errors

Homoscedasticity (equal error variance)

Normal distribution of residuals

No multicollinearity between predictors

🚫 Limitations
Model performance depends on assumptions holding true

Cannot capture nonlinear relationships

Sensitive to outliers and multicollinearity


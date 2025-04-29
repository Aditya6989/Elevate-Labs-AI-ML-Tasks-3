1. What assumptions does linear regression make?
Linear regression has a few rules it expects the data to follow:
The relationship between the inputs and the output should be roughly straight-line (linear).
The data points should be independent—what happens with one row shouldn’t influence another.
The spread of the errors (the differences between actual and predicted values) should be consistent across all values.
Those errors should also follow a normal distribution.
Finally, your input variables shouldn’t be too similar to each other (that’s called multicollinearity).

2. How do you interpret the coefficients?
Each coefficient tells you how much the target (like house price) is expected to change when you increase that variable by one unit, assuming everything else stays the same.
So, if the coefficient for "area" is 120, it means that for every additional square foot, the house price increases by ₹120—assuming other features stay constant.

3. What is the R² score and why is it important?
R² tells you how well your model explains the variation in the data. If R² is 0.65, that means your model explains 65% of why the prices are what they are.
Higher is generally better, but it's not everything—you can have a high R² and still have a bad model if you're overfitting.

4. When would you use MSE instead of MAE?
Both measure how far off your predictions are:
MAE just averages the absolute errors.
MSE squares the errors before averaging, so it punishes big mistakes more.
Use MSE if you really want to avoid large errors. Use MAE if you care more about general accuracy and want something easier to interpret.

5. How do you detect multicollinearity?
Multicollinearity means your features are stepping on each other’s toes—they’re too similar. You can:
Look at a correlation matrix: if two columns are highly correlated, that’s a red flag.
Use something called VIF (Variance Inflation Factor). If a variable has a VIF over 5 or 10, it’s probably causing issues.

6. What’s the difference between simple and multiple regression?
Simple regression uses just one feature to predict the outcome.
Multiple regression uses two or more features.
Both try to draw a line (or plane, or hyperplane) that best fits the data—they just differ in how many dimensions they work with.

7. Can you use linear regression for classification?
Not really. Linear regression is for predicting numbers, not categories.
If you want to classify (like spam vs. not spam), you'd use logistic regression or a proper classification model.

8. What happens if you break the rules (assumptions) of linear regression?
Your results might be unreliable:
The model might be wrong or misleading.
Your predictions could be way off.
You could get invalid statistical results (like wrong p-values or confidence intervals).

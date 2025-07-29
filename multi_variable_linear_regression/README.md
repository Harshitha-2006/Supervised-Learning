MULTIPLE LINEAR REGRESSION-HOUSE PRICE PREDICTION
📁 Dataset
The dataset (multiplelr.csv) contains four columns:
area - Size of the house in square feet (independent variable)
bedrooms - Number of bedrooms (independent variable)
age - Age of the house in years (independent variable)
price - Price of the house (dependent variable)

📐 Model Equation
The learned Multiple Linear Regression model is of the form:
price=m1*area+m2*bedrooms+m3*age+c
Where:
price — dependent variable
area, bedrooms, age — independent variables
m1, m2, m3 — coefficients (slopes) for each feature
c — intercept

📊 Learned Values from the Model
After training the model, the coefficients and intercept are:
Feature	Coefficient (m)
Area	137.25
Bedrooms	-26025
Age	-6825
Intercept (c): 383,725 (approx.)

🔢 Example Predictions
Predicting the price of a house with:
Area = 2600 sqft
Bedrooms = 3
Age = 20 years
price = 137.25 * 2600 - 26025 * 3 - 6825 * 20 + 383724.9999 ≈ $526,000

📈 Visualization
A 3D scatter plot visualizes the dataset:
X-axis: Area (sqft)
Y-axis: Number of bedrooms
Z-axis: Price (USD)
Green dots: Actual data points

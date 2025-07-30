LOGISTIC REGRESSION - STUDY PASS PREDICTION
📁 Dataset
The dataset (study_data.csv) contains two columns:
hrs - Number of hours studied (independent variable)
pass - Whether the student passed (dependent variable, binary: 0 or 1) : 0 - Fail,1 - Pass

📐 Model Description
The logistic regression model predicts the probability of passing based on the hours studied.
The learned logistic regression model can be expressed as:
P(pass=1)= 1/(1+e ^(−(m × hrs + c)))
  
Where:
hrs — independent variable (hours studied)
m — coefficient (slope) learned from the data
c — intercept (bias)

🔢 Example Predictions
Predicting if a student passes after studying for 9 hours:
lr.predict([[9]]) → Output: 1 (Pass)

Model also predicts probabilities and outputs for training and test data.

📈 Visualization
Scatter plot shows actual data points (hrs vs. pass) in red dots.
Line plot represents predicted probabilities of passing based on hours studied.
X-axis: Hours Studied
Y-axis: Probability of Passing

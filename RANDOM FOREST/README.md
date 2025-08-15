🌳PLAY TENNIS PREDICTION-RANDOM FOREST
📁Dataset
The dataset (play.csv) contains weather and temperature conditions, along with whether tennis was played:
Weather – Categorical feature (Sunny, Overcast, Rainy)
Temperature – Categorical feature (Hot, Mild, Cool)
Play – Target variable (Yes = 1, No = 0)

📐 Model Description
The Random Forest Classifier is used to predict whether tennis will be played based on the Weather and Temperature conditions.
Data preprocessing is done using Label Encoding to convert categorical values into numeric codes.
Model is trained with 10 decision trees (n_estimators=10).

🔢 Example Prediction
Predicting if tennis will be played when:
Weather = Overcast (encoded as 0)
Temperature = Cool (encoded as 0)
rf.predict([[0, 0]]) 
Output: 1 → Yes (Tennis will be played)

📈 Feature Importance Visualization:
The Random Forest model calculates feature importance, showing which features contribute most to the decision-making process.
Weather: Importance score from trees
Temperature: Importance score from trees
A bar chart is plotted:
X-axis: Features (Weather,Temperature)
Y-axis: Importance score

📊 Confusion Matrix Visualization:
The confusion matrix is displayed as a color-coded heatmap, where:
Darker diagonal cells indicate correct predictions for that class.
Brighter or highlighted off-diagonal cells show where the model made misclassifications.
This visualization quickly reveals which classes are most accurately predicted and which ones the model tends to confuse with others.

Since the training and testing data are the same here, accuracy is 100%.

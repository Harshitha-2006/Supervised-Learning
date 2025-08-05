🌸IRIS FLOWER CLASSIFICATION (Support vector machine-SVM)

📁 Dataset
The dataset is the built-in Iris dataset from scikit-learn and contains the following columns:
sepal length (cm)	Length of sepal in centimeters
sepal width (cm)	Width of sepal in centimeters
petal length (cm)	Length of petal in centimeters
petal width (cm)	Width of petal in centimeters
target	Flower species as numeric values:
0 - Setosa
1 - Versicolor
2 - Virginica
flower_name	Mapped class name from target

📐 Model Description
A Support Vector Classifier (SVC) is trained using the features:
Sepal Length
Sepal Width
Petal Length
Petal Width
The model learns to classify iris flowers into one of the three species using optimal hyperplanes.

🔢 Example Predictions
s = [[4.5,2.3,1.3,0.3]]        
svm.predict(s)                   
The model also:
Prints predicted vs actual flower name for test samples
Tells whether the prediction is correct or not
Example output:
Sample features: [[4.5,2.3,1.3,0.3]]
Predicted Label: 0 → setosa
Actual Label: 0 → setosa
Prediction is correct.

📈 Visualization
Two scatter plots are generated:
Sepal Length vs Sepal Width
Petal Length vs Petal Width
These help visualize how different classes (Setosa, Versicolor, Virginica) are distributed. Colors distinguish between different species.
Axes:
X-axis: Feature (e.g. sepal length or petal length)
Y-axis: Feature (e.g. sepal width or petal width)


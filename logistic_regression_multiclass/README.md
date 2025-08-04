DIGIT CLASSIFICATION USING LOGISTIC REGRESSION(MULTI-CLASS CLASSIFICATION)

📁 DATA SETS
This project uses the Digits Dataset from
-scikit-learn, which contains 8×8 grayscale images of handwritten digits ranging from 0 to 9. 
-Each image is converted into a 1D array of 64 features representing pixel intensities. 
-The corresponding target values are the digit labels (0–9).


📐 MODEL DESCRIPTION
The classification is performed using a Logistic Regression model.
- The dataset is split into training and test sets to evaluate performance.
- The logistic regression model is trained to map the 64 input features (pixels) to one of 10 digit classes.
- A high iteration limit is set to ensure proper convergence of the model.
- Once trained, the model can predict the digit represented in any input image and is evaluated based on its accuracy and error patterns.

CONFUSION MATRIX
A confusion matrix is used to evaluate the model's performance.
- It shows the actual digit labels vs. the predicted labels.
- Correct predictions appear along the diagonal.
- Off-diagonal values represent misclassifications — where the model predicted the wrong digit.
- This matrix helps in identifying which digits are most often confused with others, providing insights into the model’s weaknesses.

📈VISUALIZATION
Confusion Matrix Heatmap:  
   The confusion matrix is visualized as a heatmap using color gradients. This makes it easy to identify correct and incorrect predictions visually.  
   - Darker or brighter diagonal cells indicate strong correct classification.
   - Highlighted off-diagonal cells indicate which digits the model struggles to distinguish.

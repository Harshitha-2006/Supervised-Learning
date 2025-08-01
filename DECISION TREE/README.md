DECISION TREE - EMAIL SPAM DETECTION
📁 Dataset
The dataset (email_spam.csv) contains 4 columns:
Contains_Free – 1 if the email contains the word "Free", otherwise 0
Contains_Win – 1 if the email contains the word "Win", otherwise 0
Email_Length_gt_100 – 1 if email length is greater than 100 characters, otherwise 0
Spam – Target label:
"Spam" – Spam
"Not Spam" – Not spam

🧠 Model Description
A Decision Tree Classifier is trained to classify emails as spam or not spam using the above features.
Input Features: Contains_Free, Contains_Win, Email_Length_gt_100
Output Label: Spam or Not Spam (converted to 1 or 0 using LabelEncoder)
The model learns simple rules (splits) to decide if an email is spam, based on the feature values.

🔢 Example Predictions
Predicting for an email with these features:
dt.predict([[1, 0, 0]])  # Contains "Free", doesn't contain "Win", short email → Output: 1 (Spam)

✅ Model Accuracy
The model was trained and tested on the same small dataset:
dt.score(input, target)  →  1.0(100% accuracy)

📈Visualization
A bar chart is plotted to show feature importances visually:
X-axis: Feature Importance
Y-axis: Feature Names

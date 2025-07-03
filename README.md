# student-pass-or-fail
Steps – How it Works
1.Create Dataset
A small dataset is created with three columns:

Hours_Studied

Attendance (%)

Pass/Fail (1 = Pass, 0 = Fail)

2.Load and View Data
The dataset is loaded using pandas and displayed in a table format.

3.Visualize the Data
A scatter plot is used to show how study hours and attendance affect pass/fail status.

4.Prepare the Data

X: Features (Hours_Studied, Attendance)

y: Label (Pass/Fail)

5.Split the Dataset
The data is split into training and testing sets using train_test_split().

6.Train the Model
A Logistic Regression model from sklearn is trained on the training data.

7.Evaluate the Model
The model's accuracy is checked on the test data using accuracy_score().

8.Make Predictions
The trained model predicts if a new student will pass or fail using .predict().


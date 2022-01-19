DESCRIPTION

You are supposed to detect whether the person is running or walking based on the sensor data collected from iOS device. The dataset contains a single file which represents sensor data samples collected from accelerometer and gyroscope from iPhone 5c in 10 seconds interval and ~5.4/second frequency.

Objective: Practice classification based on Naive Bayes algorithm. Identify the predictors that can be influential.

Actions to Perform:

Load the kinematics dataset as measured on mobile sensors from the file “run_or_walk.csv.”
List the columns in the dataset.
Let the target variable “y” be the activity, and assign all the columns after it to “x.”
Using Scikit-learn, fit a Gaussian Naive Bayes model and observe the accuracy.
Generate a classification report using Scikit-learn.
Repeat the model once using only the acceleration values as predictors and then using only the gyro values as predictors.
Comment on the difference in accuracy between both models.
Access: Click the Labs tab in the left side panel of the LMS. Copy or Note the username and password that are generated. Click the Launch Lab button. On the page that appears, enter the username and password in the respective fields, and click Login.
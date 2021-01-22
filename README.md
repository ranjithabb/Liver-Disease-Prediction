# Liver-Disease-Prediction
A web application to predict whether an individual is suffering from liver disease or not. Random forest algorithm was used for this purpose.
Python 3, Spyder3.3, Flask 1.1, HTML5, CSS3, 
Libraries used- Numpy, pandas, pickle,matplotlib

Application is built using Flask python framework

1. model.py - This contains code for our Machine Learning model to predict liver disease based on training data in 'indian_liver_patient.csv' file.
2. app.py - This contains Flask APIs that receives patient details through GUI or API calls, computes the result based on our model and returns it.
3. templates - This folder contains the HTML template to allow user to enter patient details and displays the predicted disease status.

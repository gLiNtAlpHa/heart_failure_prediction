Heart Failure Prediction using Logistic Regression and Random Forest Classifier
This is a Flask web application that uses machine learning models to predict
heart failure. The models used are logistic regression and random forest
classifiers. The application allows users to input patient information, such as
age, anaemia, creatinine phosphokinase, diabetes, ejection fraction, high blood
pressure, platelets, serum creatinine, serum sodium, sex, smoking, and time. The
models will then predict if the patient is likely to suffer from heart failure.

Dependencies: Python 3 Flask NumPy Pandas Scikit-learn

Usage To use this project, follow the steps below: Clone the repository:
https://github.com/gLiNtAlpHa/heart_failure_prediction.git Install the
Dependencies: Copy code pip install Flask numpy pandas scikit-learn Run the app:
Copy code: python app.py Navigate to http://localhost:5000 in your web browser.
Usage Enter the patient's information in the form provided.

Click the "Predict" button to see the model's prediction.

The application will display a visual representation of the prediction.

Flask App The Flask app has a simple user interface that allows users to input
the following parameters:

Age Anaemia Creatinine Phosphokinase Diabetes Ejection Fraction High Blood
Pressure Platelets Serum Creatinine Serum Sodium Sex Smoking Time The app uses
the trained logistic regression and random forest classifier models to predict
heart failure based on the input parameters. The results are displayed in a
visual representation that shows the probability of heart failure.

Conclusion This project demonstrates the use of logistic regression and random
forest classifier models to predict heart failure based on medical data. The
Flask app provides a user-friendly interface for predicting heart failure and
rendering the results in a visual representation.

Credits This application was developed by Akinlolu Adeboye. The machine learning
models were trained using the Heart Failure Prediction dataset available on
Kaggle.

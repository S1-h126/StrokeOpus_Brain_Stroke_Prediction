StrokeOpus is a web-based stroke risk prediction system designed to predict the likelihood of brain stroke using a Random Forest classifier. The model is trained on a Kaggle dataset containing various health and lifestyle indicators of patients. The application features a Flask backend integrated with a React frontend for seamless user interaction.

Users can input their health data via the web interface, after which the app performs one-hot encoding for categorical features. The processed data is then sent to the backend, where a pre-trained machine learning model (serialized using Pickle) evaluates the stroke risk. The output is a binary prediction indicating whether the user is at risk of a stroke or not.

1) Features Used for Prediction:

   Age

   Gender

   Heart Disease

   Average Glucose Level

   Body Mass Index (BMI)

   Marital Status

   Residence Type

   Work Type

   Hypertension

   Smoking Status


2) Tech Stack

   Frontend: React

   Backend: Flask

   Machine Learning Algorithm: Random Forest

   Libraries: pandas, NumPy, scikit-learn

3) Model Serialization: Pickle

4) Evaluation Metrics:
    Accuracy

    Precision

    Recall

    F1 Score

    Confusion Matrix

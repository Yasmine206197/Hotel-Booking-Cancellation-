**Introduction**
This project involves building a machine learning model to predict hotel booking cancellations based on various features using the Hotel Booking Cancellation dataset. The goal is to create a Flask web application to deploy the model and allow users to input relevant data for prediction.
**Project Structure**
app.py: Flask application script containing API endpoints and model deployment logic.
model.py: Data pre-processing and model selection.
templates/: Directory containing HTML templates for web interface.
Classifiers/: Directory containing the save models.
clf.pkl: Serialized machine learning model (Gradient Boosting Classifier).
RFC_model.pkl: Serialized scaler object for feature scaling.
requirements.txt: File listing all project dependencies.
booking.csv: The comma seperated value data which is processed here.
**Project Dependencies**
The following Python libraries are used in this project:

Flask
scikit-learn
pandas
numpy

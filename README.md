# Cloud-API-Deployment

Wine Quality Prediction API
This repository contains a Flask-based web application and API deployed on Heroku for predicting wine quality based on physicochemical attributes.

Features
Web Interface: A simple interface to test wine quality predictions.
API Endpoint: A REST API for programmatically predicting wine quality.
Model: Machine learning model trained to classify wine quality (e.g., using scikit-learn).


Project Structure
.
├── app.py               # Main Flask app
├── requirements.txt     # Python dependencies
├── Procfile             # Heroku process file
├── wine_quality_model.pkl  # Pre-trained ML model
├── runtime.txt          # Specifies Python version for Heroku
├── README.md            # Documentation


Technologies Used
Flask: For web and API development.
Gunicorn: For serving the app in production.
scikit-learn: For machine learning model training.
Heroku: For cloud deployment.

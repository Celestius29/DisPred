# Header 1 Disease Prediction using Machine Learning

This repository contains a machine learning model for predicting diseases based on symptoms. The model uses three machine learning algorithms: Support Vector Machine (SVM), Gradient Boosting Classifier (GBC), and Random Forest.
Dataset

The dataset used for training and testing the models contains information about symptoms and prognosis for various diseases. The dataset has 132 features related to symptoms and 1 feature for the prognosis of the diseases. There are two datasets: training and testing.
Machine Learning Algorithms
Support Vector Machine (SVM)

The Support Vector Machine (SVM) model is trained using the training dataset. It uses a linear kernel and C=1.0 for regularization. The model is then evaluated on the testing dataset using accuracy and classification report.
Gradient Boosting Classifier (GBC)

The Gradient Boosting Classifier (GBC) model is trained using the training dataset. It uses 100 estimators and a random state of 42 for reproducibility. The model is then evaluated on the testing dataset using accuracy and classification report.
Random Forest

The Random Forest model is trained using the training dataset. It uses 100 trees and a random state of 42 for reproducibility. The model is then evaluated on the testing dataset using accuracy and classification report.
How to Use

    Clone this repository to your local machine.
    Install the required Python packages using pip install -r requirements.txt.
    Run the Jupyter notebook Disease_Prediction.ipynb to train and evaluate the models.
    Optionally, you can deploy the models as a web app or tool for disease prediction.

Future Work

This project can be extended in several ways:

    Using more advanced machine learning techniques such as neural networks.
    Collecting more data to improve the accuracy of the predictions.
    Integrating the model into a web app or tool for easy access by users.

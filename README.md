# Placement-Prognosticator 🚀

## Overview 📚
Placement-Prognosticator is a Flask web application designed to predict whether a student will be placed based on their CGPA, IQ, and Profile Score. The prediction model utilizes machine learning algorithms, specifically a Support Vector Classifier (SVC) and a Random Forest Classifier.

## Web Application 🌐
The Flask web application (app.py) serves as the primary entry point. Users can interact with the application through a web browser, providing input for CGPA, IQ, and Profile Score to receive predictions regarding a student's placement status.

## Instructions to Run the Web Application ⚙️
To run the web application, follow these steps:

1. Ensure you have the required Python packages installed. Install them using the following command:

   ```
   pip install -r requirements.txt
   ```

2. Run the Flask application by executing the following command in your terminal:

   ```
   python app.py
   ```

3. Open your web browser and navigate to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to access the web application.

## Machine Learning Model 🤖
The machine learning model is trained using the placement_prognosticator.ipynb Jupyter Notebook. The notebook covers the following steps:

- Data loading and exploration.
- Splitting the data into training and testing sets.
- Training machine learning models (Logistic Regression, Random Forest, Support Vector Classifier).
- Saving the trained model (model.pkl) using pickle.

## Project Dependencies 🛠️
The required Python packages for running the web application and training the machine learning model are listed in the requirements.txt file. Install these dependencies using the command mentioned above.

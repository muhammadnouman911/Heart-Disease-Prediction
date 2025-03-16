# Heart-Disease-Prediction

## Overview
This project is a **Heart Disease Prediction System** that utilizes **machine learning** to predict the likelihood of heart disease based on various health parameters. The model is trained on a dataset of patient records and provides a simple interface for users to input their health data and receive a prediction.

## Features
- **Machine Learning Model**: Trained using a dataset to predict heart disease.
- **Flask Web Application**: Provides an interactive web-based UI for predictions.
- **Data Visualization**: Helps understand the dataset and model performance.
- **User-friendly Interface**: Simple HTML and CSS for an easy-to-use web page.

## Project Structure
```
Heart-Disease-Prediction/
│── app.py                    # Flask backend application
│── heart_disease.ipynb        # Jupyter Notebook for model training and evaluation
│── heart.csv                  # Dataset used for training
│── heart_disease_model.pkl    # Trained ML model (Pickle file)
│── index.html                 # Frontend - input form for user
│── result.html                # Displays prediction results
│── style.css                  # CSS for styling web pages
│── README.md                  # Project documentation
```

## Installation & Setup
### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

### 2. Install Dependencies
Ensure you have Python installed, then run:
```bash
pip install -r requirements.txt
```
*(If `requirements.txt` is missing, install manually: Flask, pandas, numpy, scikit-learn, pickle, etc.)*

### 3. Run the Application
```bash
python app.py
```
The app will start at **http://127.0.0.1:5000/**.

## Usage
1. Open the web application.
2. Enter required health parameters.
3. Click **Predict** to see the heart disease risk.
4. The result page will display whether the user is at risk or not.

## Dataset
- The dataset (`heart.csv`) contains multiple features like age, cholesterol levels, blood pressure, etc.
- It is preprocessed and used to train a **Logistic Regression / Random Forest / Decision Tree** model (depending on implementation).

## Future Improvements
- Enhance model accuracy with deep learning techniques.
- Deploy the model online for global accessibility.
- Add real-time API integration for healthcare applications.

## Contributors
- **Muhammad Nouman**
- Open for contributions! Feel free to submit **pull requests**.

## License
This project is **open-source** under the **MIT License**.


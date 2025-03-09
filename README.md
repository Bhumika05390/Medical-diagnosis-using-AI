# Ai-Powered Medical Diagnosis System

![Project Logo](https://www.strategyand.pwc.com/m1/en/strategic-foresight/sector-strategies/healthcare/ai-powered-healthcare-solutions/img01-section1.jpg) <!-- Replace with your logo or image -->

A web-based application built using **Streamlit** and **Machine Learning** to predict various diseases based on user input. The system supports predictions for Diabetes, Heart Disease, Parkinson's Disease, Lung Cancer, and Hypo-Thyroid.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Features
- **Multiple Disease Prediction**: Predicts Diabetes, Heart Disease, Parkinson's Disease, Lung Cancer, and Hypo-Thyroid.
- **User-Friendly Interface**: Built using Streamlit for an intuitive and interactive user experience.
- **Machine Learning Models**: Utilizes pre-trained models for accurate predictions.
- **Customizable Inputs**: Users can input relevant health parameters for predictions.

---

## Technologies Used
- **Python**: Primary programming language.
- **Streamlit**: For building the web interface.
- **Scikit-learn**: For training and deploying machine learning models.
- **Pickle**: For saving and loading trained models.
- **Pandas & NumPy**: For data preprocessing and manipulation.
- **HTML/CSS**: For custom styling and layout.

---

## Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Steps to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Bhumika05390/Medical-diagnosis-using-AI.git
   cd Medical-diagnosis-using-AI
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
3.**Run the Streamlit App**:
    streamlit run app.py

4.**Access the App**:
       Open your browser and go to http://localhost:8501.

---

## Usage
1. **Select the disease** you want to predict from the dropdown menu.
2. **Enter the required health parameters** in the input fields.
3. **Click the "Test Result" button** to get the prediction.
4. The system will display whether the person is likely to have the disease or not.

---

## Project Structure
   
     disease-prediction-system/ 
    ├── Models/ # Pre-trained machine learning models
    │ ├── diabetes_model.sav
    │ ├── heart_disease_model.sav
    │ ├── parkinsons_model.sav
    │ ├── lungs_disease_model.sav
    │ └── Thyroid_model.sav
    ├── app.py # Main Streamlit application file
    ├── requirements.txt # List of dependencies
    └── README.md # Project documentation

---

## Acknowledgments
- **Dataset sources**: [Kaggle](https://www.kaggle.com/), [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php).
- **Streamlit** for the amazing web framework.
- **Scikit-learn** for providing machine learning tools.


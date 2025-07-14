#  Personality Prediction using Machine Learning

This project predicts whether a person is an *Introvert* or an *Extrovert* using behavioral and social activity features. It uses *Decision Tree Classifier* model with data preprocessing, feature scaling, and model evaluation.

##  Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Models Used](#models-used)
- [Results](#results)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [Screenshots (optional)](#screenshots-optional)
- [License](#license)

##  Overview

The goal of this machine learning project is to classify people into two personality types — *Introvert* or *Extrovert* — based on their daily habits, social behavior, and preferences. This is a binary classification task implemented using scikit-learn.

##  Dataset

The dataset includes behavioral and social features like:

- Time_spent_Alone
- Social_event_attendance
- Going_outside
- Stage_fear (Yes/No)
- Drained_after_socializing (Yes/No)
- Friends_circle_size
- Post_frequency
- Personality (Target: Introvert/Extrovert)

> Dataset is preprocessed (cleaned, encoded, and standardized) before training.

##  Features

- Binary classification with clean preprocessing
- Z-score standardization using StandardScaler
- Label encoding for binary categorical values
- Interactive prediction function using user input
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrix

---

##  Model Used
 Decision Tree  

##  Results

- *Accuracy*: ~87%
- *Balanced precision & recall* across both classes
- *Confusion Matrix*:

[[219  27] [ 36 214]]

- Shows good generalization and interpretability

##  Getting Started

1. *Clone the repository*  
 ```bash
 git clone https://github.com/your-username/personality-prediction-ml.git
 cd personality-prediction-ml

2. Install dependencies

pip install -r requirements.txt


3. Launch the notebook
Open personality_prediction.ipynb in Jupyter Notebook or VS Code.

 How to Use

1. Run all notebook cells.


2. Use the predict_personality() function to enter your own data.


3. View the predicted personality type (Introvert/Extrovert).

📄 License

This project is open-source and free to use under the MIT License.

 Acknowledgements

Built with Python, scikit-learn, pandas, matplotlib

Created as a learning project in Machine Learning

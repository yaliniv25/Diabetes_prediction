Project Overview:

This project uses a Neural Network (Artificial Neural Network) to predict a person's diabetes status based on various health and lifestyle factors.

Technologies Used:
Python
TensorFlow / Keras
Pandas
NumPy
Scikit-learn
Jupyter Notebook

Dataset:

The dataset contains around 120 rows and 13 columns.

Features:
Age
Gender
BMI
Waist Circumference
Blood Pressure
Fasting Glucose
HbA1c
Insulin
Physical Activity
Family History
Smoking
Diet
Pregnancies

Target:

DiabetesStatus

The target contains three classes:

Normal
Prediabetes
Diabetes

How to Run:
1. Clone the repository
git clone (https://github.com/yaliniv25/Diabetes_prediction.git)
2. Install the required libraries
pip install tensorflow pandas numpy scikit-learn matplotlib
3. Open the notebook

Open:

train.ipynb

using Jupyter Notebook or VS Code.

4. Run the cells

Execute the notebook cells in order to perform preprocessing, train the neural network, and evaluate the model.

MODEL ARCHITECTURE:

The neural network consists of 3 hidden layers.

Input Layer
    ↓
Dense Layer - 16 neurons
    ↓
Dropout - 0.2
    ↓
Dense Layer - 8 neurons
    ↓
Dropout - 0.2
    ↓
Dense Layer - 4 neurons
    ↓
Output Layer - 3 neurons

Configuration:
Hidden layer activation: ReLU
Output activation: Softmax
Optimizer: Adam
Loss function: Sparse Categorical Crossentropy
Output classes: 3

Result:

Test Accuracy: 75%
Test Loss: 0.7575

Future Improvements:
Streamlit dashboard
Hyperparameter tuning
Model comparison
Explainable AI


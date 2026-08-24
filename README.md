# 🏥 Medical Cost Insurance Prediction using Deep Learning

This project aims to predict individual medical insurance charges based on personal and health-related information using a deep learning model. The goal is to assist insurance companies and healthcare providers in estimating insurance premiums more accurately.

## 🚀 Project Overview

- **Problem Statement**: Predict the insurance cost of a patient based on features such as age, sex, BMI, number of children, smoking status, and region.
- **Solution**: A deep learning regression model is built using TensorFlow/Keras to capture complex patterns in the dataset and provide accurate predictions of insurance charges.

## 📊 Dataset

The dataset used is the **Medical Cost Personal Dataset** commonly available on platforms like [Kaggle](https://www.kaggle.com/mirichoi0218/insurance).

### Features:

- `age`: Age of the primary beneficiary
- `sex`: Insurance contractor gender (female, male)
- `bmi`: Body mass index
- `children`: Number of children covered by health insurance
- `smoker`: Smoking status (yes, no)
- `region`: Residential area in the US (northeast, southeast, southwest, northwest)
- `charges`: Individual medical costs billed by health insurance (target variable)

## 🧠 Model Architecture

- Input Layer
- Dense Layers with ReLU activation
- Dropout for regularization
- Output Layer with Linear activation (for regression)
  
The model is trained using:
- **Loss Function**: Mean Squared Error (MSE)
- **Optimizer**: Adam
- **Evaluation Metric**: Mean Absolute Error (MAE), R² Score

## 🔧 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn (for EDA & visualization)
- TensorFlow / Keras (for deep learning)
- Scikit-learn (for preprocessing & evaluation)

## 📈 Results

The model achieved strong performance on the test set with:
- High R² Score
- Low MAE and MSE values

This indicates the model effectively captures the nonlinear relationships between input features and insurance costs.

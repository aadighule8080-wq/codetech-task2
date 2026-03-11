# codetech-task2
# Deep Learning Model for Cricket Match Winner Prediction

## 📊 Project Overview
This project implements a **Deep Learning Model using TensorFlow** to predict the winner of a cricket match based on match statistics such as powerplay runs, wickets, toss result, and venue.

The model uses a **Neural Network architecture** to analyze historical match data and predict the match outcome.

This project was completed as part of the **Data Science Internship Task-2**.

---

## 🎯 Objective

The main objectives of this project are:

- Build a Deep Learning model using **TensorFlow**
- Perform **data preprocessing and feature scaling**
- Train a **Neural Network model**
- Evaluate model performance using accuracy
- Visualize training results

---

## 🗂 Dataset

The dataset contains cricket match details including:

- Series
- Venue
- Team A
- Team B
- Toss Winner
- Toss Decision
- Powerplay Runs
- Powerplay Wickets
- Total Runs
- Match Winner (Target Variable)

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow / Keras
- Matplotlib

---

## 🔄 Project Workflow

1. Data Collection
2. Data Preprocessing
3. Encoding Categorical Variables
4. Train-Test Split
5. Feature Scaling
6. Deep Learning Model Creation
7. Model Training
8. Model Evaluation
9. Result Visualization

---

## 🧠 Deep Learning Model

The model is implemented using **TensorFlow Keras Sequential API**.

Architecture:

Input Layer  
↓  
Dense Layer (64 neurons, ReLU)  
↓  
Dense Layer (32 neurons, ReLU)  
↓  
Dense Layer (16 neurons, ReLU)  
↓  
Output Layer (Softmax)

---

## 📈 Model Training

- Optimizer: **Adam**
- Loss Function: **Sparse Categorical Crossentropy**
- Metrics: **Accuracy**
- Epochs: **50**

---

## 📊 Results

The model was trained on the dataset and evaluated using test data.

Performance was visualized using:

- Training Accuracy
- Validation Accuracy

---

## 📉 Visualization

The model performance is visualized using **Matplotlib** to show:

- Training Accuracy vs Epoch
- Validation Accuracy vs Epoch

---

## 🚀 How to Run the Project

1. Clone the repository

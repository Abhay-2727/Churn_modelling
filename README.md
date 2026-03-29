📌 Project Overview:

This project focuses on predicting customer churn in a banking dataset using a Deep Neural Network (DNN) built with TensorFlow and Keras.
Customer churn refers to customers leaving a bank’s services. Predicting churn helps businesses take proactive actions to retain customers.

🎯 Objective

To build and evaluate a deep learning model that can classify whether a customer will:
Stay with the bank
Leave (churn)

🧾 Dataset
Dataset used: Churn_Modelling.csv

Contains customer details such as:
Credit score
Geography
Gender
Age
Balance
Number of products
Active membership status
Estimated salary

⚙️ Technologies Used
Python
NumPy
Pandas
Scikit-learn
TensorFlow / Keras
Matplotlib
Seaborn

🔄 Workflow
1. Data Preprocessing
Removed irrelevant columns
Encoded categorical variables:
Label Encoding (Gender)
One-Hot Encoding (Geography)
Feature scaling using StandardScaler
Split dataset into:
Training set (80%)
Testing set (20%)

3. Model Architecture
Sequential Deep Neural Network:
Input layer
Hidden layer (12 neurons, ReLU activation)
Dropout layer (0.2 to prevent overfitting)
Output layer (Sigmoid activation)

5. Model Compilation
Optimizer: Adam
Loss Function: Binary Crossentropy
Metrics: Accuracy

7. Training
Epochs: 50
Batch size: 32

9. Evaluation
Model tested on unseen data
Metrics used:
Accuracy
Confusion Matrix
Classification Report (Precision, Recall, F1-score)

📊 Results
Model outputs prediction probabilities
Converts probabilities into binary classification (0 or 1)
Visualized using a confusion matrix heatmap

📈 Output Visualization
Confusion matrix plotted using Seaborn

Displays:
True Positives
False Positives
True Negatives
False Negatives

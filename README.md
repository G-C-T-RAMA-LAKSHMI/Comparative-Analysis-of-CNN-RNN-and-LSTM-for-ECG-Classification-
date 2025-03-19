Comparative Analysis of CNN, RNN, and LSTM for ECG Classification

Overview

This project explores the comparative performance of Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN), and Long Short-Term Memory (LSTM) networks for classifying ECG signals. The models help in diagnosing cardiovascular conditions by identifying different types of heartbeats.

📌 Key Features

Data Preprocessing:

Normalization of ECG signal features

Handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)

Model Architectures:

CNN: Captures spatial patterns in ECG signals

RNN: Recognizes sequential dependencies in time-series data

LSTM: Handles long-term dependencies in ECG sequences

Model Evaluation:

Accuracy, Precision, Recall, and Confusion Matrix

Comparative analysis using bar graphs

📂 Project Structure

Comparative-ECG-Analysis/
│── data/
│   ├── filtered_ptbxl_data.csv       # ECG dataset
│── preprocessing/
│   ├── preprocessing.py               # Data preprocessing (scaling, SMOTE, etc.)
│── models/
│   ├── cnn_model.py                   # CNN model
│   ├── rnn_model.py                   # RNN model
│   ├── lstm_model.py                  # LSTM model
│── evaluation/
│   ├── evaluate.py                     # Model evaluation (accuracy, precision, recall)
│── visualization/
│   ├── visualize.py                    # Graphs comparing models
│── main.py                              # Runs all models and generates comparisons
│── requirements.txt                      # Required libraries
│── README.md                            # Project documentation

🛠 Installation

Step 1: Clone the Repository

git clone https://github.com/yourusername/Comparative-ECG-Analysis.git
cd Comparative-ECG-Analysis

Step 2: Install Dependencies

pip install -r requirements.txt

Step 3: Run the Project

1️⃣ Preprocess Data

python preprocessing/preprocessing.py

2️⃣ Train Models

python models/cnn_model.py
python models/rnn_model.py
python models/lstm_model.py

3️⃣ Evaluate Models

python evaluation/evaluate.py

4️⃣ Visualize Results

python visualization/visualize.py

📊 Results

Models are evaluated using Accuracy, Precision, and Recall.

Bar graphs illustrate the performance comparison of CNN, RNN, and LSTM models.

📌 Conclusion

This project provides insights into the strengths of CNN, RNN, and LSTM for ECG classification. The comparison helps in choosing the best model for healthcare applications.

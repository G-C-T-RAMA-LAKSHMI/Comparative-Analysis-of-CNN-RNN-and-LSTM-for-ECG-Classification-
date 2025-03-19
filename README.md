Comparative Analysis of CNN, RNN, and LSTM for ECG Classification

# Overview

This project conducts a comparative analysis of Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN), and Long Short-Term Memory (LSTM) networks for classifying ECG signals. The analysis evaluates different architectures and kernel sizes to determine the most effective model for ECG classification.

# Dataset

The dataset used is filtered_ptbxl_data.csv, which contains ECG signal data with labels indicating whether the ECG is normal or indicative of myocardial infarction (IMI).

# Key Features

# Preprocessing:

- Filtering and labeling ECG signals based on scp_codes.

- Handling missing values using mean imputation.

- Addressing class imbalance using SMOTE.

- Standardizing features with StandardScaler.

# Model Training & Evaluation:

- Training CNN, RNN, and LSTM models with different architectures.

- Experimenting with kernel sizes (3, 5, 7) for CNN.

- Evaluating models based on accuracy scores.

- Identifying the best model configuration for each kernel size.

# Model Configurations

The study tests five configurations of Conv1D layers (cl_values) and Dense layers (dl_values) across CNN, RNN, and LSTM models:

- cl_values: [8], dl_values: [8]

- cl_values: [8, 16], dl_values: [16, 8]

- cl_values: [8, 16], dl_values: [32, 16, 8]

- cl_values: [8, 16, 32], dl_values: [32, 16, 8]

- cl_values: [8, 16, 32], dl_values: [64, 32, 16, 8]

# Results

Best accuracy scores for each model type across different kernel sizes:

Kernel Size

CNN (Accuracy, Case)

RNN (Accuracy, Case)

LSTM (Accuracy, Case)

3

0.7867, Case 5

0.7802, Case 1

0.7694, Case 1

5

0.7912, Case 5

0.7836, Case 5

0.7710, Case 5

7

0.7962, Case 3

0.7828, Case 5

0.7760, Case 2

# Dependencies

- Python 3.x

- TensorFlow

- NumPy

- Pandas

- Scikit-learn

- Imbalanced-learn

# How to Run

- Install dependencies:

pip install tensorflow pandas numpy scikit-learn imbalanced-learn

- Run the script:

python ecg_classification.py

# Conclusion

The CNN model with kernel size 7 and configuration 3 achieved the highest accuracy (0.7962), making it the most effective model for ECG classification in this study. Further improvements could be made by fine-tuning hyperparameters and incorporating additional ECG signal features.

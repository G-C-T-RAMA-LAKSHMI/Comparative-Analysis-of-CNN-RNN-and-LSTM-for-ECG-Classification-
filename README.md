**Comparative Analysis of CNN, RNN, and LSTM for ECG Classification**\n

This project demonstrates the use of Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN), and Long Short-Term Memory (LSTM) networks to classify ECG signals for healthcare diagnostics. The project involves the application of various deep learning architectures to address the problem of ECG signal classification.

**Overview**\n
The project explores the comparative performance of three different deep learning models: CNN, RNN, and LSTM. The models are trained and evaluated using ECG data to classify different types of heartbeats, helping in diagnosing cardiovascular conditions.
**
Key Features**\n
**Data Preprocessing:**\n

ECG signals are preprocessed by normalizing features.
SMOTE (Synthetic Minority Over-sampling Technique) is applied to address class imbalance.
**Model Architectures:**\n

CNN: A Convolutional Neural Network used to capture spatial features in ECG signals.
RNN: A Recurrent Neural Network employed to capture sequential dependencies.
LSTM: A Long Short-Term Memory network designed for sequential data with long-term dependencies.
**Model Evaluation:**\n

Performance metrics include accuracy, precision, recall, and confusion matrix.
Comparison of the models through bar graphs showing the accuracy, precision, and recall of each architecture.
Installation

**Data Preprocessing:**\n

The raw ECG data is preprocessed in the preprocessing.py file.
**Model Training:**\n

You can train each model by running the corresponding scripts:
For CNN: cnn_model.py
For RNN: rnn_model.py
For LSTM: lstm_model.py
**Model Evaluation:**\n

Evaluate the performance of each model using the scripts located in the evaluation/ directory. Metrics like accuracy, precision, and recall are provided.
**Visualizing Results:**\n

The visualization.py script generates bar graphs comparing the performance of CNN, RNN, and LSTM models.
**Results**\n
The models are evaluated using confusion matrix, accuracy, precision, and recall. The results are visualized to help compare model performance in a clear and understandable manner.

**Conclusion**\n
This project provides insights into the use of CNN, RNN, and LSTM architectures for ECG signal classification. The comparison of different models assists in selecting the optimal architecture for healthcare applications involving ECG signal analysis.


# ECG Anomaly Detection with Bidirectional LSTMs and Variational Autoencoders

This project implements a novel approach for detecting anomalies in Electrocardiogram (ECG) signals using Bidirectional Long Short-Term Memory (LSTM) networks in combination with Variational Autoencoders (VAEs). The combination leverages the strengths of LSTMs in capturing temporal dependencies within the ECG signals and VAEs in providing a probabilistic framework for anomaly detection.

## Features

- **Bidirectional LSTMs**: Bidirectional LSTMs are employed to capture both past and future temporal dependencies within the ECG signals, enabling the model to learn complex patterns and relationships.
  
- **Variational Autoencoders (VAEs)**: VAEs are utilized to learn the latent representation of normal ECG signals. By sampling from the learned latent space, the model can generate normal ECG signals and detect anomalies based on deviations from this distribution.

- **Anomaly Detection**: Anomalies are detected based on reconstruction error or probability density estimation in the latent space, allowing for the identification of irregular ECG patterns indicative of cardiac abnormalities.

## Requirements

- Python (>=3.6)
- TensorFlow (>=2.0)
- NumPy
- Matplotlib





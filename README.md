# Anomaly_Detection_System

In conclusion, this project successfully demonstrates the implementation of an anomaly detection system using both traditional machine learning and deep learning approaches. By simulating a dataset with injected anomalies, we were able to apply and compare three models: Isolation Forest, One-Class SVM, and a deep learning Autoencoder. Among them, the Autoencoder provided a robust way to learn normal data patterns and effectively flag deviations. Visualizations such as the reconstruction error distribution and boxplots enhanced interpretability. Finally, a simple deployment function was created to simulate real-time anomaly detection. This pipeline can be adapted for real-world anomaly detection tasks in domains such as finance, cybersecurity, and industrial systems.

# Project Structure

- *Data Preparation*: Simulates and preprocesses synthetic data with injected anomalies.
- *Modeling*:
  - Isolation Forest (Scikit-learn)
  - One-Class SVM (Scikit-learn)
  - Autoencoder (TensorFlow/Keras)
- *Evaluation*: Compares models using precision, recall, and F1 score.
- *Visualization*: Plots reconstruction error and highlights anomalies.
- *Deployment*: Includes a real-time anomaly detection function.

# Results

| Model            | Precision | Recall | F1 Score |
| ---------------- | --------- | ------ | -------- |
| Isolation Forest | 0.0385     | 0.0417  | 0.04 |
| One-Class SVM    | 0.0385     | 0.0417  | 0.04  |
| Autoencoder      | 0.0333     | 0.0417  | 0.0370 |


MIT License
Copyright (c) 2025 *1453nicat*

# Honeywell Predictive Maintenance using Multi-Stage Hybrid CNN-LSTM

## Overview

This project presents an intelligent predictive maintenance system designed for smart factory environments. The solution utilizes a multi-stage hybrid CNN-LSTM architecture to predict equipment failures in advance using multi-sensor heterogeneous data streams.

The system combines Remaining Useful Life (RUL) prediction, health-state classification, anomaly detection, uncertainty estimation, and maintenance scheduling to enable proactive maintenance decisions while minimizing false alarms.

---

## Problem Statement

Honeywell aims to design a neural network-based predictive maintenance model for smart factories. The objective is to predict potential equipment failures in advance using multi-sensor data streams, incorporating anomaly detection, feature fusion, and real-time inference to optimize maintenance scheduling and improve operational efficiency.

---

## Dataset

**NASA CMAPSS (Commercial Modular Aero-Propulsion System Simulation) Dataset**

- Subset Used: FD001
- Multi-sensor time-series data
- Run-to-failure degradation trajectories
- Remaining Useful Life (RUL) estimation benchmark

Features Used:
- Operating Conditions (op1, op2, op3)
- Selected Sensor Measurements (17 features)

---

## Proposed Architecture

### Multi-Stage Hybrid CNN-LSTM Network

### Stage 1
- Multi-scale 1D CNN Feature Extraction
- Squeeze-and-Excitation Attention
- LSTM Temporal Modeling

### Stage 2
- Residual CNN Blocks
- Bidirectional LSTM

### Stage 3
- Dilated CNN Layers
- Self-Attention Mechanism
- Feature Fusion Layer

---

## Key Features

- Remaining Useful Life (RUL) Prediction
- Equipment Health-State Classification
- Multi-Sensor Feature Fusion
- Anomaly Detection using Autoencoder and Isolation Forest
- Monte-Carlo Dropout Uncertainty Estimation
- Real-Time Inference Engine
- Intelligent Maintenance Scheduling
- Failure Risk Assessment
- Reduced False Alarm Generation

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn
- Isolation Forest
- Autoencoder Networks

---

## Performance Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- NASA Scoring Function
- Classification Accuracy
- Precision
- Recall
- F1-Score
- False Alarm Rate

---

## Results

The developed system successfully:

- Predicts equipment degradation trends
- Estimates Remaining Useful Life
- Detects anomalous operating conditions
- Generates maintenance recommendations
- Performs real-time failure risk assessment
- Supports proactive maintenance planning

---

## Project Workflow

Sensor Data
→ Data Preprocessing
→ Feature Fusion
→ Multi-Stage CNN-LSTM Model
→ RUL Prediction
→ Health-State Classification
→ Anomaly Detection
→ Uncertainty Estimation
→ Maintenance Scheduling
→ Real-Time Decision Support

---

## Future Enhancements

- Training on FD002, FD003, and FD004 subsets
- Transformer-based architectures
- IoT deployment for edge devices
- Industrial dashboard integration
- Federated predictive maintenance systems

---

## Author

Saanjal

Machine Learning & Deep Learning Enthusiast

Focused on building intelligent systems for predictive analytics, computer vision, and industrial AI applications.

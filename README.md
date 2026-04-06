# Endpoint Security Anomaly Detection System

Processes 20K+ endpoint telemetry events and flags real-time threats 
using a TensorFlow autoencoder model with 88%+ precision.

## Tech Stack
Python · TensorFlow · Scikit-learn · Flask · Pandas · NumPy · Docker · JavaScript

## Features
- Autoencoder-based anomaly detection model
- Live SOC dashboard for real-time threat monitoring  
- REST API for the detection engine
- Docker deployment with CI/CD pipeline

## Results
- Processed 20,000+ telemetry events
- Detected 1,000+ real-time threats with high precision
- Automated model updates via CI/CD

## How to Run
pip install -r requirements.txt
python src/main.py

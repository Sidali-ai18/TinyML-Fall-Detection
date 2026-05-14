# Resume Project Entry — TinyML Fall Detection

## Project Title
**TinyML Fall Detection System (Edge AI + Embedded IoT)**

## Summary (2–3 lines)
Built an end-to-end wearable fall-detection system that classifies falls vs daily activities using 3-axis accelerometer time-series data. Trained and optimized a TensorFlow/Keras model in Python, converted it to TensorFlow Lite Micro, and deployed real-time on-device inference to Arduino hardware with BLE-based alerting and user cancel logic.

## Resume Bullets (ATS-friendly)
- Designed and implemented an end-to-end TinyML pipeline: sensor data collection, windowed preprocessing, model training, TensorFlow Lite conversion, and embedded deployment.
- Processed multivariate IMU time-series data using **75-sample sliding windows** (x/y/z accelerometer channels) for binary fall classification.
- Improved model robustness with **3D random rotation augmentation** (SciPy) to handle wearable orientation variance.
- Trained a compact **CNN classifier** in TensorFlow/Keras with dropout regularization and evaluated performance via confusion matrix and false-positive/false-negative metrics.
- Deployed the model to microcontroller firmware using **TensorFlow Lite Micro** with constrained memory allocation (`tensor arena`) for real-time edge inference.
- Implemented an embedded alert workflow with **probability-threshold fall detection**, local buzzer signaling, button-based cancellation/debounce logic, and BLE notification fallback after timeout.

## Tech Stack
**Python, TensorFlow, Keras, NumPy, Pandas, SciPy, scikit-learn, Jupyter/Colab, TensorFlow Lite, TensorFlow Lite Micro, Arduino C/C++, ArduinoBLE, Arduino_LSM9DS1**

## Architecture Keywords
**Edge AI, TinyML, Time-Series Classification, Embedded ML Inference, Wearable Sensing, BLE Alerting, Real-Time Systems**

## Optional “One-Liner” Version
Developed a TinyML-based wearable fall detector using accelerometer time-series CNN inference on Arduino (TensorFlow Lite Micro), with on-device alerting, user override controls, and BLE emergency notification.

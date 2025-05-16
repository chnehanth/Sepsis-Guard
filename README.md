# SepsisGuard: IoT-Enabled Real-Time Sepsis Alert System
SepsisGuard is a real-time healthcare monitoring system that uses IoT sensors and a machine learning model to detect early signs of sepsis. It ensures timely alerts to hospital staff via SMS and dashboards, helping prevent life-threatening complications.

# 🚀 Features
- Real-time monitoring of Heart Rate, Temperature, and Respiration 
- ML-based prediction using Random Forest
- Alerts via SMS and cloud dashboard (ThingSpeak)
- Cost-effective and scalable
- Easy-to-use Arduino-based setup

# 🧰 Technologies Used
- Arduino UNO, DS18B20, LM358
- Python, scikit-learn, pyserial
- ThingSpeak for IoT Cloud
- GSM Module for SMS alerts

# 📦 Folder Structure

| Folder         | Description                             |
|----------------|-----------------------------------------|
| `hardware/`     | Circuit diagrams and sensor specs        |
| `iot_firmware/` | Arduino code to read sensors             |
| `ml_model/`     | Python model training & sepsis detection |
| `alert_system/` | Code to send SMS via GSM                 |
| `cloud/`        | Setup guide for ThingSpeak               |
| `data/`         | Sample and cleaned datasets              |
| `docs/`         | Final PDF report and diagrams            |



# 🧪 How it Works
1. IoT sensors collect real-time vitals.
2. Arduino transmits data via serial to a local system.
3. ML model analyzes vitals for sepsis risk.
4. If risk is high:
     - Alert sound (buzzer)
     - SMS alert to medical staff
     - ThingSpeak dashboard updates


# 📊 Dataset
- Source: PhysioNet Sepsis Challenge (2019)
- Features used: Heart Rate, Temperature, Respiration
- Preprocessing: Imputation, Scaling, Feature Selection

# ML Model
- Random Forest Classifier
- Accuracy: 93.5%
- Training/testing split: 80/20

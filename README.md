# SafeDrop-Smart-IoT-ML-System-for-Real-Time-Water-Quality-Monitoring

## Overview
**SafeDrop** is an intelligent **IoT-based water quality monitoring system** that integrates real-time sensor data collection with **Machine Learning (ML)** for predictive water quality analysis.  
The system measures **pH, TDS, Turbidity**, and **Temperature (DS18B20)** using an **ESP32 microcontroller**, processes the data in real-time, and evaluates the **Water Quality Index (WQI)** for multiple use cases such as **drinking water** and **river water assessment**.

##  Key Features
-  **IoT Integration** – Real-time water quality data collection using ESP32  
-  **Cloud Storage** – Data stored and synced through Firebase Realtime Database  
-  **ML Analytics** – Classification (Good, Moderate, Poor) and Regression (parameter forecasting) models  
-  **Data Processing** – JSON-to-CSV conversion pipeline using Python for dataset preparation  
-  **WQI Framework** – Custom WQI calculation for different water sources and purposes  
-  **Web Dashboard** – Real-time visualization, trend analysis, and decision support  

##  Data and Collection
- **Sensors:** pH, TDS, Turbidity, Temperature (DS18B20)  
- **Interval:** Every 30 seconds for 30 minutes per test  
- **Sources:** Tap water, lake water, Gomoti river water, and industrial wastewater  
- **Storage:** Firebase Realtime Database  

##  Machine Learning Models
| Task | Models Used | Evaluation Metrics |
|------|--------------|--------------------|
| Classification | Logistic Regression, Random Forest, XGBoost | Accuracy, Precision, Recall, F1-score, Confusion Matrix |
| Regression | Linear Regression, Random Forest Regressor, XGBoost Regressor | RMSE, MAE, R², Adjusted R² |

**Model Performance:**  
- Classification Accuracy: **94.3%**  
- RMSE: **3.1**  
- R² Score: **0.952**

##  Future Work
- Integration of additional sensors (e.g., dissolved oxygen, electrical conductivity)  
- Expansion to marine and agricultural water monitoring  
- Edge-based computation and cloud IoT scalability  

##  Author
**Sumaia Akter Shimu**  
Department of Computer Science and Engineering  
**Comilla University, Bangladesh**

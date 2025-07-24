# Industrial-IoT-Fault-Detection
Streamlit app for industrial iot fault detectio# 🛠️ Industrial Fault Detection App

This is a Streamlit app that predicts machine faults using sensor values.

## 🔍 What it does
Enter:
- Vibration (mm/s)
- Pressure (bar)
- RMS Vibration
- Temperature (°C)
- Mean Temperature

Then the model predicts if:
- ✅ No Fault
- ❌ Bearing Fault
- ❌ Overheating
- 
Output Examples
- If temperature is too high → shows Overheating
- If vibration is too high → shows Bearing Fault
- If all values are normal → shows No Fault
Result

## 🚀 How to Run

### Install packages
```bash
pip install streamlit scikit-learn joblib numpy

Run the app:
streamlit run fault detection_app.py

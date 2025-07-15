# 🌊 FLOOD PREDICTOR

A Machine Learning-based project designed to **predict the likelihood of a flood** using environmental features such as rainfall, temperature, humidity, and more. This model helps in early warning and disaster preparedness for flood-prone areas.

---

## 📌 Project Overview

Floods are one of the most devastating natural disasters. The **Flood Predictor** aims to use historical data and environmental parameters to predict the occurrence of floods. It uses supervised learning techniques to train a model that can classify whether a flood is likely based on current weather conditions.

---

## 📁 Dataset

- **File**: `flood_dataset.csv`
- **Features Used**:
  - `Date`
  - `Rainfall` (in mm)
  - `Temperature` (in °C)
  - `Humidity` (%)
  - `River_level` (in meters)
  - `Soil_moisture` (%)
  - `Flood` (Target: 0 = No, 1 = Yes)

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🧠 ML Model Summary

- **Preprocessing**:
  - Missing value handling
  - Feature scaling
  - Label encoding
- **Model Used**:
  - Logistic Regression (can be extended to Random Forest, SVM, etc.)
- **Metrics**:
  - Accuracy
  - Confusion Matrix
  - Classification Report

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/flood-predictor.git
   cd flood-predictor
   ```

2. Install the requirements:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Flood_predictor.ipynb
   ```

---

## 📊 Example Output

```python
Input:
  Rainfall = 110 mm
  Temperature = 28°C
  Humidity = 85%
  River Level = 7.2 m
  Soil Moisture = 70%
  
Output:
  Flood Likely: ✅
```

---

## 📈 Future Enhancements

- Integrate real-time weather API data
- Build a web-based UI using Flask/Django
- Geo-map visualization of flood zones
- Include time-series forecasting

---

## 🛡️ License

This project is licensed under the MIT License 

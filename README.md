# Air-Quality-Prediction-Using-Deep-Learning-A-Sequential-Model-Approach

# **Air Quality Prediction Using Deep Learning**

## **Overview**
This project builds a **deep learning-based Sequential model** to predict **PM2.5 levels** using air pollutant data such as **NO2, SO2, CO, O3, and PM10**. The dataset used is **city_day.csv**, containing air quality data from different Indian cities.

## **Features**
- **Data Preprocessing**: Handles missing values and selects relevant features
- **Feature Scaling**: Uses **StandardScaler** to normalize input data.
- **Deep Learning Model**: Implements a **Sequential neural network** with **Dense and Dropout layers**.
- **Model Training**: Uses **Adam optimizer** and trains with validation.
- **Evaluation**:
  - Computes **Mean Absolute Error (MAE)**.
  - **Loss vs. Epochs** plot to monitor training progress.
  - **Actual vs. Predicted PM2.5 Scatter Plot** for performance evaluation.

## **Installation & Usage**
### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/air-quality-prediction.git
cd air-quality-prediction
```

### **2. Install Dependencies**
```bash
pip install pandas numpy tensorflow scikit-learn matplotlib
```

### **3. Run the Script**
```bash
python air_quality_prediction.py
```

## **Future Improvements**
- Optimize model with **hyperparameter tuning**.
- Explore **CNN/LSTM models** for better time-series predictions.
- Integrate **real-time air quality API** for live predictions.

Contributions are welcome! 🚀



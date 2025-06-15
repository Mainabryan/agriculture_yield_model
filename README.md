# agriculture_yield_model

# 🌾 Crop Yield Prediction with Machine Learning

This project uses real-world-inspired agricultural data to predict crop yield (in tons) based on multiple environmental and agricultural factors. The final result is deployed using a Streamlit web application for easy interaction.

## 📊 Dataset Overview
The dataset contains 1,000 rows and the following columns:

- `Month`: Month of observation (1–12)
- `Region`: Agricultural region (e.g., Rift Valley, Western)
- `Crop Type`: Type of crop (e.g., Maize, Beans, Tea, Wheat)
- `Rainfall (mm)`: Monthly rainfall
- `Fertilizer Used (kg)`: Amount of fertilizer used per acre
- `Pesticide Usage (L)`: Amount of pesticide used per acre
- `Temperature (°C)`: Average monthly temperature
- `Soil Type`: Type of soil (e.g., Clay, Sandy)
- `Market Access (%)`: % of farmers with buyer access
- `Crop Yield (tons)`: 🌟 Target variable

## 🧠 Goal
Build a Multiple Linear Regression model that predicts the crop yield based on the inputs above.

## 🔍 ML Workflow
1. **Data Preprocessing**: Handle categorical variables, normalize numeric features.
2. **Feature Engineering**: One-hot encode Region, Crop Type, Soil Type.
3. **Model Building**: Train a regression model using scikit-learn.
4. **Evaluation**: Use R² Score and MSE to evaluate performance.
5. **Deployment**: Streamlit app to make yield predictions in real time.

## 🚀 Streamlit App Features
- Select region, crop type, soil type
- Adjust rainfall, fertilizer, pesticide, temperature, and market access
- Predict crop yield instantly
- Visual insights (charts coming soon!)

## 📁 Files
- `agriculture_yield_dataset.csv`: Dataset used for modeling
- `app.py`: Streamlit application (create with help from this repo)
- `yield_model.pkl`: Trained regression model (to be generated)
- `README.md`: Project documentation

## 📣 How to Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

## 🤝 Credits
Developed by Bryan Waweru using guidance from ChatGPT (Nova). Built to support smart farming through data-driven insights.

## 🌍 License
MIT License – Free to use and modify.

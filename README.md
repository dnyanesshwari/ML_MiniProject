# 🌱 Renewable Energy Suitability Prediction using Machine Learning

This mini project analyzes climate data using machine learning algorithms to determine the most suitable locations in India for setting up solar or wind energy plants. By processing historical weather data, we can classify and forecast areas with high renewable energy potential, aiding sustainable energy development.

---

## 📁 Dataset

We use a weather dataset containing temperature, wind speed, and humidity records for multiple Indian cities. A dummy dataset (`dummy_weather_data.csv`) under 25MB is provided for demonstration purposes.

**Sample Columns:**
- `timestamp`
- `location`
- `temperature_C`
- `wind_speed_kmph`
- `humidity_percent`

---

## 🧠 Machine Learning Models Used

- **K-Means Clustering** – For region segmentation based on weather conditions
- **Linear Regression** – For future weather-based suitability prediction (till 2050)
- **Decision Tree, Random Forest, KNN, Naive Bayes, Logistic Regression** – For classification of energy plant type (solar/wind)

---

## 📊 Features

- Weather condition analysis (Temperature, Wind, Humidity)
- Energy type recommendation system (Solar/Wind)
- Prediction of future trends in renewable energy suitability
- Streamlit dashboard for interactive exploration
- Geo-visualization using PyDeck

---

## 🚀 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/renewable-energy-ml.git
   cd renewable-energy-ml
   
##Install dependencies

bash
Copy
Edit
pip install -r requirements.txt

##Run the Streamlit dashboard
bash
Copy
Edit
streamlit run app.py

##🌍 Future Enhancements
Integration with real-time weather APIs
State-wise energy policy mapping
Deployment as a web app with user-uploaded data

##📜 License
This project is open-source and available under the MIT License.

## contact 
Gmail - 2317026@ritindia.edu

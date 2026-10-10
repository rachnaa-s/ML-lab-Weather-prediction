# 🧪 ML Lab Work 01: Real-Time Data Collection via API

**Course:** Machine Learning Lab  
**Lab Assignment:** 01  
**Topic:** Data Acquisition, Dataset Generation (CSV), and Version Control  

---
# 🌦️ Weather Prediction using Machine Learning

## 📌 About the Project
This project focuses on predicting weather conditions using Machine Learning and historical weather data. It uses data analysis and predictive modeling to identify weather patterns and generate forecasts.

## 🎯 Objectives
- Analyze historical weather data.
- Understand weather patterns and trends.
- Build a Machine Learning model for weather prediction.
- Evaluate model performance and prediction accuracy.

## 🛠️ Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Machine Learning

## ⚙️ Project Workflow
1. Load the weather dataset.
2. Explore and visualize the data.
3. Clean and preprocess the dataset.
4. Select relevant features for prediction.
5. Train a Machine Learning model.
6. Evaluate the model's performance.
7. Generate weather predictions.

## 🚀 How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Upload the required dataset or connect to its source.
3. Install the required libraries, if needed.
4. Run the notebook cells sequentially.
5. Review the model results and predictions.

## 📊 Expected Outcome
The project aims to demonstrate how Machine Learning can be used to analyze weather data and predict weather-related conditions.

## 🔮 Future Improvements
- Integrate real-time weather APIs.
- Improve prediction accuracy with additional weather features.
- Build an interactive weather prediction dashboard.
- Extend forecasting to multiple locations.

## 👩‍💻 Project Type
Machine Learning | Data Analysis | Weather Forecasting

---

**Note:** Prediction results depend on the dataset, selected features, and model performance. They are estimates and may not represent actual weather conditions.

## 🛠️ Tools & Technologies
* **Language:** Python 3.x
* **Environment:** Google Colab
* **Libraries:** `requests`, `pandas`
* **API:** OpenWeatherMap API
* **Version Control:** Git & GitHub

---

## 📋 Methodology & Steps

1. **API Integration:** Sent HTTP GET requests to OpenWeatherMap REST API endpoint.
2. **Data Parsing:** Extracted JSON parameters like Temperature, Humidity, Pressure, Wind Speed, and Weather Condition.
3. **DataFrame Construction:** Converted raw unstructured JSON response into a structured Pandas DataFrame.
4. **CSV Export:** Exported processed data to `weather_ml_dataset.csv`.
5. **Deployment:** Pushed the notebook and CSV dataset to GitHub for documentation.

---

## 📊 Dataset Description (`weather_ml_dataset.csv`)

| Column Name | Description | Unit |
| :--- | :--- | :--- |
| `City` | Name of the target city | String |
| `Temperature_C` | Measured temperature | °C |
| `Feels_Like_C` | Perceived temperature | °C |
| `Humidity_%` | Relative atmospheric humidity | % |
| `Pressure_hPa` | Atmospheric pressure | hPa |
| `Wind_Speed_m_s` | Wind velocity | m/s |
| `Weather_Condition` | Primary weather description | String |

---

## 🚀 How to Run

1. Open `Weather_API_Data_Collection.ipynb` in Google Colab.
2. Set `API_KEY` parameter with a valid OpenWeatherMap API key.
3. Run all cells to generate `weather_ml_dataset.csv`.

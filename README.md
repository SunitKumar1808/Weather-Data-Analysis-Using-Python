# 🌦️ Weather Data Analysis & Crop Recommendation System – India 🇮🇳
This project presents an in-depth exploratory data analysis (EDA) of synthetic weather data collected from different Indian cities, containing over 10,000 records. The data includes essential weather features like temperature, humidity, rainfall, wind speed, and weather conditions, with an additional column that recommends suitable seasonal crops (Kharif, Rabi, Zaid) based on temperature and rainfall.

The main aim is to provide insights into weather trends, and more importantly, offer data-driven crop recommendations to enhance agricultural decision-making and support climate-smart farming practices.

# 📌 Project Objectives
Analyze weather conditions across multiple Indian cities.

Understand how climate factors like temperature and rainfall influence crop suitability.

Recommend seasonal crops based on weather patterns.

Visualize trends using a variety of graphs and plots.

Identify ideal locations and seasons for farming.

# 📁 Dataset Overview
The dataset used in this project contains the following features:

Column Name	Description
Date	Date of observation (random within the last 10 years)
City	Indian city where weather is recorded
Temperature (°C)	Daily average temperature
Humidity (%)	Daily humidity percentage
Rainfall (mm)	Daily rainfall in mm
Wind Speed (km/h)	Wind speed at that time
Weather Condition	Description like Sunny, Rainy, Foggy, etc.
Recommended Crop	Suggested crop based on temperature & rainfall
# 🛠️ Tools & Libraries Used
Python – Primary language for analysis

Jupyter Notebook – Development and analysis environment

Pandas – Data manipulation and analysis

NumPy – Numerical operations

Matplotlib – Static data visualizations

Seaborn – Statistical graphics and advanced visualizations

Datetime – For date and time extraction

# 📊 Data Visualizations Used
To make insights clearer and more interactive, the following graphs and plots have been implemented:

📈 Histograms – For distribution of temperature across the dataset

📊 Bar Charts – To compare weather conditions and rainfall per city

📉 Line Graphs – For showing monthly temperature and rainfall trends

📌 Pie Charts – Distribution of recommended crops

🧮 Box Plots – To analyze rainfall and temperature variation across crops

🧭 Heatmaps – For understanding correlation between weather features

☁️ Scatter Plots – Visual relationship between temperature and rainfall

# 📚 Topics Covered in This Project
1. Basic Data Exploration
Shape, datatypes, null checks, descriptive statistics

Unique values and frequency distributions

2. City-wise Weather Analysis
Average temperature, rainfall, and wind speed by city

Most common weather condition and top crop per city

3. Monthly Trends Analysis
Monthly temperature and rainfall averages

Visual trends using line and bar plots

Seasonal weather patterns

4. Crop Recommendation Logic
Crops divided into Kharif, Rabi, and Zaid seasons

Recommendation based on:

Temperature > 25°C and Rainfall > 100mm → Kharif crops

Temperature < 20°C and Rainfall < 50mm → Rabi crops

Others → Zaid crops

5. Relationship between Weather and Crops
Temperature and Rainfall ranges for each crop

Correlation between weather features

Crop suitability for specific weather conditions

6. Farming Suitability by City
Best cities for agriculture based on rainfall, humidity

Ideal crops for each region

# 🔍 Insights Gained
Certain cities have consistently high rainfall and are suitable for Kharif crops like Rice and Maize.

Regions with dry and cool climates are better for Rabi crops like Wheat and Barley.

Temperature and rainfall show moderate correlation with the crop types.

Pie and bar chart analysis help identify the most frequently recommended crops.

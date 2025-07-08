🌫️ India Air Quality Index Dashboard Project

📌 Overview

This project presents a comprehensive Air Quality Index (AQI) Dashboard for major Indian cities—Delhi, Jaipur, Lucknow, Mumbai—by analyzing and visualizing air pollution data from 2022 to 2024. It combines real-time AQI values with seasonal and city-based breakdowns to uncover patterns and insights that can aid citizens, researchers, and policymakers.

📊 Key Features

✅ Dashboard Highlights

Average AQI across India (2019–2024)

Maximum & Minimum AQI recorded

% of Safe Days (AQI ≤ 50)

AQI Trends Over Years by City

AQI by Season (Winter, Summer, Monsoon, Autumn)

Pie Chart: Distribution of AQI Categories (Moderate, Satisfactory, Poor, etc.)

Interactive Filters: City, Season, Date Range


📍 Cities Covered

Delhi

Jaipur

Lucknow

Mumbai

📁 Project Structure

Air-Quality-Index/
 1. README.md                      
 2. Air-Quality-Dashboard.pbix      
 3. AQI-Dashboard.pdf       
 4. data/
    a. Air-Quality-2024.csv             
    b. aqi_weather_merged_2022_2024.csv 
    c. cleaned_aqi_with_season_fixed.csv
    d. weather_data_2019_2024.csv
                
 5. notebook/
    a. cleaned_aqi_data-checkpoints.ipynb                          

📌 Data Sources


CPCB Open AQI Data

VisualCrossing Weather API

[Indian Meteorological Department (IMD)] (for seasonal classification)

🔧 Tools Used

Power BI (Dashboard creation & filtering)

Python (Data cleaning, merging, feature engineering)

Pandas, NumPy, Regex, Matplotlib

Jupyter Notebook (for EDA)


💡 Insights Uncovered

Winter consistently shows the worst AQI levels, especially in Delhi and Lucknow

Safe Days (< 50 AQI) are extremely rare across all cities

Seasonality plays a major role in air pollution, with monsoon showing slight improvements

AQI levels are improving slightly post-2023 in some cities due to policy actions and awareness

📈 Example Visuals



🚀 How to Use

Clone or download this repository

Open the India-AQI-Dashboard.pbix file in Power BI Desktop

Apply filters by City, Season, Date

View insights and download visual PDF if needed

🙋‍♀️ Author

Yukta Bansal
Computer Science Student 
Passionate about solving real-world issues through clean data and clear dashboards

📮 Feedback

If you liked this dashboard or want to collaborate on similar environmental projects, feel free to connect or suggest improvements!

⭐ Star this Repo

If this helped you understand AQI in India or saved your time, a star would be much appreciated!

📌 Tags

#PowerBI #AirQuality #AQI #India #DataVisualization #Dashboard #DataScience #Environment
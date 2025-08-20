🌤️ Live Weather Dashboard – Power BI
This project is an interactive weather analytics dashboard built in Power BI, powered by live data from a weather API.
The goal was to transform raw API data into a visually engaging and decision-friendly dashboard, combining real-time insights with short-term forecasting.

📊 Features
✅ Current Weather Metrics

Temperature (°C)

Humidity (%)

Pressure (hPa)

✅ Wind Analysis

Wind Speed (km/h or m/s)

Wind Direction with compass visuals

✅ Air Quality Insights

AQI (Air Quality Index) values

Clear indicators for safe vs unsafe conditions

✅ Time-based Insights

Sunrise & Sunset

Current Local Time display

✅ Cloud Cover & Visibility

Cloud %

Sky condition indicators

✅ Forecasting

📈 2-Day Temperature Forecast to support proactive planning

⚙️ Tools & Technologies
Power BI → Interactive data visualization

Weather API → Live + forecast data extraction

DAX (Data Analysis Expressions) → Custom measures for:

Sunshine Duration

Local Time tracking

Pressure conversion (if needed)

JSON Data Handling → Parsing API responses into Power BI

🛠️ How It Works
Data Connection

Weather API integrated directly into Power BI using Web connector

API returns live + forecast data in JSON format

Data Transformation

Used Power Query to clean and shape data

Extracted key fields: temperature, humidity, wind, AQI, sunrise/sunset, forecasts

Custom Calculations (DAX)

Current Local Time – dynamic time display

Sunshine Duration – difference between sunset and sunrise

Pressure conversion if required

Visualization Layer

Designed KPIs, Cards, and Charts for easy interpretation

Included forecasting visuals for next 2 days

💡 Key Learnings
Connecting & consuming live APIs inside Power BI

Writing DAX measures for time-based and calculated insights

Designing dashboards that go beyond “current data” by adding predictive context

Dashboard storytelling with weather data

📸 Dashboard Preview

🚀 Future Improvements
Extend forecast beyond 2 days (weekly trend)

Add severe weather alerts (rain, storm, AQI warnings)

Deploy as a public Power BI Service dashboard

🔗 Links
📂 GitHub Repository: [this repo link]

💼 LinkedIn Post: [your LinkedIn project showcase link]

✨ If you like this project, don’t forget to ⭐ the repo!


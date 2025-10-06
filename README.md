# 🚴‍♂️ OLA Bike Rides – Data Analysis Dashboard  

## 📘 Overview  
This project analyzes **OLA Bike Ride Requests** data to explore how **weather, temperature, humidity, and seasons** influence ride demand.  
Built using **Power BI** and **SQL**, it provides actionable insights that help understand user behavior and demand patterns.  

---

## 🎯 Objectives  
- Explore ride data to identify **seasonal and weather-based trends**  
- Build an **interactive Power BI dashboard**  
- Derive **data-driven insights** to improve operational strategies  
- Strengthen **data storytelling** and visualization skills  

---

## 🧩 Tools & Technologies  
| Tool | Purpose |
|------|----------|
| **Power BI** | Data cleaning, modeling, visualization |
| **SQL** | Data analysis and trend exploration |
| **Excel / CSV** | Data preparation |
| **DAX** | Calculations and KPIs |
| **GitHub** | Version control and portfolio showcase |

---

## 📊 Key Insights  
- 🌡️ **Average Temperature:** 20.14°C – ideal for high ride activity  
- 💧 **Average Humidity:** 59.95% – slightly lowers ride frequency  
- 💨 **Average Wind Speed:** 25 km/h – minimal effect on rides  
- 👥 **Users:** 1M+ registered | 267K casual riders  
- ☀️ **Seasonal Trend:** ~335K+ rides per season (stable demand)  
- 🌦️ **Weather Impact:** Clear weather = highest rides (25%)  
- 📈 **Monthly Peak:** July–September & December show top activity  

---

## 🧠 SQL Query Example  
```sql
-- Find top 3 months with the highest total rides
SELECT month, SUM(total_rides) AS total_rides
FROM ride_data
GROUP BY month
ORDER BY total_rides DESC
LIMIT 3;

👨‍💻 Author

Bharath Telugu
📧 telugubharath4@gmail.com

🔗 LinkedIn:




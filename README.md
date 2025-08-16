# 🏃‍♂️ Fitness Activity KPI Analysis

This project explores detailed Key Performance Indicators (KPIs) from two perspectives: full-session weather-integrated data and activity-session-specific metrics. The goal is to uncover actionable patterns related to athletic performance, environmental impact, and personal fitness trends using Python and visual data analysis.

## 📁 Project Structure

- **`ImprovedData_FullKPI.ipynb`**  
  A comprehensive analysis of activity data combined with detailed weather variables (temperature, wind speed, humidity, rainfall). This notebook focuses on environmental factors and how they impact training metrics.

- **`Session_Level_Activity_KPIs.ipynb`**  
  A session-level analysis that dives into personal performance KPIs like steps, cadence, heart rate, and speed. It identifies intra-session patterns and physiological insights.

---

## 📊 Key Insights

### From `ImprovedData_FullKPI.ipynb`
- **Weather vs Heart Rate**: Analyzed how average heart rate correlates with temperature, humidity, wind speed, and rainfall.
- **Rainfall Impact**: Rainy sessions were fewer and often shorter in duration.
- **Time of Day Trends**: Training frequency peaks during early morning and evening.
- **Heart Rate Distributions**: Visualized distributions across weather types and time slots.
- **Speed & Distance Patterns**: Scatter plots reveal how speed and distance vary with temperature and heart rate.
- **Box Plots**: Compared activity scores across temperature and rainfall conditions.

### From `Session_Level_Activity_KPIs.ipynb`
- **Average Heart Rate Histogram**: Shows how frequently specific heart rate ranges occurred across sessions.
- **Calories vs Activity Score**: Explores correlation between activity score and calories burned.
- **Steps and Speed Relationship**: Evaluated cadence and speed over multiple activities.
- **Top 10 Sessions by Speed**: Ranked fastest sessions based on recorded average speed.
- **Training Time Distribution**: Identifies most common session durations.

---

## 🛠️ Tools & Libraries

- Python 3.x
- pandas
- matplotlib
- seaborn
- numpy

---

## 🧠 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/srihariichandran/Fitness-Activity-KPI-Analysis.git

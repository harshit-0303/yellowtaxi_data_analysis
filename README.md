# 🚕 Yellow Taxi Trip Data Analysis using Python & Power BI  

## 📊 Project Overview  
This project focuses on analyzing **New York Yellow Taxi Trip Data** to uncover insights into passenger behavior, fare patterns, and trip characteristics.  
The goal is to transform raw trip data into meaningful business insights using **Python for data analysis** and **Power BI for visualization**.  

---

## 🎯 Objectives  
- Perform **data cleaning and preprocessing** to ensure high-quality, accurate data.  
- Conduct **exploratory data analysis (EDA)** to identify trends and outliers.  
- Apply **statistical hypothesis testing** to validate key assumptions.  
- Build an **interactive Power BI dashboard** for business insights and storytelling.  

---

## 🧩 Tech Stack  
- **Languages & Tools:** Python, Power BI  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scipy, statsmodels  
- **Techniques:** EDA, hypothesis testing, data visualization, DAX measures  

---

## 🧹 Data Cleaning & Preprocessing  
Performed in Python:  
1. Converted pickup and dropoff columns to **datetime** format.  
2. Dropped **null values** (3% in passenger count).  
3. Removed **duplicate records**.  
4. Changed **data types** (e.g., passenger_count to int).  
5. Filtered out **invalid trip distances and fares** to improve accuracy.  

---

## 🔍 Exploratory Data Analysis (EDA)
Key analyses performed:
- Trip distribution by **duration**, **distance**, and **fare amount**.  
- Correlation between **trip distance and fare amount**.  
- Average fare by **payment type** (Card vs Cash).  
- **Passenger count** trends and their impact on fare.  
- Time-based analysis: busiest hours and average trip duration per hour.  

---

## 📊 Hypothesis Testing  
- **Objective:** Check if there’s a significant difference in mean fare between **Card** and **Cash** payments.  
- **Method:** Independent **T-test** using `scipy.stats`.  
- **Result:** Null hypothesis rejected (p-value < 0.05), indicating a statistically significant difference between payment methods.  

---

## 📈 Power BI Dashboard Highlights  
- **Trip Duration & Distance Analysis:** Visualizes ride time vs distance distribution.  
- **Fare Trends:** Displays average fare by payment type and trip distance.  
- **Passenger Insights:** Shows most common passenger counts and their impact on revenue.  
- **Interactive Filters:** Allow filtering by date, time, and payment mode for flexible exploration.  

---

## 🧠 Key Insights  
- **Card payments** were slightly higher on average than cash payments.   
- **Short-distance trips** made up a major portion of total rides.  
- Correlation between **trip distance and fare** is positive but not perfectly linear due to flat-rate patterns.  

---

## 🚀 Outcome  
- Built an **interactive Power BI dashboard** summarizing trip trends and fare patterns.  
- Combined **Python analytics** and **Power BI visualization** for end-to-end analysis.  
- Helped uncover actionable insights for optimizing pricing and understanding customer behavior.  

---

  

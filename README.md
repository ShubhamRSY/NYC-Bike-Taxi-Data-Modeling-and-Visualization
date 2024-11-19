# 🚖 NYC Taxis and Citi Bike Data Analysis Project 🚴‍♂️

Welcome to the **NYC Taxis and Citi Bike Data Analysis** repository!  
This project is a deep dive into the bustling transportation ecosystem of New York City, using advanced **data science techniques** to uncover critical insights. Whether you're an urban planner, a data enthusiast, or an environmental advocate, this repository offers a comprehensive analysis of NYC's taxi and bike systems, providing actionable recommendations for smarter transportation.

---

## 🚀 Project Overview

This project analyzes **multi-modal transportation data** from New York City to answer pivotal questions, such as:
- **What are the most popular transportation modes based on time, location, and demographics?**
- **How can we forecast demand for better resource allocation and cost efficiency?**
- **What are the economic and environmental implications of different transportation modes?**

Each aspect of this study is tackled in four distinct sub-projects:
1. **Project 1: Exploratory Data Analysis (EDA) and Preprocessing**  
   Understand the data structure, clean the datasets, and derive preliminary insights.
2. **Project 2: Demand Forecasting with Machine Learning**  
   Build predictive models to forecast usage patterns and inform operational strategies.
3. **Project 3: Economic Analysis for Optimal Transport Recommendations**  
   Analyze costs, benefits, and user preferences to identify the best transport options.
4. **Project 4: Geographic Insights and Visualization**  
   Use mapping techniques to reveal spatial trends in demand and usage.

---

## ✨ Key Features

- 🚀 **Exploratory Data Analysis**: Discover patterns in transportation usage across different times, locations, and demographics.
- 🤖 **Predictive Modeling**: Leverage advanced machine learning techniques to predict demand with high accuracy.
- 💰 **Economic Optimization**: Compare costs and efficiencies to recommend the most suitable transportation options.
- 🗺️ **Geographic Mapping**: Visualize high-demand zones and transit trends to support city planning.
- 🌱 **Environmental Insights**: Evaluate the ecological impact of bike-sharing compared to taxi services.

---

## 🛠️ Data Preparation and Preprocessing

### Initial Dataset Overview
- **Green Taxi**: 51,837 rows, 20 columns  
- **Yellow Taxi**: 3,076,903 rows, 19 columns  
- **Citi Bike**: 112,443 rows, 13 columns  

### Post-Cleaning Dataset
- **Green Taxi**: 46,827 rows  
- **Yellow Taxi**: 2,729,770 rows  
- **Citi Bike**: 112,443 rows  

### Preprocessing Highlights
- Unified timestamps across datasets for consistent analysis.
- Created grouping variables for pickup hour, location, and day type.
- Removed missing values and irrelevant columns for optimized performance.

---

## 📈 Exploratory Data Analysis Highlights

### Key Observations:
- **Citi Bike Usage**: Peaks during morning (8–9 AM) and evening (5–7 PM) rush hours, aligning with commuter patterns.
- **Yellow Taxis**: Predominantly active in Manhattan, especially during business hours.
- **Green Taxis**: Serve outer boroughs like Brooklyn and Queens, catering to underserved areas.

---

## 🔍 Predictive Modeling for Demand Forecasting

### Key Features Used:
- `pickup_hour`, `day_of_week`, `is_weekend`, `is_holiday`

### Best Performing Model:
- **Model**: Random Forest Classifier  
- **Accuracy**: 97%  
- **Key Insight**: Time of day is the most significant predictor of transportation demand.

---

## 💡 Economic Analysis and Recommendations

### Findings:
- **Citi Bikes**: Cost-efficient for short trips, particularly during peak hours.
- **Yellow Taxis**: Faster for medium-to-long trips, especially in Manhattan.
- **Surge Pricing Impact**: Increases taxi fares significantly during peak demand.

---

## 🌍 Geographic Insights

### Demand Hotspots:
- **Yellow Taxis**: Concentrated in Manhattan near Times Square, Wall Street, and Broadway.
- **Green Taxis**: Cover neighborhoods like Brooklyn, Queens, and Bronx.
- **Citi Bikes**: Predominantly active around Central Park, Grand Central, and Penn Station.

---

## 🌟 Why This Project Matters

- **Urban Planning**: Helps NYC authorities optimize transit systems for efficiency.
- **Business Value**: Provides taxi companies and Citi Bike operators with actionable insights for better operations.
- **Sustainability**: Encourages eco-friendly choices, reducing the city's carbon footprint.

---

## 📜 License

This project is open-source under the [MIT License](LICENSE). Contributions are welcome!

---

## 📬 Contact

For questions or collaboration, feel free to reach out!

# 🏨 Hotel Data Analysis

This project provides a comprehensive analysis of hotel booking data, focusing on booking trends, occupancy, revenue, and customer ratings across multiple properties and cities. The analysis is performed using a Jupyter Notebook and is suitable for hotel managers, data analysts, and anyone interested in hospitality analytics.

---

## 📘 Project Overview

The notebook explores hotel booking records, property details, room categories, and booking platforms to uncover insights into:

- Occupancy rates and capacity utilization  
- Revenue generation and realization  
- Booking status patterns (Checked Out, Cancelled, No Show)  
- Customer ratings and guest demographics  
- Trends across cities, property categories, and time periods  

---

## 🔍 Key Features

- **Data Cleaning**  
  Handles missing values, inconsistent date formats, and negative/invalid guest counts.

- **Occupancy Analysis**  
  Calculates occupancy percentages for each property, room category, and date.

- **Revenue Analysis**  
  Compares generated vs. realized revenue, segmented by booking status and platform.

- **Trend Analysis**  
  Identifies booking patterns by month, week, and day type.

- **Property & Room Segmentation**  
  Breaks down performance by property, city, category, and room class.

- **Customer Insights**  
  Analyzes guest counts and rating distributions.

---

## ⚙️ How to Use

### ✅ Requirements

- Python 3 
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`, `matplotlib`

### ▶️ Running the Analysis

1. Open the `hotel_data_analysis.ipynb` notebook in Jupyter.
2. Run all cells sequentially to:
   - Load and clean the data
   - Perform feature engineering
   - Generate insights and visualizations

### 🛠️ Customization

- Modify the notebook to analyze specific date ranges, properties, or booking statuses.
- Add your own visualizations or KPIs as needed.

---

## 📈 Sample Insights

- **Occupancy Rate**  
  ```text
  Occupancy (%) = (Successful Bookings / Capacity) × 100

- **Revenue Leakage**  
  Can be identified by comparing `revenue_generated` vs. `revenue_realized`.

- **Booking Platform Performance**  
  Performance can be benchmarked (e.g., direct online vs. OTA platforms).

- **Guest Ratings**  
  Guest feedback and ratings provide insight into overall service quality and customer satisfaction.

---

## 📝 Notes

- The dataset contains some negative values for guest counts and missing ratings. These are handled during the data cleaning steps.
- The analysis can be extended to include predictive modeling or deeper segmentation as needed.

---

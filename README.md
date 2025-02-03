# Airline-data-analysis
# ✈️ Power BI Flight Analysis Dashboard

## 📌 Overview
This project analyzes flight, passenger, and ticket information using **Power BI**, focusing on:
- Data **Cleaning** and **Transformation**
- Data **Modeling** with **Star Schema**
- **DAX Calculations** for flight and passenger insights
- **Interactive Visualizations** for airline performance tracking

## 📂 Project Structure
- **`data/`** → Contains raw datasets (Flight, Passenger, Ticket)
- **`dashboards/`** → Contains the `.pbix` file with the Power BI dashboard
- **`scripts/`** → SQL queries used for data transformation
- **`reports/`** → Project documentation and analysis report

## 🚀 Key Features
- **Data Cleaning & Preparation:** Removing duplicates, renaming columns, changing data types.
- **Data Modeling:** Star schema with **Flight as Fact Table** and **Passenger, Ticket as Dimension Tables**.
- **Calculated Columns:** Flight classification (`Best` vs. `To Be Improved`).
- **Visualizations:** **Bar charts, Pie charts, Tree maps**, and more.
- **Row-Level Security (RLS):** Implemented for Airline A.
- **Scheduled Refresh:** Configured to update daily at 5 PM.

## 📊 Key Insights
- **Airline A** has the highest passenger count.
- **Confirmed Tickets** account for **38%** of total bookings.
- **Flights by Destination:**
  - **Houston:** 43 flights
  - **Los Angeles:** 42 flights

## 📸 Dashboard Screenshots
![Dashboard Overview](visualizations/dashboard_overview.png)
![Passenger Insights](visualizations/passenger_insights.png)

## 🛠 Technologies Used
- **Power BI**
- **SQL (PL/SQL, SQL Server)**
- **DAX (Data Analysis Expressions)**
- **Excel for Data Preparation**

## 📥 How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/PowerBI-Flight-Analysis.git

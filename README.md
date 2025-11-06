# AICW_PowerBI_Energy_Consumption_Analysis

# ⚡ Energy Consumption Analysis – Power BI Project

## 📊 Project Overview
This Power BI project provides a detailed **Energy Consumption Analysis** for **Gas**, **Electricity**, and **Water** usage.  
It helps monitor utility performance, identify high-consumption patterns, and optimize resource utilization across locations or time periods.

By visualizing consumption data through interactive dashboards, this project supports **data-driven decisions for energy efficiency** and **sustainability planning**.

---

## 🎯 Objectives
- To analyze **monthly and yearly trends** of gas, electricity, and water consumption.
- To compare **usage and cost distribution** across different departments or locations.
- To identify **peak consumption periods** and detect possible wastage.
- To provide **data transparency** for decision-makers in energy management.

---

## ⚙️ Tools & Technologies Used
- **Microsoft Power BI** – Data visualization and dashboard design  
- **Power Query Editor** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – Custom KPIs and measures  
- **Excel / CSV Dataset** – Source data for energy usage  
- **Conditional Formatting** – Highlighting abnormal or high consumption patterns  

---

## 📁 Dataset Description
| Column Name | Description |
|--------------|-------------|
| **Date** | The date or month of data collection |
| **Location / Department** | The physical area or business unit consuming energy |
| **Gas Consumption (m³)** | Total gas usage for the period |
| **Electricity Consumption (kWh)** | Total electrical energy usage |
| **Water Consumption (L)** | Volume of water used |
| **Gas Cost** | Expense associated with gas usage |
| **Electricity Cost** | Expense associated with electricity |
| **Water Cost** | Expense associated with water |
| **Total Energy Cost** | Combined energy expense (gas + electricity + water) |

---

## 📈 Dashboard Visualizations
### 1. **KPI Cards**
Show key metrics at a glance:
- Total Gas, Electricity, and Water Consumption  
- Total Energy Cost  
- Average Monthly Usage  
- Highest Consuming Month / Department  

---

### 2. **Trend Line Chart – Monthly Consumption**
Displays the **monthly trends** for Gas, Electricity, and Water consumption.  
Helps detect seasonal peaks and identify months with unusual consumption levels.

---

### 3. **Bar Chart – Energy Usage by Department or Location**
Compares **energy consumption across different departments or sites**.  
Useful for identifying **energy-efficient** and **high-usage** areas.

---

### 4. **Pie Chart / Donut Chart – Cost Distribution by Utility Type**
Shows how total energy costs are divided among:
- Gas  
- Electricity  
- Water  

Provides a quick overview of which energy source contributes most to total expenses.

---

### 5. **Waterfall Chart – Monthly Cost Variation**
Visualizes the increase or decrease in total energy cost over time, highlighting the impact of consumption changes or rate fluctuations.

---

### 6. **Interactive Filters (Slicers)**
Users can explore data dynamically based on:
- **Year / Month**  
- **Department / Location**  
- **Utility Type (Gas, Electricity, Water)**  

---

## 🧠 Key Insights
- Identified **peak energy consumption months**, aligning with seasonal demands.  
- **Electricity** accounted for the **largest share** of total cost.  
- Certain departments showed **consistent high usage**, suggesting potential inefficiencies.  
- **Gas and water consumption** remained more stable across the year compared to electricity.  

---

## 📊 KPIs and DAX Measures
| KPI | Formula | Description |
|------|----------|-------------|
| **Total Gas Consumption** | `SUM(Gas Consumption)` | Total gas used |
| **Total Electricity Consumption** | `SUM(Electricity Consumption)` | Total electricity used |
| **Total Water Consumption** | `SUM(Water Consumption)` | Total water used |
| **Total Energy Cost** | `SUM(Gas Cost + Electricity Cost + Water Cost)` | Combined cost |
| **Average Monthly Consumption** | `AVERAGE(Gas + Electricity + Water)` | Monthly average usage |
| **Cost per Unit** | `DIVIDE(Total Energy Cost, Total Units Consumed)` | Unit efficiency metric |

---

## 🚀 How to Use the Dashboard
1. Open the Power BI file (`Energy_Consumption_Analysis.pbix`) in **Power BI Desktop**.  
2. Load or refresh the dataset if required.  
3. Use the slicers to filter by year, location, or energy type.  
4. Analyze consumption patterns, costs, and efficiency metrics interactively.  
5. Export reports or screenshots for presentations or sustainability reports.

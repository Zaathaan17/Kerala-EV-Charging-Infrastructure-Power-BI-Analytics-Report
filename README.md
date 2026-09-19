# ⚡ Kerala EV Charging Infrastructure Analytics Dashboard

An interactive **Power BI data analytics project** developed to analyze Kerala's Electric Vehicle (EV) charging infrastructure across all **14 districts**.

The dashboard provides a comprehensive view of Kerala's EV charging ecosystem by examining **charging station distribution, charging capacity, charger technology, network growth, charging demand, energy consumption, utilization patterns, and district-level performance**.

The project transforms EV charging infrastructure data into an interactive analytical dashboard using **Power BI, Power Query, DAX, Excel, and data modeling techniques**.

---

# 📊 Dashboard Overview

The dashboard is organized into **seven analytical pages**, beginning with a navigation and introduction page and progressing through state-level analysis, district-level analysis, charging network analysis, utilization and demand, strategic insights, and finally an overall conclusion.

---

## 🏠 Page 1: Dashboard Navigation

![Dashboard Navigation](Screenshot%202026-09-10%20230908.png)

The first page acts as the **main landing and navigation page** for the entire dashboard. It introduces the project through the theme **"Driving a Cleaner Kerala"**, representing the focus on understanding Kerala's developing EV charging ecosystem.

The page provides navigation to the major analytical sections of the dashboard: **State Overview, District Analysis, Charging Network, Utilization & Demand, Strategic Insights, and Conclusion**. This creates a structured analytical flow, allowing users to move from a broad overview of Kerala's EV infrastructure toward detailed infrastructure, utilization, demand, and strategic analysis.

---

## 🌴 Page 2: State Overview

![State Overview](Screenshot%202026-09-09%20185732.png)

The **State Overview** page provides a consolidated view of Kerala's EV charging infrastructure across all 14 districts. It presents the major network-level KPIs, including **2,000 charging stations, 7,219 charging points, 48,948 estimated daily charging sessions, 2.14M kWh estimated daily energy consumption, 64.17% average network utilization, and 43.94 kW average charging power**.

The page also examines the distribution of charging stations by district, station status, and site type. Interactive filters such as **District, Operator, Opening Year, Area Type, and Station Status** allow users to dynamically explore the network and understand how different characteristics affect the overall charging infrastructure.

---

## 📍 Page 3: District Analysis

![District Analysis](Screenshot%202026-09-09%20185800.png)

The **District Analysis** page provides a detailed comparison of Kerala's **14 districts** based on charging infrastructure and network performance. It examines **total charging stations, charging ports, daily charging sessions, average utilization, and daily energy consumption** to understand how the EV charging ecosystem varies geographically.

The page uses multiple visualizations to compare district performance, including charging-port distribution, station counts, average utilization, and daily energy consumption. Interactive district selection allows users to focus on individual districts and investigate their infrastructure and usage patterns in greater detail.

---

## 🔌 Page 4: Charging Network

![Charging Network](Screenshot%202026-09-09%20185826.png)

The **Charging Network** page focuses on the technical composition and development of Kerala's EV charging infrastructure. It analyzes the distribution of **AC and DC charging points, charger types, connector technologies, charging capacity, and maximum charging power** across the network.

The dashboard examines technologies such as **AC 7.4kW, AC Type 2, DC Fast CCS2, DC Fast CHAdeMO, and DC Ultra Fast CCS2**. It also compares charger technology mixes across districts and analyzes charging-point growth based on station opening year, providing a clearer picture of how the charging network has developed over time.

---

## 📈 Page 5: Utilization & Demand

![Utilization & Demand](Screenshot%202026-09-09%20185858.png)

The **Utilization & Demand** page shifts the focus from infrastructure availability to how actively the charging network is being used. It highlights **24.47 average daily sessions per station, 1,069 kWh average daily energy consumption, 64.17% average network utilization, and approximately 49K total daily charging sessions**.

The page also identifies high-demand charging stations by comparing daily sessions, utilization, and energy consumption. Additional analysis compares utilization across **Rural, Semi-Urban, Suburban, and Urban** areas and examines utilization trends according to the opening year of charging stations.

---

## 🎯 Page 6: Strategic Insights

![Strategic Insights](Screenshot%202026-09-09%20185919.png)

The **Strategic Insights** page brings the major infrastructure and utilization indicators together into a consolidated district-level comparison. It compares **total stations, charging points, daily charging sessions, average utilization, and daily energy consumption** across Kerala's districts.

This page provides a broader analytical perspective by allowing users to compare districts across multiple dimensions rather than relying on a single indicator. It highlights differences in infrastructure availability, charging demand, utilization, and energy consumption that can be considered when evaluating future EV charging infrastructure development.

---

## 📝 Page 7: Conclusion & Overall Summary

![Conclusion & Overall Summary](Screenshot%202026-09-09%20190005.png)

The **Conclusion & Overall Summary** page brings together the major findings from the entire Kerala EV charging infrastructure analysis. It connects the insights from infrastructure distribution, district-level performance, charger technology, network utilization, charging demand, and energy consumption into a final overview of the analyzed ecosystem.

With **2,000 charging stations, 7,219 charging points, approximately 48,948 daily charging sessions, 64.17% average network utilization, and around 2.14 million kWh of estimated daily energy consumption**, the dashboard provides a comprehensive analytical view of Kerala's charging infrastructure.

The conclusion also highlights the differences between districts, charging technologies, area types, and utilization levels. Overall, the project demonstrates how **Power BI, Power Query, DAX, data modeling, and interactive visualization** can transform EV infrastructure data into a structured analytical story and provide a foundation for understanding charging-network development and future infrastructure planning.

---

# 📌 Key Project Metrics

The analyzed dataset provides the following major network-level indicators:

| Metric | Value |
|---|---:|
| Districts Covered | 14 |
| Total Charging Stations | 2,000 |
| Total Charging Points | 7,219 |
| Estimated Daily Charging Sessions | 48,948 |
| Average Network Utilization | 64.17% |
| Estimated Daily Energy | 2.14M kWh |
| Average Charging Power | 43.94 kW |
| Maximum Charging Power | 240 kW |

---

# 🔍 Key Analytical Areas

The dashboard analyzes the EV charging ecosystem from several different perspectives.

### 🏢 Infrastructure Distribution

Analysis of the number of charging stations and charging points available across Kerala's districts. This provides an understanding of how charging infrastructure is geographically distributed across the state.

### ⚡ Charging Capacity

Comparison of charging-point availability and AC/DC infrastructure across different districts and locations. This helps understand the charging capacity available within different parts of the network.

### 🔌 Charger Technology

Analysis of charger categories and connector technologies, including different AC and DC charging systems. The dashboard examines the technology mix and how charger types are distributed across districts.

### 📈 Network Growth

Analysis of charging infrastructure according to station opening year to understand how the network has developed over time and how charging capacity has expanded.

### 🚗 Charging Demand

Analysis of estimated daily charging sessions and identification of stations with higher charging activity. This provides an indication of where charging demand is concentrated within the network.

### 🔋 Energy Consumption

Comparison of estimated daily energy consumption across districts and charging stations to understand the energy requirements associated with charging activity.

### 📊 Network Utilization

Measurement and comparison of average utilization across districts and different area types. This provides an indication of how actively the available charging infrastructure is being used.

### 🗺️ Area-wise Analysis

Comparison of charging utilization across **Rural, Semi-Urban, Suburban, and Urban** locations to understand differences in usage patterns based on area classification.

### 🏪 Site-Type Analysis

Analysis of charging station deployment across different locations such as **highway hubs, fuel stations, shopping malls, KSEB facilities, parking areas, automobile dealers, hotels, residential areas, and hospitals**.

### 🏷️ Station Status

Analysis of charging station operational status, including categories such as **operational, temporarily offline, and maintenance**.

---

# 🧮 DAX & Analytical Measures

The dashboard uses **DAX measures** to dynamically calculate and display important performance indicators.

Examples include:

* Total Charging Stations
* Total Charging Points
* Total Daily Sessions
* Total Daily Energy
* Average Network Utilization
* Average Charging Power
* Average Daily Sessions per Station
* District-level Utilization
* District-level Energy Consumption
* Charging-point Distribution
* Station-level Demand Indicators

These measures allow the dashboard's KPIs and visualizations to respond dynamically to slicers, filters, and user selections.

---

# 🧹 Data Preparation & Transformation

The dataset was prepared and transformed using **Power Query** before being used for dashboard development.

The data preparation process includes:

* Data type transformation
* Data cleaning
* Handling missing or inconsistent values
* Standardizing categorical fields
* Preparing district and location dimensions
* Structuring charger-type information
* Preparing fields for analytical calculations
* Creating a data model suitable for Power BI visualization

The transformed data was then connected with DAX measures and Power BI visuals to create the final interactive dashboard.

---

# 🛠️ Tools & Technologies

### Microsoft Power BI

Used to build the interactive dashboard, data model, KPIs, slicers, charts, tables, navigation system, and analytical pages.

### Power Query

Used for data cleaning, transformation, restructuring, standardization, and preparation of the source data.

### DAX

Used to create calculated measures and dynamic analytical metrics for KPIs, utilization, demand, energy consumption, and district-level comparisons.

### Microsoft Excel

Used for dataset preparation, initial data handling, and organizing the source information before analysis.

### Data Visualization

The project uses multiple visualization formats, including:

* KPI Cards
* Bar Charts
* Donut Charts
* Line Charts
* Treemaps
* Tables
* Gauge Charts
* Slicers
* Conditional Formatting
* Interactive Navigation

---

# 🎯 Project Objective

The primary objective of this project is to create an interactive analytical view of Kerala's EV charging ecosystem and demonstrate how data analytics can be used to understand infrastructure and usage patterns.

The dashboard combines **infrastructure data, technology information, demand indicators, energy consumption, utilization metrics, and geographic distribution** into a single interactive environment.

The project allows users to move from a broad state-level perspective to detailed district and station-level analysis, making it possible to investigate how charging infrastructure is distributed and how usage varies throughout Kerala.

---

# 💡 Analytical Value

The dashboard demonstrates how a large collection of EV charging infrastructure records can be transformed into a structured analytical story.

Instead of simply displaying the number of charging stations, the project examines the relationship between **infrastructure availability, charging capacity, utilization, demand, energy consumption, technology type, location, and network growth**.

This provides a more complete understanding of the charging ecosystem and demonstrates the application of **business intelligence, data modeling, and interactive visualization** to a real-world sustainability and transportation use case.

---

# 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Kerala-EV-Charging-Dashboard.git

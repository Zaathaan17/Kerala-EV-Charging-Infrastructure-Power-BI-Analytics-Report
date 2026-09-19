# ⚡ Kerala EV Charging Infrastructure Analytics Dashboard

An interactive **Power BI data analytics project** developed to analyze Kerala's Electric Vehicle (EV) charging infrastructure across all 14 districts.

The dashboard provides a comprehensive view of the state's charging ecosystem by examining **charging station distribution, charging capacity, charger technology, network growth, charging demand, energy consumption, utilization patterns, and district-level performance**.

The project is designed as an end-to-end data visualization and analytics solution, where raw EV charging infrastructure data is transformed using **Power Query and DAX** and presented through an interactive multi-page Power BI dashboard.

---

# 📊 Dashboard Overview

The dashboard is organized into six main pages. Each page focuses on a different layer of the EV charging ecosystem, beginning with the overall dashboard navigation and gradually moving into state-level, district-level, network, utilization, and strategic analysis.

---

## 🏠 Page 1: Dashboard Navigation

![Dashboard Navigation](Screenshot%202026-09-09%20185732.png)

The first page serves as the **landing page and navigation interface** for the entire dashboard. The theme, *"Driving a Cleaner Kerala"*, represents the project's focus on understanding the development of EV charging infrastructure and its role in supporting a cleaner transportation ecosystem.

The page provides an overview of the analytical structure of the project and allows users to navigate between the different sections of the dashboard. The main analytical areas include **State Overview, District Analysis, Charging Network, Utilization & Demand, and Strategic Insights**.

The navigation structure is designed to allow users to move from a broad understanding of Kerala's EV infrastructure into progressively deeper levels of analysis. This creates a logical flow from **overall infrastructure → district distribution → charging technology → utilization and demand → strategic comparison**.

---

# 🌴 Page 2: State Overview

![State Overview](Screenshot%202026-09-09%20185800.png)

The **State Overview** page provides a consolidated view of Kerala's EV charging infrastructure. It acts as the starting point for understanding the overall scale and current structure of the charging network before examining individual districts.

The top KPI section summarizes the major network indicators, including **2,000 total charging stations, 7,219 charging points, 48,948 estimated daily charging sessions, 2.14 million kWh of estimated daily energy consumption, 64.17% average network utilization, and 43.94 kW average power**.

The page also examines how charging stations are distributed across districts and different site types. The station-status visualization provides an overview of operational and non-operational infrastructure, while the site-type analysis highlights the locations where charging stations are being deployed, such as highway hubs, fuel stations, shopping malls, KSEB facilities, parking facilities, automobile dealers, hotels, residential areas, and hospitals.

Interactive filters for **District, Operator, Opening Year, Area Type, and Station Status** allow users to dynamically explore the state-level dataset and understand how different selections affect the dashboard's analysis.

---

# 📍 Page 3: District Analysis

![District Analysis](Screenshot%202026-09-09%20185826.png)

The **District Analysis** page moves from the state-level view to a more detailed comparison of Kerala's **14 districts**.

The page compares districts using several important indicators, including **total charging stations, total charging ports, daily charging sessions, average utilization, and daily charging energy**. This makes it possible to understand not only where charging infrastructure is located, but also how intensively that infrastructure is being used.

The district comparison shows that **Ernakulam has 236 charging stations and 850 charging points**, while Thiruvananthapuram and Thrissur also have relatively large charging networks. At the same time, districts with fewer stations can be examined to understand differences in charging capacity and utilization.

The page contains multiple visual perspectives. The **Average Utilization by District** chart compares network usage levels, while the **Charging Ports by District** chart highlights differences in charging capacity. Additional charts show station counts and daily energy consumption by district.

A district slicer allows users to select individual districts and investigate their infrastructure characteristics more closely. This makes the page useful for understanding regional differences within Kerala's EV charging ecosystem.

---

# 🔌 Page 4: Charging Network

![Charging Network](Screenshot%202026-09-09%20185858.png)

The **Charging Network** page focuses on the technical structure of Kerala's EV charging infrastructure. Instead of looking only at the number of stations, this page examines **what types of charging equipment make up the network**.

The KPI section provides an overview of the total charging points, AC and DC charging capacity, and maximum charging power. The dashboard contains approximately **7,219 charging points**, with both AC and DC charging technologies represented across the network.

The **Charger and Connector Breakdown** provides a detailed comparison of technologies such as **AC 7.4kW, AC Type 2, DC Fast CCS2, and DC Fast CHAdeMO**. This helps illustrate the different charging technologies available within the analyzed network.

The **Charger Technology Mix by District** visualization compares the technology composition between districts, showing how the charging infrastructure is distributed across different charger categories.

The **Charging Network Growth by Year** chart analyzes the number of charging points associated with different station opening years. This provides a historical perspective on how the charging network has developed over time.

A treemap showing **Total Charging Points by Charger Type** provides another way of understanding the relative contribution of each charger category to the overall network.

---

# 📈 Page 5: Utilization & Demand

![Utilization & Demand](Screenshot%202026-09-09%20185919.png)

The **Utilization & Demand** page shifts the analysis from infrastructure availability to **actual usage and charging demand**.

The KPI section highlights four important indicators: **24.47 average daily sessions per station, 1,069 kWh average daily energy, 64.17% average network utilization, and approximately 49K total daily sessions**.

The **Top Charging Stations by Daily Demand** table identifies stations with high estimated daily charging activity. It compares individual stations using metrics such as estimated daily sessions, average utilization percentage, and estimated daily energy consumption.

The **Overall Network Utilization** gauge provides a simplified view of the network-wide utilization level, while the **District Utilization by Area Type** table compares utilization across Rural, Semi-Urban, Suburban, and Urban locations.

The **Utilization Trend by Opening Year** visual examines how average utilization varies according to the year in which charging infrastructure was introduced. Together, these visuals provide a broader understanding of charging demand and how infrastructure usage differs by location and station characteristics.

---

# 🎯 Page 6: Strategic Insights

![Strategic Insights](Screenshot%202026-09-09%20190005.png)

The **Strategic Insights** page brings the major infrastructure and utilization metrics together into a consolidated district-level analysis.

The main table compares all 14 districts using five key indicators: **Total Stations, Total Charging Points, Total Daily Sessions, Average Utilization, and Total Daily Energy Consumption**.

This allows users to compare districts from multiple perspectives rather than relying on a single metric. For example, a district may have a large number of charging stations but a different utilization profile, while another district may have fewer stations but relatively strong charging activity.

The page is therefore designed to support **comparative analysis and infrastructure planning discussions**. It helps identify differences in charging capacity, demand, energy consumption, and utilization across Kerala and provides a final analytical view of the overall charging network.

Rather than focusing on a single "best" district, the page allows users to examine the different dimensions of network performance and understand where infrastructure characteristics and usage patterns differ.

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

The dashboard analyzes the EV charging ecosystem from several different perspectives:

### 🏢 Infrastructure Distribution
Analysis of the number of charging stations and charging points available across Kerala's districts.

### ⚡ Charging Capacity
Comparison of charging-point availability and AC/DC infrastructure across different locations.

### 🔌 Charger Technology
Analysis of charger categories and connector technologies, including AC and DC charging systems.

### 📈 Network Growth
Analysis of charging infrastructure according to station opening year to understand network development over time.

### 🚗 Charging Demand
Analysis of estimated daily charging sessions and identification of stations with higher charging activity.

### 🔋 Energy Consumption
Comparison of estimated daily energy consumption across districts and charging stations.

### 📊 Network Utilization
Measurement and comparison of average utilization across districts and different area types.

### 🗺️ Area-wise Analysis
Comparison of charging utilization across **Rural, Semi-Urban, Suburban, and Urban** locations.

### 🏪 Site-Type Analysis
Analysis of charging station deployment across locations such as highway hubs, fuel stations, shopping malls, KSEB facilities, parking areas, automobile dealers, hotels, residential areas, and hospitals.

### 🏷️ Station Status
Analysis of station operational status, including operational, temporarily offline, and maintenance categories.

---

# 🧮 DAX & Analytical Measures

The dashboard uses DAX measures to dynamically calculate and display important performance indicators.

Examples include:

* Total Charging Stations
* Total Charging Points
* Total Daily Sessions
* Total Daily Energy
* Average Network Utilization
* Average Charging Power
* Average Daily Sessions per Station
* District-level utilization
* District-level energy consumption
* Charging-point distribution
* Station-level demand indicators

These measures allow the dashboard visuals and KPIs to respond dynamically to slicers and user selections.

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
* Creating a model suitable for Power BI visualization

The transformed data was then connected to DAX measures and Power BI visuals to create the final interactive dashboard.

---

# 🛠️ Tools & Technologies

### Microsoft Power BI
Used to build the interactive dashboard, data model, KPIs, slicers, charts, tables, and analytical pages.

### Power Query
Used for data cleaning, transformation, restructuring, and preparation.

### DAX
Used to create calculated measures and dynamic analytical metrics.

### Microsoft Excel
Used for dataset preparation and initial data handling.

### Data Visualization
The project uses multiple visual formats including:

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

The dashboard demonstrates how a large collection of charging infrastructure records can be transformed into a structured analytical story.

Instead of simply displaying the number of charging stations, the project examines the relationship between **infrastructure availability, charging capacity, utilization, demand, energy consumption, technology type, location, and network growth**.

This provides a more complete understanding of the charging ecosystem and demonstrates the application of business intelligence techniques to a real-world sustainability and transportation use case.

---

# 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Kerala-EV-Charging-Dashboard.git

# Transportation Dashboard

<p align="justify">
This Excel dashboard presents a clear and structured view of commuter activity across the network. It is designed to assist users analyze route performance, understand day and hour patterns, and evaluate bus utilization using concise KPIs and well-organized visuals.
</p>

## Key Features

- **Data Preparation and Modeling**
  - Data has been loaded from multiple CSV files using <b>Power Query</b> for cleaning, merging, and transformation.
  - A <b>Power Pivot</b> model has been created signifying relationships, measures, and KPIs that drive all visuals.
  - Though the layout is static, calculations have been made dynamic through the data model.
- **Core Visuals**
  - **Top-Level KPIs** showing Total Commuters, Average Commuters per Trip, Average Age, Total Buses, and Busiest/Least Busy Routes.
  - **Commuters by Hour** to identify peak and off-peak periods.
  - **Commuter Distribution by Day** to compare weekly footfall.
  - **Yearly Commuter Trend** to observe changes across years.
  - **Commuter Type Breakdown** to understand segment composition.
  - **Bus Utilization** indicators for well-utilized, under-utilized, and over-utilized groups.

## Dashboard Insights

- **Network Snapshot:** The system recorded a total of **6,587 commuters** supported by **40 buses**, and the average load per trip was **33 commuters**, which indicates moderate occupancy levels and steady daily demand.
- **Peak and Off-Peak Windows:** Commuter volume was highest between **10 AM and 3 PM** with **2,243 commuters**, while the evening period from **8 PM to 12 AM** saw **1,653 commuters**. Early morning and late afternoon ranges remained comparatively lower at around **1,345 to 1,346 commuters**.
- **Day-of-Week Distribution:** **Sunday (1,185)** and **Monday (1,085)** recorded the highest footfall, while **Friday (762)** and **Saturday (796)** saw the lowest. This pattern highlights stronger demand at the start of the week and lighter usage as the weekend approaches.
- **Day vs Night Mix:** The dashboard shows that **63.25%** of commuters traveled during the day and **36.75%** traveled at night, which confirms that daytime operations support a larger portion of overall movement.
- **Route Performance:** The **East–West Express** was identified as the busiest route, while the **South Line** had the lowest commuter count. This indicates that the East–West corridor supports the greatest demand, and the South Line may benefit from route or schedule adjustments.
- **Bus Utilization:** Utilization levels varied across the fleet. **34 buses** were well‑utilized (**41%**), **29 buses** were under‑utilized (**35%**), and **20 buses** were over‑utilized (**24%**). This distribution suggests that rebalancing resources could improve efficiency.
- **Commuter Types:** The largest commuter groups included **Professionals** and **Self‑Employed individuals**, each with more than **1,300 commuters**, while **Students (479)** and **Retired individuals (589)** formed smaller segments. This indicates that most travel demand is driven by working-age individuals.
- **Year-over-Year Trend:** Total commuters declined significantly from **5,654 in 2023** to **933 in 2024**, which reflects an **83.50% decrease**. This sharp drop signals a need to investigate potential causes such as route changes, external factors, shifts in commuter behavior, or imcomplete data.

## Previews

#### 1. Data Model

![DM](https://github.com/TSgthb/Excel_Projects/blob/main/Transportation%20Dashboard/Images/Data%20Model.png)

#### 2. Dashboard

![Dashboard](https://github.com/TSgthb/Excel_Projects/blob/main/Transportation%20Dashboard/Images/Dashboard.png)

#### 1. Calculations

![Dashboard](https://github.com/TSgthb/Excel_Projects/blob/main/Transportation%20Dashboard/Images/Dashboard_Calculations.png)


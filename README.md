![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Farguewithdata-hub%2FGWL-Energy-Optimization&countColor=%23263759)
# Energy Optimization Models (MILP)
**Author:** George Ayensu, PE (Professional Electrical Engineer)

This repository contains Mixed-Integer Linear Programming (MILP) models built in Python (Pyomo) to demonstrate algorithmic energy management for inflexible loads. 

## Project 1: Water Utility Optimization (Week 1)
*   **File:** `George_Ayensu_Week1_Data_Analysis_PhD_Working_Code.ipynb`
*   **Description:** Optimizes the dispatch of high-voltage (3.3 kV) fixed-speed pumps and storage wells at a municipal water utility to minimize Time-of-Use electricity costs. Proves a 6.3-year payback and $9.2M Net Present Value.

## Project 2: Data Center Thermal Optimization (Week 2)
*   **File:** `George_Ayensu_Week2_DataCenter_Optimization.ipynb`
*   **Description:** Demonstrates the mathematical transferability of the Week 1 model to Data Centers. The model optimizes chiller dispatch and Thermal Energy Storage (TES) to meet an inflexible server cooling load, successfully avoiding inefficient chillers during peak tariff hours.

---

## Data Source & Assumptions
The empirical parameters used in these models (capacity, energy intensity, storage limits) were derived from real-time SCADA readings, nameplate data, and operational audits conducted at the Ghana Water Limited (GWL) Weija Head Works. 

*   **Old Plant:** 3 × 500 kW motors (3.3 kV), capacity 1000 m³/hr, calculated energy intensity 0.533 kWh/m³.
*   **New Plant:** 3 × 1000 kW motors (3.3 kV), capacity 2250 m³/hr, calculated energy intensity 0.398 kWh/m³.
*   **Storage:** 5 clear wells, total capacity ~22,730 m³.

*Note: Due to corporate confidentiality policies, raw SCADA data is not published. The code utilizes the mathematically derived parameters from the plant data to simulate the optimization scenarios.*

# **Electric Vehicle Data Analysis**

## **Overview**
This project analyzes electric vehicle (EV) adoption trends using a dataset containing vehicle registration information across the United States. The dataset includes vehicle characteristics such as make, model, model year, electric range, CAFV eligibility, and geographic distribution.

The analysis focuses on identifying EV adoption trends, manufacturer dominance, vehicle model popularity, and eligibility for Clean Alternative Fuel Vehicle (CAFV) incentives. The dashboard was built using Tableau and provides an interactive view of EV trends from **2011 to the 2025.**

#### **Geographic Bias**
The dataset is heavily concentrated in **Washington State.**

This indicates that the dataset primarily reflects EV adoption patterns within Washington rather than nationwide trends.

## **Objective**
- Analyze the growth of electric vehicles over time.
- Compare the adoption of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).
- Identify the top EV manufacturers and models dominating the market.
- Evaluate CAFV eligibility distribution, which indicates eligibility for clean energy incentives.
- Explore the geographic distribution of EV registrations.
- Provide insights into electric range trends and market dominance among EV manufacturers.

## **Dataset**
The dataset contains detailed electric vehicle registration data with fields such as:
- VIN (Vehicle Identification Number)
- County, City, State, Postal Code
- Model Year
- Make and Model
- Electric Vehicle Type (BEV / PHEV)
- CAFV Eligibility
- Electric Range

[Dataset link](https://www.kaggle.com/datasets/nuhmanpk/electric-vehicle-population-data-2025?resource=download)

## **Dashboard**
![](https://github.com/aayushmanmukherjee/EV_Analysis_Tableau/blob/main/Electric%20Vehicle%20Data%20Analysis.png)

[Dashboard link](https://public.tableau.com/views/EV_Data_Analysis_Dashboard/ElectricVehicleDataAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### **Key Performance Indicators (KPI)**
- **Total Vehicles**
  - 247,285 vehicles
  Observation:
    - The dataset indicates a large EV adoption base, with nearly a quarter million registered EVs.

- **Average Electric Range**
  - 44.62 miles
  Observation:
    - The average electric range appears relatively low because the dataset includes both BEVs and PHEVs, and PHEVs typically have much shorter electric ranges.

- **Total Battery Electric Vehicles (BEV)**
  - 197,093 vehicles (79.7%)
  Observation:
    - BEVs dominate the dataset, accounting for nearly 80% of all EVs.
    - This suggests a strong shift toward fully electric vehicles instead of hybrid options.

- **Total Plug-in Hybrid Electric Vehicles (PHEV)**
  - 50,192 vehicles (20.3%)
  Observation:
    - PHEVs represent a smaller portion of the EV market.
    - The trend indicates that consumers increasingly prefer fully electric vehicles rather than hybrids.

### **Dashboard Charts Insights**
- **Total Vehicles by Model Year**
  The line chart shows EV registrations from 2011 to 2025.
  
  Observations:
    - EV adoption remained relatively low between 2011 and 2017.
    - A steady increase begins around 2018, coinciding with the expansion of EV model availability.
    - A significant surge occurs between 2021 and 2023, peaking at approximately 59K vehicles in 2023.
    - A decline appears in 2025, due to incomplete or partial data for the current year rather than an actual market decline.

- **Total Vehicles by State**
  The map visualizes EV registrations by state.
  
  Observations:
    - Washington State dominates the dataset, with approximately 246,740 vehicles, indicating that the dataset is heavily centered on Washington.
    - The presence of EV registrations in multiple states suggests limited nationwide coverage, but the analysis is primarily representative of Washington’s EV market.

- **Top 10 Vehicles by Make**
  Bar chart showing EV registrations by manufacturer.
  
  Observations:
    - Tesla dominates the EV market, accounting for approximately 50.83% of vehicles.
    - Tesla’s vehicle count (~104,960 vehicles) is significantly higher than any other manufacturer.
    - Chevrolet and Nissan follow but with much smaller shares.

- **Total Vehicles by CAFV Eligibility**
  Donut chart showing eligibility for Clean Alternative Fuel Vehicle incentives.
  
  Observations:
    - A large portion of vehicles fall under “Unknown eligibility”, likely because battery range data has not been fully researched or updated.
    - Approximately 30% of vehicles qualify for CAFV incentives, indicating significant adoption of vehicles that meet clean energy policy standards.
 
- **Total Vehicles by Model**
  Table showing most registered EV models.

## **Conclusion**
- The analysis highlights the rapid growth of electric vehicle adoption over the past decade, particularly after 2018. The market is strongly dominated by Battery Electric Vehicles, which represent nearly 80% of the total electric vehicles.
- Tesla has emerged as the undisputed leader in the EV market, with multiple Tesla models ranking among the most popular vehicles. Models such as the Tesla Model Y and Model 3 significantly drive EV adoption.
- Geographically, the dataset is largely centered on Washington State.
- Overall, the dashboard provides valuable insights into EV market growth, manufacturer dominance, and adoption trends, offering a data-driven perspective on the transition toward sustainable transportation.

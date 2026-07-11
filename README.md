1. Project Title
🚗 Road Accident Analytics Dashboard: Interactive Excel-Based Safety & Casualty Analysis

An interactive Microsoft Excel dashboard designed to analyze road accident data by casualty severity, vehicle type, road conditions, and time-based trends. The dashboard transforms raw accident records into meaningful insights using Pivot Tables, Pivot Charts, Slicers, and dynamic visualizations to support road safety analysis and data-driven decision-making.

2. Short Description

This dashboard is created to analyze and visualize road accident data across different factors such as accident severity, vehicle type, road type, lighting condition, and area type (urban/rural). It helps in identifying patterns and supporting data-driven decision-making for road safety initiatives.

3. Tech Stack

The dashboard was built using the following tools and technologies:

📊 Microsoft Excel – Primary platform used to develop the interactive dashboard.
📋 Pivot Tables – Used to summarize and aggregate accident data.
📈 Pivot Charts – Created dynamic visualizations linked to Pivot Tables.
🎚️ Slicers – Enabled interactive filtering by Year, Area Type, and Day of Week.
📊 Donut Charts – Visualized proportional comparisons such as Urban vs Rural and Day vs Night casualties.
📉 Line Charts – Compared Current Year (CY) and Previous Year (PY) casualty trends.
🌳 Treemap Charts – Displayed casualties by road surface condition.
📊 Bar Charts – Compared casualties across road types.
🎨 Conditional Formatting – Enhanced KPI visibility and data interpretation.
🚗 Shapes & Icons – Improved dashboard design using vehicle icons and custom KPI cards.
📁 File Format – .xlsx for dashboard development and .png for dashboard previews.

4. Data Source

Source: Simulated Road Accident Dataset (Microsoft Excel)

The dataset contains detailed road accident records used to analyze accident severity, casualty distribution, vehicle involvement, road conditions, and environmental factors.

Dataset includes:

📋 Original Dataset

The raw dataset contains the following fields:

Index
Accident_Severity
Accident Date
Latitude
Longitude
District
Area
Number_of_Casualties
Number_of_Vehicles
Vehicle_Type
Road_Type
Road_Surface_Conditions
Urban_or_Rural_Area
Weather_Conditions
Light_Conditions

Data Transformation (Power Query)

Power Query was used to clean, transform, and prepare the dataset for dashboard reporting. The following transformations were performed:

Removed unnecessary columns (Latitude, Longitude, District, Area, Weather Conditions, Number of Vehicles, etc.).
Renamed columns to improve readability.
Changed appropriate data types.
Created an Accident ID from the original Index column.
Extracted Year and Month from the Accident Date.
Renamed Accident Severity to Casualty Severity.
Renamed Number_of_Casualties to Casualty Count.
Renamed Vehicle_Type, Road_Type, Road_Surface_Conditions, Urban_or_Rural_Area, and Light_Conditions to user-friendly field names.

📊 Final Dataset Used in Dashboard

After transformation, the dashboard uses the following columns:

Column	Description

Accident ID	Unique identifier for each accident
Accident Date	Date of the accident
Year	Extracted year for yearly analysis
Month	Extracted month for monthly trend analysis
Casualty Severity	Severity category (Fatal, Serious, Slight)
Casualty Count	Number of casualties involved
Vehicle Type	Type of vehicle involved in the accident
Road Type	Classification of road where the accident occurred
Road Surface Condition	Road condition at the time of the accident
Urban/Rural Area	Area classification
Light Condition	Daylight or darkness condition

The dataset is structured using Excel Tables and analyzed through Pivot Tables to support dynamic reporting.

5. Features / Highlights
📌 Business Problem

Road accidents result in significant human and economic losses every year. Government agencies and transportation authorities require an efficient analytical solution to monitor accident trends, identify high-risk conditions, and improve road safety planning.

Key questions addressed include:

What is the total number of casualties?
Which vehicle types are involved in the most accidents?
How do casualties compare between the current and previous year?
Which road types have the highest accident rates?
Are accidents more common in urban or rural areas?
Do more accidents occur during daylight or darkness?
How do road surface conditions affect accident frequency?
🎯 Goal of the Dashboard

The dashboard is designed to provide an interactive reporting solution that enables users to:

Monitor overall casualty statistics.
Compare accident trends across multiple years.
Analyze casualties by vehicle type and severity.
Evaluate accident distribution across different road conditions.
Identify high-risk road environments.
Support road safety planning through interactive data exploration.

📊 Walkthrough of Key Visuals
Executive KPI Cards

The dashboard presents high-level accident statistics through interactive KPI cards.

KPIs Included:

Total Casualties
Fatal Casualties
Serious Casualties
Slight Casualties
Casualties by Cars

These KPIs provide a quick overview of accident severity and overall road safety performance.

Casualties by Vehicle Type

Displays casualty counts for different vehicle categories including:

Cars
Motorcycles
Buses
Trucks
Tractors
Others

Business Insights

Identifies vehicle categories with the highest casualty rates.
Supports targeted road safety initiatives.
CY vs PY Casualty Trend (Line Chart)

Compares monthly casualty figures between the Current Year (CY) and Previous Year (PY).

Business Insights

Measures yearly performance.
Identifies seasonal accident patterns.
Tracks improvements or increases in casualties over time.
Casualties by Road Type (Horizontal Bar Chart)

Compares accident casualties across different road types including:

Single Carriageway
Dual Carriageway
Roundabout
One-Way Street
Slip Road

Business Insights

Identifies the highest-risk road infrastructure.
Supports transportation planning and road improvements.
Casualties by Road Surface Condition (Treemap)

Displays accident distribution across road surface conditions.

Categories include:

Dry
Wet
Snow/Ice

Business Insights

Evaluates the impact of weather and road conditions on accidents.
Supports seasonal road maintenance planning.
Urban vs Rural Casualties (Donut Chart)

Compares accident casualties occurring in Urban and Rural areas.

Business Insights

Identifies accident concentration by area type.
Supports region-specific safety initiatives.
Light Condition Analysis (Donut Chart)

Analyzes accident distribution during:

Daylight
Darkness

Business Insights

Determines whether accidents are more frequent during the day or at night.
Supports improvements in road lighting and nighttime safety.
Interactive Filter Panel

The dashboard includes interactive slicers for:

Year
Weather Conditions
Wind Conditions

All Pivot Charts update dynamically based on slicer selections, enabling flexible and user-friendly analysis.

6.Screenshots

<img width="1288" height="715" alt="image" src="https://github.com/user-attachments/assets/3d43572e-753a-42b5-a3ca-0b61568d1a57" />


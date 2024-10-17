# Earthquake Data Visualization with Tableau

[View the dashboard here](https://public.tableau.com/app/profile/esther.adeyeni/viz/WORLDEARTHQUAKERECORDSDASHBOARD2001-2023/Dashboard1?publish=yes)

This project showcases data visualization techniques using Tableau to analyze and understand earthquake data. I focus on key aspects of the dataset such as earthquake magnitudes, the occurrence of tsunamis, geographic distribution, and the significance of earthquake events. Below are the instructions for replicating each visualization and creating an interactive dashboard.

## Dataset
The dataset used in this project is an 'Earthquakes' dataset in CSV format. It contains information about earthquakes worldwide, including:
- **Date and Time** of occurrence
- **Magnitude** of the earthquake
- **Latitude** and **Longitude** for geographic location
- **Country** of occurrence
- **Tsunami** indicator (whether or not the earthquake resulted in a tsunami)
- **Significance Level** of the earthquake

## Visualizations
The project includes the following visualizations:

### 1. Tsunami-Resulted Earthquakes (Pie Chart)
This pie chart displays the number of earthquakes that resulted in tsunamis versus those that did not.

- **Steps to create**:
  - Open a new worksheet.
  - Drag the **Tsunami** field to the Columns and Rows shelves.
  - Apply a **Quick Table Calculation** on the Rows field for "Percent of Total."
  - Change the chart type to **Pie** from the **Show Me** panel.
  - Drag **Tsunami** to **Color** to differentiate categories.
  - Drag **Tsunami** to **Label** to display category counts.
  - Add the title: "Number of Earthquakes Resulting in Tsunami."

### 2. Magnitude Distribution (Map Chart)
This map shows the worldwide distribution of earthquake magnitudes using color intensity.

- **Steps to create**:
  - Open a new worksheet.
  - Drag **Latitude** to Rows and **Longitude** to Columns.
  - Change the chart type to **Map** from the **Show Me** panel.
  - Drag **Magnitude** to **Color** to represent intensity.
  - Add the title: "Worldwide Earthquake Magnitude Distribution."

### 3. Earthquake Magnitude Fluctuation in Peru and Russia (Line Chart)
This line chart compares earthquake magnitude trends in Peru and Russia over time.

- **Steps to create**:
  - Open a new worksheet.
  - Drag **Date_Time** to Columns and **Magnitude** to Rows.
  - Filter by **Country** and select "Peru" and "Russia."
  - Drag **Country** to **Color** to differentiate between Peru and Russia.
  - Add the title: "Earthquake Magnitude Fluctuation in Peru and Russia."

### 4. Relationship between Magnitude and Significance (Scatter Plot)
This scatter plot displays the relationship between earthquake magnitude and significance level.

- **Steps to create**:
  - Open a new worksheet.
  - Drag **Magnitude** to Columns and **Significance** to Rows.
  - Change the chart type to **Scatter Plot** from the **Show Me** panel.
  - Add the title: "Relationship between Earthquake Magnitude and Significance Level."

### 5. Magnitude Distribution in 2022 (Histogram)
This histogram shows the distribution of earthquake magnitudes that occurred in the year 2022.

- **Steps to create**:
  - Open a new worksheet.
  - Filter **Date_Time** by the year "2022."
  - Drag **Magnitude** to Columns and Rows.
  - Change the chart type to **Histogram** from the **Show Me** panel.
  - Add the title: "Earthquake Magnitude Distribution in 2022."

## Dashboard Creation
The dashboard compiles all the visualizations into a single view for easy analysis.


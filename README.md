# climate-dataset
Climate Data Analysis - Power BI Visualization

Overview

This project analyzes climate data using Power BI. The dataset includes temperature, precipitation, humidity, wind speed, and other weather-related parameters recorded over time. The goal is to create insightful visualizations to identify trends and patterns in the climate data.

Dataset

File Name: climate data.xlsx
Sheet Name: Sheet1

Columns and Descriptions:

Year, Month, Day – Date of data recording

Temperature (general or average), Maximum Temperature, Minimum Temperature – Temperature values

Sea Level Pressure, Station Pressure – Atmospheric pressure readings

Humidity – Relative humidity percentage

Precipitation – Rainfall amount in mm/inches

Visibility – Distance visibility in km/miles

Wind Speed, Maximum Wind Speed, Wind Gust Speed – Wind-related metrics

Fog, Rain, Snow, Thunderstorm – Binary indicators for weather conditions

Trace of Precipitation – Small unmeasured precipitation traces

Power BI Visualization Guide

1. Load Data into Power BI

Open Power BI Desktop.

Click Home > Get Data > Excel and select climate data.xlsx.

Choose Sheet1 and click Load.

2. Data Cleaning (Power Query)

Replace missing values ("-") with null.

Ensure numerical fields (temperature, wind speed, etc.) are set as Decimal Number.

Convert date-related fields to Date type.

3. Visualizations

1. Temperature Trends (Line Chart)

X-Axis: Year, Month

Y-Axis: Maximum Temperature, Minimum Temperature, Average Temperature

Insight: Identify seasonal temperature changes.

2. Precipitation Over Time (Bar Chart)

X-Axis: Month

Y-Axis: Precipitation

Insight: Compare rainfall across months.

3. Wind Speed vs Visibility (Scatter Plot)

X-Axis: Wind Speed

Y-Axis: Visibility

Legend: Month

Insight: Examine wind impact on visibility.

4. Humidity Heatmap (Matrix Visualization)

Rows: Month

Values: Humidity

Conditional Formatting: Color scale for intensity.

5. Weather Conditions Breakdown (Pie Chart)

Values: Fog, Rain, Snow, Thunderstorm

Insight: Proportion of weather events.

4. Dashboard Customization

Apply filters for Year, Month selection.

Format charts with appropriate colors and labels.

Arrange visuals in an easy-to-read layout.

5. Publishing and Sharing

Click Publish in Power BI.

Upload to Power BI Service for sharing.

Conclusion

This Power BI dashboard helps analyze climate patterns over time. It provides insights into temperature fluctuations, precipitation trends, wind-visibility relationships, and overall weather conditions.

For further enhancements, additional geospatial data can be incorporated for map-based visualizations.


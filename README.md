# **Project**: Solar Power Generation Analysis & Prediction

## **Project Description**
This a repo of performing an analysis on two solar power plant generation and buiding a predictive machine leearning model to predict the power generation for the next 2 days.
This data has been gathered at two solar power plants in India over a 34 day period. It has two pairs of files - each pair has one power generation dataset and one sensor readings dataset. The power generation datasets are gathered at the inverter level - each inverter has multiple lines of solar panels attached to it. The sensor data is gathered at a plant level - single array of sensors optimally placed at the plant.

There are a few areas of concern at the solar power plant:

1- Can we predict the power generation for next couple of days? - this allows for better grid management.

2- Can we identify the need for panel cleaning/maintenance?

3- Can we identify faulty or suboptimally performing equipment?

## To get these areas of concer answered, the project has followed a systematic process for data analysis. The steps involved in this analysis project were:

1. **Importing and Exploring the Data** - Initially, the data from two solar plants were imported and examined. This step involved understanding the variables and their data types.

2. **Inspecting Power Generation Data** - We examined the correlation between different variables specifically for DC and AC power generated, daily yield, and total yield for both plants.

3. **Examining Weather Sensor Data** - The study of weather parameters such as ambient temperature, module temperature, and irradiation preceded. These parameters greatly affect the efficiency and performance of solar panels.

4. **Visualizing DC Power over Time** - One of the first visualizations involved plotting DC power over time for Plant 1's inverters. The objective was to identify any outliers or anomalies that could indicate issues with equipment.

5. **Exploring Inverters Performance** - Different visual plots for each inverter's DC Power generation over time allowed us to compare inverters' performances and identify potential anomalies. 

6. **Effect of Weather Conditions on Power Generation** - By merging the weather sensor data with the generation data, we could analyze the correlation between weather conditions and DC power/AC power values. This helped provided insights regarding optimal weather conditions for maximum power generation. 

7. **Predictive Modeling using Machine Learning** - Machine learning (Random Forest Model) was used to predict the DC Power using the available features from weather sensor data. It helped us understand how these features contribute to the effective power generation of a solar plant. The model achieved a high R-squared value and a low Mean Squared Error, indicating a good fit.

8. **Identifying the Need for Panel Cleaning/Maintenance and Faulty Equipment** - By looking at sudden drops and consistency in normalized power output, we tried to identify the need for panel cleaning/maintenance and whether any equipment was faulty or underperforming.

Based on this comprehensive analysis, valuable and actionable insights were uncovered with essential recommendations provided for maintaining solar panel efficiency and identifying early potential issues related to cleanliness and equipment performance. 

It was concluded that an effective solar power plant operation should include regular health monitoring of equipment, proactive cleanliness checks and maintenance, and making good use of predictive analytics to enhance operational efficiency and preemptively detect potential issues.

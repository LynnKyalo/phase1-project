# Project Overview
This project was conducted as part of a data science exercise to assist a fictional company in expanding into the aviation sector. The company seeks to identify low-risk aircraft for purchase by analyzing aviation accident data.
The project involved data cleaning, missing value treatment, data analysis, visualizations, and insights generation to support business decision-making.

# Business Problem
The company plans to diversify its portfolio by venturing into commercial and private aviation. However, it lacks expertise regarding the potential risks associated with different types of aircraft.
My role was to analyze historical aviation accident data and provide actionable recommendations on which aircraft models are the safest and most reliable for the company's new aviation division.

# Data Description
The dataset used for this project was sourced from the National Transportation Safety Board (NTSB) and contains aviation accident records from 1962 to 2023.
The data includes variables such as:Aircraft Make and Model,,Date of the Event,,Location,,Injury Severity,,Fatalities and Serious Injuries,,Weather Conditions and Event Descriptions

# Tools and Libraries Used
Python (Pandas, Matplotlib, Seaborn)
Tableau (for dashboard creation)
Jupyter Notebook (for development and analysis)

# Methodology
## 1. Data Cleaning
Dropped columns with more than 60% missing values to retain useful information.
Focused on essential columns like Latitude, Longitude, Make, Model, and Injury Severity.
Renamed columns to be consistent by removing dots and spaces and making all names lowercase.
Converted relevant date columns (event_date and publication_date) into datetime format for better time-based analysis.
Handled remaining missing values strategically depending on the column.

## 2. Data Analysis
Performed aggregation to calculate:
Total accidents per aircraft model and make
Fatal accident counts
Fatality rates (percentage of fatal accidents relative to total accidents)
Investigated patterns and trends such as:
Which aircraft types and makes had the highest number of accidents
How accident numbers have changed over time
Which models had consistently lower accident and fatality rates

## 3. Visualizations
Several visualizations were created to uncover insights, including:
Bar Charts showing injury severity counts
Horizontal Bar Charts for aircraft make vs. accident counts
Pie Charts representing proportions of accidents among top makes
Histograms for distribution of accidents among aircraft models
Boxplots comparing fatality rates across different makes
Line Chart showing accident trends across decades

## 4. Insights and Recommendations
Aircraft models like Cessna 172, Piper PA-28, and Beechcraft Bonanza appeared frequently in accident reports — indicating they should be investigated further for reliability history.
Some manufacturers exhibited lower fatality rates, making their aircraft more attractive for purchase.
The overall trend shows that aviation accidents have decreased significantly over time, especially after the 1990s, which is promising for entering the market today.
Recommended focusing on models with high accident counts but low fatality rates, as these incidents often resulted in minor injuries or no injuries at all.

# Dashboard Creation (Tableau)
After cleaning the data, it was saved as cleaned_aviation_data.csv.
The file was imported into Tableau.
A dashboard was created to:
Allow stakeholders to interactively explore accident counts by make and model.
Visualize injury severity breakdowns.
Examine accident trends over time.

# How to Run This Project
## 1. Python Analysis
Clone this repository.
Install dependencies: pip install pandas matplotlib seaborn
Open the Jupyter Notebook and run the provided code to reproduce the cleaning, analysis, and visualizations.

## 2. Tableau Dashboard
You can view the interactive dashboard here:  
🔗 [View Dashboard on Tableau Public](https://public.tableau.com/views/Aircraftaccidentanalysis_17459037525170/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### 📈 Dashboard Overview
This Tableau dashboard provides a visual summary of aviation accident trends and risk patterns, built using cleaned accident data from the National Transportation Safety Board (NTSB). The goal is to help stakeholders make informed decisions about which aircraft models or makes are safer for investment.

### 📌 Dashboard Sections
1.**Bar Chart – Accidents by Aircraft Model**
This chart presents the number of recorded accidents for each aircraft model, helping identify which models have the highest and lowest incident rates.
2.**Line Chart – Accident Trends Over the Years**
This visualization shows how the number of aviation accidents has changed annually, providing insights into whether aviation safety is improving or declining over time.
3.**Pie Chart – Distribution of Accident Severity**
This chart illustrates the proportions of different injury severities (e.g., fatal, serious, minor, none) across all incidents, offering a clear picture of how severe most accidents tend to be.


### 🎯 Purpose
The dashboard is designed to provide actionable insights to guide the company in selecting low-risk aircraft as part of its expansion into the aviation industry.


# Conclusion
This project successfully identified key insights from aviation accident data, empowering business decision-makers with actionable recommendations.
By identifying safer aircraft based on historical accident and fatality data, the company can make data-driven decisions to minimize risk as it enters the aviation sector.

#Introduction


The COVID-19 pandemic, which began in late 2019, has profoundly impacted global health, economies, and daily life. The unprecedented nature of this pandemic necessitates ongoing and comprehensive analysis to understand its trajectory, impact, and response effectiveness. This report provides a detailed analysis of COVID-19 data, focusing on key trends and patterns observed across various dimensions: country-wise, month-wise, region-wise, and population-wise.

#Methodology


PowerBI used for data cleaning, processing, and analysis. Measures are used for finding aggregate value of columns.

1.Data Sources

   This analysis is based on data sourced from
   https://www.kaggle.com/datasets/imdevskp/corona-virus-report

2.Data Import:

   o	The datasets were imported into Power BI using its get data options. Various formats such as CSV, Excel, and direct database connections use excel format for importing data.

#Data Transformation

1.	Data Cleaning:
   
  o	Removing Duplicates: Identified and removed duplicate entries to ensure data accuracy.

  o	Handling Missing Values: Addressed missing values through imputation or exclusion based on the extent of the missing data.

  o	Standardizing Formats: Ensured consistency in date formats, numerical data, and categorical variables.

2.	Data Shaping:
   
  o	Merging Datasets: Combined multiple data sources into a single dataset using Power BI’s merge queries functionality.

  o	Filtering Data: Applied filters to focus on relevant time periods, regions, and demographic groups.

  o	Creating Calculated Columns: Added new columns for derived metrics such as case growth rates and recovery ratios using DAX (Data Analysis Expressions).
  
#Data Modeling

1.	Schema Design:
   o	Defining Relationships: Established relationships between tables using Power BI’s data model feature to enable comprehensive analysis across different dimensions.

   o	Building Measures: Created measures and KPIs (Key Performance Indicators) to aggregate and analyze data, such as total cases, daily new cases, and recovery rates.

2.	Data Aggregation:
   o	Summarizing Data: Aggregated data at various levels (e.g., country, region, month) to facilitate detailed analysis.

#Data Visualization


1.	Creating Dashboards:
   
   o	Interactive Reports: Developed interactive dashboards using Power BI’s visualization tools, including bar charts, line graphs, and maps, to present trends and comparisons effectively.

   o	Geographical Maps: Used Power BI’s map visualizations to illustrate regional and country-wise data distribution.

2.	Design and Layout:
   
   o	User Experience: Designed intuitive and user-friendly report layouts to ensure that insights are easily accessible and comprehensible.

   o	Dynamic Filters: Implemented slicers and filters to allow users to interactively explore different data segments, such as by country, region, or time period.


#Key Insights

1. Country-wise Analysis:
   
    •	Overall Trends: Discuss the trends observed in different countries. Include graphs and tables to show infection rates, recovery rates, and death rates .Total active case is 6358K,Confirmed case is 16M and Total death Case is 654K.

    •	Top Affected Countries: Highlight countries with the highest number of cases reported in America-WHO Region and lowest number in Western Pacific region. 

2. Month-wise Analysis:
   
    •	Case Trends: Show how the number of cases has evolved month-by-month. Use Stacked area chart and Table to illustrate trends.

    •	Seasonal Effects: The  report from 22-1-2020 to 27-07-2020.July month shows highest active cases, death case more on April and Recovery case highest on April.

3. Region-wise Analysis:
   
    •	Regional Distribution:The American region have highest active cases and new active death case is 3887 and 3699 Recovered cases.

4. Population-wise Analysis:
   
     •	Infection Rates by Population Density: India has the highest population compared to other regions, and the rate of reported cases is moderate. Active cases highest in America,new cases reported more in Mexico and death case highest in America.

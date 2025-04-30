# Project-2

MIST 4610 21484 Group 9 Project 2
Team Members:

Gabriela Rivera @Gcr79540
Daniel Yi @dmy17582
Maggie Craig @Maggiecraig108
Rashi Modey @rm53961
John Carr @jac08171
Our Dataset and What it Contains:
The data set utilized here is the U.S. Chronic Disease Indicators data set that was retrieved from the Data.gov data repository of the U.S. government. This data set has 309,215 rows and 34 columns and captures each row of information on a distinct public health observation concerning chronic conditions of asthma, cancer, diabetes, etc. This data set is drawn from multiple data sources such as the Behavioral Risk Factor Surveillance System (BRFSS) and U.S. Cancer Statistics.

Each row contiains
Time and place information: YearStart, YearEnd, LocationAbbr, Location

Topic-related fields include: Topic and Question and their respective IDs

Measurement values: DataValue, DataValueType, DataValueUnit, and statistical limits like LowConfidenceLimit and HighConfidenceLimit

Demographic stratifications: Including StratificationCategory1 and Stratification1 (for instance, gender and

Geographic information: e.g., LocationID and Geolocation

Notes and metadata: such as DataSource, DataValueFootnote, and internal identifiers

Most of the columns are text (object type), number (int64 or float64), or a combination of both based on their information. For instance, LocationDesc and Topic are text fields and DataValue is a number field (float) with the primary statistical value. Other fields such as Response and StratificationCategory2 contain mostly null values and likely serve as placeholders for further data expansion. In general, this dataset offers a rich and precise picture of chronic disease trends in the United States over time, places, and groups of people and is thus appropriately suited to detect health disparities and guide public health policy.

Our Two Questions and their Relevance:
How do rates of invasive cancer incidence vary by state and gender in 2015?

This question is important because it highlights regional and gender disparities in cancer risk and helps target public health interventions. This is important as it assists policymakers in allocating resources for cancer screening and education programs more effectively.

Data Used: MAGGIE

Screenshot 2025-04-29 at 10 34 34 PM
How do rates of asthma mortality vary by race from the years of 2019-2022?

This question uncovers patterns of inequality linked to pollution, environmental conditions, substandard housing, and limited education. It displays data during the pandemic, disproportionately affecting minority groups. This is important as it enforces plans to support reallocation of resources and upgraded living conditons.

Data Used:DANIEL

Screenshot 2025-04-29 at 10 35 30 PM
Data Manipulation:
We did not need to manipulate any of our data sets in Excel due to the already organized nature of our files. Sorting and grouping were not necessary, as the data was well prepared. We simply filtered our data in Tableau based on the time period we needed the data from as well as other variables.

Analysis and Results:
The analysis of asthma mortality data from 2019 to 2022 reveals a concerning trend where black individuals experienced significantly higher rates of asthma-related deaths compared to all other groups. This disparity remained consistent over 4 years, indicating a systemic and persistent public health issue rather than an anomaly. Asthma is usually a manageable chronic condition when diagnosed early and treated effectively. Yet, for Black communities, mortality rates remain disproportionately high, which could be sign of more than just medical issues. These numbers suggest longstanding inequities in social determinants of health, with contributing factors such as structural barriers, environmental racism, economic stressors, or delayed diagnosis. With the pandemic particularly, these disparities may have been intensified. There must be targeted interventions that expand education and screening, improve air quality, and ensure equitable healthcare access.

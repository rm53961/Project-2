# MIST 4610 21484 Group 9 Project 2

**Team Members:**

1) Gabriela Rivera [@Gcr79540](https://github.com/Gcr79540/Group-Project-2/)
2) Daniel Yi [@dmy17582](https://github.com/dmy17582/Group-Project-2/)
3) Maggie Craig [@Maggiecraig108](https://github.com/Maggiecraig108)
4) Rashi Modey [@rm53961](https://github.com/rm53961/Project-2)
5) John Carr [@jac08171](https://github.com/jac08171/Group-Project-2/)

# Our Dataset and What it Contains:
The data set utilized here is the U.S. Chronic Disease Indicators data set that was retrieved from the Data.gov data repository of the U.S. government. This data set has 309,215 rows and 34 columns and captures each row of information on a distinct public health observation concerning chronic conditions of asthma, cancer, diabetes, etc. This data set is drawn from multiple data sources such as the Behavioral Risk Factor Surveillance System (BRFSS) and U.S. Cancer Statistics.

## Each row contiains

**Time and place information:** YearStart, YearEnd, LocationAbbr, Location

**Topic-related fields include:** Topic and Question and their respective IDs

**Measurement values:** DataValue, DataValueType, DataValueUnit, and statistical limits like LowConfidenceLimit and HighConfidenceLimit

**Demographic stratifications:** Including StratificationCategory1 and Stratification1 (for instance, gender and

**Geographic information:** e.g., LocationID and Geolocation

**Notes and metadata:** such as DataSource, DataValueFootnote, and internal identifiers



Most of the columns are text (object type), number (int64 or float64), or a combination of both based on their information. For instance, LocationDesc and Topic are text fields and DataValue is a number field (float) with the primary statistical value. Other fields such as Response and StratificationCategory2 contain mostly null values and likely serve as placeholders for further data expansion. In general, this dataset offers a rich and precise picture of chronic disease trends in the United States over time, places, and groups of people and is thus appropriately suited to detect health disparities and guide public health policy.




# Our Two Questions and their Relevance:

## How do rates of invasive cancer incidence vary by state and gender in 2015?

This question is important because it highlights regional and gender disparities in cancer risk and helps target public health interventions.
This is important as it assists policymakers in allocating resources for cancer screening and education programs more effectively.

### Data Used: 
We analyzed invasive cancer incidence rates across U.S. states in the year 2015, with a specific focus on gender, to better understand geographic and demographic disparities in cancer risk. Invasive cancer, which refers to cancers that have spread beyond the original tissue, is a major public health concern—and its incidence can be influenced by a variety of factors including access to screening, environmental exposures, and lifestyle behaviors. By comparing rates between males and females across all 50 states, we aimed to highlight patterns that may point to underlying inequities in prevention and early detection efforts. This analysis offers insight into how gender and geography intersect to shape health outcomes, and serves as a basis for more targeted cancer awareness, diagnostic access, and policy interventions aimed at reducing the burden of cancer across diverse populations.


<img width="669" alt="Screenshot 2025-04-29 at 10 34 34 PM" src="https://github.com/user-attachments/assets/a0778ac5-070b-41d4-b36e-42bd1cb4fb4b" />





## How do rates of asthma mortality vary by race from the years of 2019-2022?

This question may show correlation between patterns of inequality linked to pollution, environmental conditions, substandard housing, and limited education. It displays data during the pandemic, which may be disproportionately affecting minority groups. This is important as it enforces plans to support reallocation of resources and upgraded living conditons.

### Data Used:
We analyzed asthma mortality rates across racial groups in the United States during the years 2019 through 2022 to uncover disparities in health outcomes. Specifically, we examined how the death rate from asthma—a condition that is generally manageable with proper medical care—varied among different racial populations. By isolating mortality data by race over this four-year span, which notably includes the COVID-19 pandemic period, we aimed to identify systemic inequities in healthcare access, treatment efficacy, and environmental risk factors. This approach allowed us to assess not only the direct impact of asthma on different communities, but also the broader social determinants of health that contribute to disproportionate outcomes. Our findings provide a data-driven foundation for addressing racial disparities in chronic disease management and for guiding targeted public health interventions.


<img width="635" alt="Screenshot 2025-04-29 at 10 35 30 PM" src="https://github.com/user-attachments/assets/db5b578f-9764-460f-950c-be95bcdf7319" />



# Data Manipulation:

We did not need to manipulate any of our data sets in Excel due to the already organized nature of our files. Sorting and grouping were not necessary, as the data was well prepared. We simply filtered our data in Tableau based on the time period we needed the data from as well as other variables. 


# Analysis and Results: 

Given the results from the Cancer Incidence data set, from 2015 to 2022, this explains the findings of cancer related incidences (not mortality) cases across the United States. From the map we can find a higher average across states that are from the east (split from texas to the right) compared to the west (given montana as an outlier) from how much darker it is colored from the key maps. The data set also shows that males are more prone to these cases rather than females, supporting evidence of gender specific causes. However, there is still a drastic output of cases within these states from the east, showing leeway for different variables in play.

The analysis of asthma mortality data from 2019 to 2022 reveals a concerning trend where black individuals experienced significantly higher rates of asthma-related deaths compared to all other groups. This disparity remained consistent over 4 years, indicating a systemic and persistent public health issue rather than an anomaly. Asthma is usually a manageable chronic condition when diagnosed early and treated effectively. Yet, for Black communities, mortality rates remain disproportionately high, which could be sign of more than just medical issues. These numbers suggest longstanding inequities in social determinants of health, with contributing factors such as structural barriers, environmental racism, economic stressors, or delayed diagnosis. With the pandemic particularly, these disparities may have been intensified. There must be targeted interventions that expand education and screening, improve air quality, and ensure equitable healthcare access.

# Tableau Packaged Workbooks: 

<a href = "https://github.com/Gcr79540/Group-Project-2/blob/3bb6c6b0266ff2e0ab0b0742c9daa30adeb310ef/Cancer%20Incidence%20Question%201" >Question 1<a></u1>

<a href = "https://github.com/Gcr79540/Group-Project-2/blob/3a8dc79f36a768015212622a03f804960ebdbc00/MISTProject2_Question2.twbx" >Question 2</a></ul>

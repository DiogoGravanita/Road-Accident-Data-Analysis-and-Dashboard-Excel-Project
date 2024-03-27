# Road Accident Data Analysis and Dashboard Excel Project


## Introduction:

Road accidents are a significant concern worldwide, impacting lives and communities every day. Understanding the factors contributing to accidents and their consequences is essential for developing effective safety measures and policies. This project delves into comprehensive analysis of road accident data collected over several years, aiming to uncover key insights and trends that can inform decision-making and improve road safety strategies.

<br/><br/>

## Project Overview

### Data Source

The data used in this project originates from "Road Accident Data(Finished).xlsx". The dataset comprises comprehensive information on road accidents, including accident date, severity, location, weather conditions, vehicle types involved, and various other relevant factors. The accuracy and reliability of the data are essential for ensuring the validity of the analysis and insights derived from this project.

### Objectives

<br/><br/>


## Key Performance Indicators (KPIs)


1. Primary KPI: Total Casualties After the Accident
2. Primary KPIs: Percentage of Total by Accident Severity and Total Casualties by Type of Vehicle
3. Secondary KPIs:
   - Monthly Trend Comparison of Casualties for Current Year and Previous Year
   - Total Casualties by Road Type
   - Distribution of Total Casualties by Road Surface
   - Relation Between Casualties by Area/Location & by Day/Night


<br/><br/>

<br/><br/>

## Tools and Technologies:

 - Excel for Data cleaning, analysis and Dashboard Creation

<br/><br/>

## Data cleaning and preparation:
<br/><br/>



### Correction of Accident Severity Entries:

Some entries in the "Accident Severity" field were recorded as "Fetal" instead of "Fatal." These inaccuracies were corrected to maintain consistency and accuracy in the severity classification.



<br/><br/>



### Creation of Month Column:


To facilitate temporal analysis and trend identification, a new column representing the month of the accident was added to the dataset. This was achieved by extracting the month from the "Accident Date" field and merging the month abbreviations into the newly created column.

```excel
=TEXT(B2,"mmm")
```

<br/><br/>

### Creation of Year Column:

Similarly, a new column capturing the year of the accident was created using the "Accident Date" field to enable yearly trend analysis.

```excel
=TEXT(B2,"yyyy")
```

<br/><br/>

### Standardization of Junction Control Entries:

Inconsistencies were observed in the entries for "Junction Control," with variations such as "auto traffic sgl" and "auto traffic signal." These discrepancies were rectified by standardizing the entries to ensure uniformity and accuracy in the data.

<br/><br/>

### Duplicate Removal:

Duplicate entries within the dataset were identified and removed to eliminate redundancy and maintain data integrity.


<br/><br/>

## Data visualization:

### Pivot table creation:

1. Sheet Organization:

   
 - Two sheets were created to facilitate visualization development:
One for base visualizations and pivot tables.
One for the dashboard layout.


2. Pivot Tables Creation:


Initial pivot tables were meticulously crafted to summarize critical metrics:
 - Total casualties.
 - Distribution of casualties based on accident severity.

3. Calculation of Percentages:

Tables were created to calculate the percentages of casualties based on accident severity categories. These percentages were computed to provide additional insights and were intended for inclusion in the dashboard.


![image](https://github.com/DiogoGravanita/Road-Accident-Data-Analysis-and-Dashboard-Excel-Project/assets/163042130/bd485e61-b943-4323-9455-5abe8dde60be)


4. Timeline Slicer Creation:

A timeline slicer was incorporated to enable dynamic filtering of data based on the accident date range. This interactive feature enhances user engagement and facilitates data exploration on the dashboard.


5. Vehicle Type Analysis:

A pivot table was constructed to analyze the total number of casualties by vehicle types. Custom categories were created for all vehicle types using the "Create Calculated Item" feature in the PivotTable Analyze Tab.

Before:
<br/><br/>
![image](https://github.com/DiogoGravanita/Road-Accident-Data-Analysis-and-Dashboard-Excel-Project/assets/163042130/e5c3da83-d653-46bb-9634-171c60dbb025)

<br/><br/>

After:
<br/><br/>
![image](https://github.com/DiogoGravanita/Road-Accident-Data-Analysis-and-Dashboard-Excel-Project/assets/163042130/a4ee1f31-8fbf-442c-b8fa-2c1b581c768b)
<br/><br/>

6. Monthly Trend Analysis:

Two pivot tables were generated to visualize the number of casualties per month for each year. A chart depicting the monthly casualty trends was created to highlight seasonal variations and long-term patterns.

<br/><br/>
![image](https://github.com/DiogoGravanita/Road-Accident-Data-Analysis-and-Dashboard-Excel-Project/assets/163042130/c724fb2f-d78c-4391-a82a-35f4e21aeb38)

<br/><br/>
7. Road Characteristics Analysis:

Additional pivot tables were created to analyze the number of casualties based on road type, road surface conditions, and the classification of urban or rural areas, considering the time of day (daylight or dark).


<br/><br/>
### Summary of Dashboard Insights

1. Navigation Buttons:
   - Four intuitive buttons offer quick access to essential resources:
         - Contact button provides direct email contact.
         - Information button links to additional details about the dataset.
         - Dataset button provides access to the dataset itself.
         - Pivot Tables button navigates to the sheet containing all pivot tables for deeper analysis.
    

2. Casualties Overview Cards:
 - Four prominent card-like presentations offer summarized data on various casualty categories:
       - Total Casualties
       - Serious Casualties
       - Slight Casualties
       - Casualties by Car

   Each card displays the corresponding numerical count, dynamically linked to the underlying data tables and slicer selections. Donut charts within each card provide visual representations of the percentage distribution relative to all other cases.



3. Casualties by Vehicle Type Bar Chart:
An informative bar chart vividly illustrates the distribution of casualties across different vehicle types. Icons accompany each vehicle type for easy identification and understanding.


4. Casualties by Year Line Graph:
A dynamic line graph visually compares casualties over two years, providing insights into temporal trends and year-on-year variations.


5. Casualties by Road Type Bar Chart:
A clear and concise bar chart showcases casualties categorized by road types, facilitating a deeper understanding of road-related factors influencing accident outcomes.

6. Casualties by Road Surface TreeMap:
An interactive treemap offers a hierarchical view of casualties based on road surface conditions, allowing users to explore the distribution of casualties across different surface types.

7. Casualties by Location and Light Conditions Donut Charts:
Two insightful donut charts provide visual representations of casualties categorized by location and light conditions, offering insights into spatial and environmental factors contributing to accidents.

8. Filter Panel with Time Slicer:
A convenient filter panel featuring a timeline slicer enables users to dynamically adjust the time range for analyzing casualty data, enhancing interactivity and data exploration capabilities.


Together, these dashboard components empower users to explore, analyze, and glean actionable insights from the road accident data, facilitating informed decision-making and targeted interventions aimed at improving road safety outcomes.



<br/><br/>

<br/><br/>

<br/><br/>


## Dashboard image:
<br/><br/>

<br/><br/>

![image](https://github.com/DiogoGravanita/Road-Accident-Data-Analysis-and-Dashboard-Excel-Project/assets/163042130/e452d8ae-a157-4883-a966-e30184effc4d)




<br/><br/>



<br/><br/>
<br/><br/>
# Results/findings
<br/><br/>


## Project Statistics Summary


### Total Casualties After the Accident:
 - 417,883
<br/><br/>
### Percentage of Total by Accident Severity:
 - Fatal: 7,135
 - Serious: 59,312
 - Slight: 351,435

<br/><br/>
### Total Casualties by Type of Vehicle:
 - Car: 333,484
 - Van: 33,472
 - Bus: 12,798
 - Bike: 33,672
 - Farmer: 1,032
 - Others: 3,424

   <br/><br/>
### Monthly Trend Comparison of Casualties for Current Year and Previous Year:

Casualties exhibit a monthly increase throughout the year, peaking in December with a significant decrease of over 30,000 casualties. Notably, there were more casualties in 2021 than in 2022, except for February, indicating a positive trend towards reduced casualties, possibly attributed to advancements in technology enhancing safety measures.


<br/><br/>
### Total Casualties by Road Type:

Single Carriageway accounts for the highest number of casualties with 310,000, followed by Dual with 67,000, Roundabout with 26,000, and One Way Street with 7,000.

<br/><br/>
### Distribution of Total Casualties by Road Surface:

The majority of casualties occur on dry roads (280,000), followed by wet roads (115,000), and snow/icy roads (23,000).


<br/><br/>
### Relation Between Casualties by Area/Location & by Day/Night:

 - Urban locations witness a higher number of casualties (255,000) compared to rural areas (162,000).
 - Surprisingly, there are more casualties during daylight (300,000) than during nighttime (110,000). This trend may be attributed to higher traffic volume during the day, despite the potential for reduced visibility and increased risk of accidents at night.

<br/><br/>

## Conclusion:


In conclusion, the analysis of road accident data reveals critical insights into the factors influencing casualty outcomes and trends. The total casualties recorded stand at 417,883 spanning 2 years, with varying degrees of severity observed, including 7,135 fatalities, 59,312 serious injuries, and 351,435 slight injuries. Understanding these distributions is pivotal for devising targeted interventions and resource allocation.

Vehicle involvement analysis indicates cars as the primary contributor to casualties, followed by vans, bikes, buses, farmers, and other vehicle types. Tailored safety measures addressing the unique risks associated with each vehicle category are imperative to mitigate casualties effectively.

Monthly casualty trends display a consistent increase throughout the year, with a notable decrease observed in December. Furthermore, a positive trend of decreasing casualties in 2022 compared to 2021 suggests potential improvements in road safety, possibly attributed to technological advancements and safety measures.

Regarding road characteristics and conditions, single carriageways emerge as the most hazardous, emphasizing the need for enhanced safety measures. The prevalence of casualties on dry roads underscores the significance of maintaining road surfaces and addressing hazards, particularly during adverse weather conditions.

Urban areas experience a higher incidence of casualties compared to rural areas, emphasizing the importance of targeted safety initiatives in urban environments. Surprisingly, more casualties occur during daylight hours, highlighting the need to address factors contributing to daytime accidents despite lower traffic volumes at night.

In summary, the insights gleaned from this analysis underscore the holistic nature of road safety initiatives, encompassing vehicle safety, road infrastructure, weather conditions, and driver behavior. By leveraging these insights, stakeholders can develop evidence-based strategies to reduce road accidents and minimize casualties, thereby fostering safer road environments for all.

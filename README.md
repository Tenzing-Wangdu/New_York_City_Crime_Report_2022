# NYC Crime Reduction Report
- author: Tenzing Wangdu 
- date created: 12/04/2022

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were:
1. For data integration - Python and Excel
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages


### Project Planning

Motivation for project:

In the last year, NYC shooting incidents have increased by 13.4% in areas like Brooklyn, Queens, and Staten Island. Crime rate is growing exponentially in NYC every year and we want to provide a better understanding and awareness of crimes that take place across NYC. 

Our objective is to help NYC citizens to be aware of their surroundings and safe from being a potential crime victim. We also want to share the insight with NYPD, security companies where they can utilize the knowledge to actually protect the citizens from the crime.   


Description of the issues or opportunities the project will address:
* With the project result, we can analyze which area or neighborhoods of the different boroughs has a higher rate of different types of crime
* A clear understanding of crime in relation to demographic categories such as  age, gender, etc.  
* Assist the NYPD in focusing on regions that need greater law enforcement by highlighting the locations where crimes occur more frequently. 
* We will analyze complaints, shooting and arrest data of year to date.
* In conclusion, with our result, we can provide better solutions to tackle the increased crime rate in NYC. 


Project Business or Organization Value:

High-level Business Initiative:
Increase awareness about the crimes taking place in New York City.
Determine the areas in New York City with a higher crime rate and the type of crimes happening.

What’s the Business Value?
The project will give helpful insights on crime statistics that will help NYPD to make informed decisions regarding how to better manage their resources  to combat crime within New York City. They can make changes to their yearly budget and the departments within their organization that may need labor reinforcement in order to create a safer place for NYC residents. They can also recommend strategies to educate the general public about implementing different safety measures when present in high risk areas.
 
Data Sources:

1.NY Open Data - NYPD Complaint Data Historic
https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i 

### Business Requirements Definition

List of Data Warehouse KPI's:

1. Total complaints by borough
2. Crimes committed by age of suspect
3. Crimes by victim’s races
4. Crime by victim’s ages 
5. Common offense by borough


### Dimensional Model

This project's Dimensional Model consists of 1 Facts Table and 6 Dimensions

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Map of New York City for Total complaints by borough
2. Horizontal Bar Chart for Crimes committed by age of suspect
3. Highlighted Table for Crimes by victim’s races
4. Horizontal Bar Chart for Crime by victim’s ages 
5. A Tree Map for Common offense by borough

### Deployment

The project was deployed on Tableau Public:

Dashboard 1:
https://public.tableau.com/app/profile/tenzing.wangdu8609/viz/NYCCrimeReductionProject/Dashboard_1_Geographic?publish=yes 

Dashboard 2:
https://public.tableau.com/app/profile/tenzing.wangdu8609/viz/NYCCrimeReductionProjectDemographic/Dashboard_2_Demographic?publish=yes


```python

```

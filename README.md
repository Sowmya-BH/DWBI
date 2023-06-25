
# Crime Analysis in the United States :
A number of violent and non-violent crimes are committed in the United States each year.In this project, we divided violent crimes into divided  four categories in accordance with FBI's Uniform Crime Reporting (UCR) Program: murder and nonnegligent manslaughter, forcible rape, robbery, and aggravated assault. Non-violent crimes generally include (a) property crimes, such as theft, larceny, embezzlement, receipt of stolen goods, and arson of personal property; (b) Contract crimes, fraud, tax crimes; (c) Various drug and alcohol-related crimes; (d) Various other crimes including traffic offences, prostitution, gambling, bribery, etc. A detailed analysis of these crimes allows us to comprehend the crime pattern in an area and derive insights for future understanding of criminal activity patterns. 

This study aims to highlight some of the safest and most unsafe areas in America. Studying demographic factors, GDP, annual income, educational qualification and impact of family history can help us gather a fair understanding of crimes

# Dataset:
For this project we have used a Socio-economic dataset from the '90 Census. It contains Law enforcement data from the 1990 Law Enforcement Management Admin Stats survey And Crime data from the 1995 FBI UCR. The dataset consists of 2215 instances across 147 attributes which include 3 categorical and 144 numeric attributes. The data is divided into states and communities. 

## Methodology and Tools Used
Python 3.9.7 for data preprocessing.
We have used Tableau to generate the visualizations and analyze the data. 

## Challenges and Limitations
Our dataset consisted of a lot of null values making it necessary to preprocess the data and exclude columns that we deemed unfit during our analysis. Another challenge was identifying which of the 146 parameters were relevant. To identify the parameters for our analysis we created a corrplot.


# Analysis:
The dashboard represents analysis of Violent and Non-Violent Crimes based on socio-economic factors. For the purpose of analysis, we have used features pertaining to Education, Unemployment and Poverty. In the dashboard we measure these features as follows:
Poverty has been measured as the average percentage of the population under poverty.
Education is measured in 2 levels, the population without a high school degree and the population with at least a Bachelor’s degree.
Unemployment is measured as the average percentage of unemployed population for a given state.
Each circle in the 3 scatter plots represents a state in the United States

The second dashboard is an interactive visualization that provides custom analyses of offense data within one or more states and in the entire  United States of America and . The interactivity allows users to filter data based on the state and to get a holistic view of the crime statistics in the entire country as well as  in the entire state. The state filter is the primary selection tool that allows users to choose to obtain data for one or more individual states. 



# Results: 
## Dashboard - 1
### Poverty vs Crimes:
There are higher non violent crimes than violent crimes and they both increase with an increase in the percentage of population under poverty.
 
### Education vs. Crime:
The number of non-violent crimes per 100k population increase regardless of the percentage of people educated in the state. However, the number of violent crimes per 100k population decreases as a higher proportion of the state’s population earns at least a bachelor’s degree.
 
### Unemployment vs. Crime:
The number of violent and non-violent crimes per 100k population increase with an increase in the percent of the state’s unemployed population.

### Non-violent crimes per violent crime vs. State:
The map chart depicts the rate of non-violent crimes per violent crime for each state. The ratio is highest for the state of Nevada which means, the state experiences a lot more non-violent crimes compared to violent crimes.

## Dashboard - 2
Crime is more concentrated in certain pockets of the state. For example, Chicago city accounts for the majority of the crimes committed in Illinois. 

Washington DC is the area with the greatest number of violent crimes committed per head whereas California has the highest number of crimes committed.

Majority of the crimes committed are non violent crimes with Larcenies being the most common among non violent crimes and burglaries being the most common among violent crimes.


 

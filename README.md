
# Crime Analysis in the United States :
A number of violent and non-violent crimes are committed in the United States each year. Violent crime is divided into four categories under the FBI's Uniform Crime Reporting (UCR) Program: murder and nonnegligent manslaughter, forcible rape, robbery, and aggravated assault. Non-violent crimes generally include (a) property crimes, such as theft, larceny, embezzlement, receipt of stolen goods, and arson of personal property; (b) Contract crimes, fraud, tax crimes; (c) Various drug and alcohol-related crimes; (d) Various other crimes including traffic offences, prostitution, gambling, bribery, etc. A detailed analysis of these crimes allows us to comprehend the crime pattern in an area and derive insights for future understanding of criminal activity patterns. 

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


# Results: 
## Poverty vs Crimes:
There are higher non violent crimes than violent crimes and they both increase with an increase in the percentage of population under poverty.
 
## Education vs. Crime:
The number of non-violent crimes per 100k population increase regardless of the percentage of people educated in the state. However, the number of violent crimes per 100k population decreases as a higher proportion of the state’s population earns at least a bachelor’s degree.
 
## Unemployment vs. Crime:
The number of violent and non-violent crimes per 100k population increase with an increase in the percent of the state’s unemployed population.

## Non-violent crimes per violent crime vs. State:
The map chart depicts the rate of non-violent crimes per violent crime for each state. The ratio is highest for the state of Nevada which means, the state experiences a lot more non-violent crimes compared to violent crimes.

 

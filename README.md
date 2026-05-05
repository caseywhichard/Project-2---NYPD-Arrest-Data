# Team 7-MIST 4610 Group Project 2 - NYPD Arrest Data
## Team Name:
21479 Group 7
## Group Members:
  1. Casey Whichard
  2. Ally McVay - https://github.com/allymcvay/NYP-Arrest-Data
  3. Sydney Pratt - https://github.com/scp31975/Project-2-NYPD-Arrest-Data-Year-to-Date
  4. Mino Guzman - https://github.com/Mino-Guzman/MIST-4610-Project-Two---NYPD-Arrest-Data

## Dataset Description
The NYPD Arrest Data Set was published by the City of New York on Data.gov with the provided metadata being modified most recently on 02/09/26. The dataset contains 19 clearly defined fields (columns) and a total of 278,953 rows. The columns within the dataset include ARREST_KEY, ARREST_DATE, PD_CD, PD_DESC, KY_CD, OFNS_DESC, LAW_CODE, LAW_CAT_CD, ARREST_BORO, ARREST_PRECINCT, JURISDICTION_CODE, AGE_GROUP, PERP_RACE, X_COORD_CD, Y_COORD_CD, Latitude, Longitude, Location. These columns help capture the key aspects of each arrest, including the type of offense committed, the legal classifications of the crime, the geographic location of the arrest, and the demographic characteristics of the suspect such as their age group, race, and sex. The data represented within the set includes a mix of data types such as integers, floats (decimal numbers), and text values. This combination of structured data allows users to easily understand patterns in police enforcement activity, for example when and where arrests occur and what types of crime are most common.

## Necessary Dataset Manipulations 
There were no manipulations or calculations applied to the NYPD Arrest Dataset prior to inputting the information into Tableau. We chose to use the NYPD Arrest Dataset as it was already comprehensive, well-organized, and appropriately formatted for our analysis. Before uploading the dataset into Tableau to begin creating our visuals we, as a group, reviewed it in order to ensure that there were no missing values, inconsistencies, or formatting issues that would negatively impact our results. Therefore, since the dataset met our standards, we were able to continue without further manipulation.

# Question #1 - What is the crime rate for each of the 5 boroughs?

## Tableau Visualization 
<p align="center">
<img width="629" height="553" alt="Screenshot 2026-05-04 at 7 35 03 PM" src="https://github.com/user-attachments/assets/72071adc-ae49-428c-9049-c6c55f7d756b" />
</p>

## Importance
Our client is the NYPD, and this question is important for them to better understand, in general, where the most crimes are committed in the city. This information can help determine where its efforts and funding should be primarily spent, as the police stations in boroughs with higher crime may need more resources than stations in low crime areas. This funding could include more training for officers, advancements on weapons or state vehicles, or crime prevention programs, depending on which kinds of crimes are committed. This data relates to the dataset since each arrest listed contains the borough/location where the arrest took place, so we can therefore find the total count of crimes within each borough.  

## Analysis & Results
For this question, we chose to use a dashboard in Tableau showing a heat map of New York City alongside a bar chart showing total arrest count for the five boroughs. With the heat map, we were able to see that arrest activity is more concentrated in the northern and central regions, those being Manhattan and Brooklyn. The bar chart confirms this Brooklyn being the region with the highest arrest count, followed by Manhattan.

The difference between the five boroughs is likely due to many factors such as population size, density, and wealth disparities. The data visualization allowed us to see concentration and the distribution between the boroughs, which is why we wanted to drill down into the causes in question two. 

# Question #2 - Within the borough with the highest crime, who is committing the most violent vs. nonviolent crimes based on age and gender?

## Tableau Visualization 
<p align="center">
<img width="632" height="417" alt="Screenshot 2026-05-04 at 7 35 31 PM" src="https://github.com/user-attachments/assets/d141bb6d-4aff-4f70-83d1-fa805ff2c58d" />
</p>

## Importance
This question is important to our client, the NYPD, to answer in order to determine what type of funding they should focus on. We assume the NYPD wants to focus its funding on the borough with the highest crime rate, which was answered in the previous question. So, by looking at violent vs. nonviolent crimes, as well as which demographics are committing these crimes, can determine the type of training officers receive, for example, whether they focus their efforts on targeting middle-aged males versus young females. Also, depending on whether or not violent or nonviolent crimes make up most of the borough’s crimes, this can determine the types of prevention programs that the NYPD can endorse. This data relates to the dataset since each arrest reports what the individual was arrested for, as well as their age and gender, so we can therefore determine who is committing what crimes in the most dangerous borough.

## Analysis & Results
For question 2, we opted to use a side by side bar chart to go more in depth into Brooklyn’s arrests, with crime type (Violent and Non Violent), age, and gender. Since in question 1 we were able to find that Brooklyn was the borough with the highest crime rate, we wanted to take a closer look into who was committing the crimes.

The bar chart shows that across all categories, males account for the majority of arrests. The 25-44 age group had the highest arrest count for both non violent and violent crimes, with the 45-64 age group coming in second. The visualization also shows that non violent crimes tend to be more popular than violent crimes in every age group. The graph itself is unimodal with one peak at 25-44 and a clear drop off. The visualization allowed us to see exactly which demographic groups are most represented in Brooklyn's arrest data, giving us a clearer picture of where the crime is coming from within the borough.

These results suggest that young and middle aged males are the most at risk demographic with crime activity in Brooklyn. With the majority of crimes being non violent, this may suggest that the arrests are tied to offenses such as drug possession or petty theft rather than more serious violent crimes. The significant drop off in arrests for those under 18 and those 65 and older could reflect differences in lifestyle, opportunity, or even how crimes are reported and prosecuted across different age groups. Overall, these findings point to the idea that targeted intervention programs aimed at males in the 25-44 range could potentially have the greatest impact on reducing Brooklyn's overall arrest rate.

## Assumptions
For this assignment, we approached the NYPD Arrest Data Set from the perspective of recent college graduates relocating to New York City who are choosing to prioritize safety when choosing where to live, since each of us are approaching that time where we will end up deciding where to live once we graduate. As individuals unfamiliar with the city’s daily crime patterns, we sought to better understand how arrest activity varies across the five boroughs and which areas present higher or lower levels of risk. We assume that our client, the NYPD, cares deeply about its citizens and understands the trend of young people moving into the city, which is why they need our help.

Our primary goal in analyzing this dataset was to gain insight into both the geographic distribution of crime and the demographics most commonly associated with arrests. This perspective not only helped us identify where crimes tend to be more concentrated, but also provided a clearer understanding of the types of offenses being committed and the individuals involved. This information is helpful to our clients, the NYPD, who are interested in how and where to distribute their funding in order to ensure better safety throughout the city.

Ultimately, we chose to examine this dataset because it offers real, structured information that can support informed and practical decision-making. The insights we took away from this analysis can help guide choices related to housing, lifestyle, and overall awareness of public safety in New York City. In conclusion, ‘this approach demonstrates how data-driven analysis can lead to more confident and informed decisions for how to protect natives and new-comers of New York City. 

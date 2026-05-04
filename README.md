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

# Question #2 - Within the borough with the highest crime, who is committing the most violent vs. nonviolent crimes based on age and gender?

## Tableau Visualization 
<p align="center">
<img width="632" height="417" alt="Screenshot 2026-05-04 at 7 35 31 PM" src="https://github.com/user-attachments/assets/d141bb6d-4aff-4f70-83d1-fa805ff2c58d" />
</p>

## Importance
This question is important to our client, the NYPD, to answer in order to determine what type of funding they should focus on. We assume the NYPD wants to focus its funding on the borough with the highest crime rate, which was answered in the previous question. So, by looking at violent vs. nonviolent crimes, as well as which demographics are committing these crimes, can determine the type of training officers receive, for example, whether they focus their efforts on targeting middle-aged males versus young females. Also, depending on whether or not violent or nonviolent crimes make up most of the borough’s crimes, this can determine the types of prevention programs that the NYPD can endorse. This data relates to the dataset since each arrest reports what the individual was arrested for, as well as their age and gender, so we can therefore determine who is committing what crimes in the most dangerous borough.

## Analysis & Results
## Assumptions

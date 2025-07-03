# Police-Arrest-Analysis

## Table of Contents

- [Data_Overview](#data-overview)
- [Content](#content)
- [Data_Sources](#data-sources)
- [Some_Abbreviations_and_Meaning](#some-abbreviations-and-meaning)
- [Observations_During_Cleaning_and_Preparation](#observations-during-cleaning-and-preparation)
- [Findings](#findings)
- [Recommendation](#recommendation)
- [References](#references)

### Data Overview

The U.S police is in a quest to understand the reason for increase in suspects in a particular period and how this number of arrested suspected can be mitigated.

### Content

OVERVIEW:
The dataset analyzed is a police arrest report that shows reports of the following;

- ID Reference Number: This is the inmate's Identification Number.
- Subject Race: This is how they can identify the Inmate based on their skin color and biological traits.
- Gender: This has to do with whether they are male or female
- Ethnicity: This has to do with the Language and language group they belong.
- Age: This has to do with the Age grade the inmate falls into.
- Adjacent to School: This has to do with how Far or near they were arrested close to school
- Assigned Division: This has to do with the Unit they were arrested in an Area.
- Assigned Bureau: This has to do with the Area where they were arrested
- Event Date: It is the record of the date they were arrested from 2021-2024.
- Event time: This has to do with the time the inmates were arrested.
 
### Data Sources

This data set is a relational dataset and it is a CSV file extension.


### Some Abbreviations and Meaning

On the Assigned BUREAU we have some Abbreviation that needs to be studied.

* 1.FSB: FSB (Field Services Bureau): This Bureau Handles On-the-ground Policing Activities, Including Patrol, Traffic Control, And Response To Incidents.

* 2.PSB : PSB (Patrol Services Bureau): Similar To FSB, This Bureau Focuses On Patrol Operations And Maintaining Order Within A Defined Area.

* 3.ISB : (Investigative Services Bureau): This Bureau Is Responsible For Investigating Crimes, Gathering Evidence, And Pursuing Criminal Cases.

* 4.MSB : (Management/Maintenance Services Bureau): This Bureau Provides Support Services, Such As Fiscal Management, Personnel Administration, And Technology Infrastructure For The other Bureau.

- On the Assigned Division we have some Abbreviation that needs to be studied.
* 1. TOD: 
* 2. 3D
* 3. 5D
* 4. IMTD
* 5. 2D
* 6. SVID
* 7. PSTA
* 8. PSCC
* 9. SVID
* 10 MCSO and so much more.
	 All these are Divisions under Assigned Division.

### Observations During Cleaning And Preparation

- From the original dataset collected, there were 23,511 rows and 11 columns. But after the cleaning of      Null Values, the columns and rows left was 18,775 rows and 11 columns respectively.
- On the Adjacent to school column, the values 1 and 0, were replace with text “ Near” and “Far”     respectively.
- The Engine in excel that was used to transform this data to a proper analyzable dataset is the power     query Editor.

### Findings

-  Highest per group
* a. By Race - Black African American
* b. By Gender- Male
* c. By Age- 18 years old
* d. By Ethnicity - Non-Hispanic
* e. By Time/Period - 5pm
* f. By Assigned Bureau- PSB
* g. By Year and Month - March, 2022
* h. By Assigned Division - 3D
* i. By Location adjacent to school - Far

  - Lowest Per group
  * a. By Race - Hawaiian/Pacific Islander
  * b. By Gender - Female
  * c. By Age - 1,82,84,85 and 86 years old
  * d. By Ethnicity - Hispanic
  * e. By Time/Period - 5am
  * f. By Assigned Bureau - MSB
  * g. By Year and Month - February, 2021
  * h. By Assigned Division - PERS and PSCC
  * i. By Location adjacent to school - Near


### Recommendation:
  
From this analysis, the age group arrested the most are the 18 years. So, Government should create     engaging activities or skill empowerment for them both male and Female to enable them to be busy.

Also, It is observed that people caught mostly don’t speak a known language( which is Spanish). So when arrested, they should have a language councilor that will help interpret if the arrested are guilty or not.


### References:
* The Police Logo used for this dashboard was gotten from google.
* Microsoft Excel 2021 







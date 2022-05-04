# How foreign actors avoided disclosures while lobbying U.S. govt
## By Nazmul Ahasan

### Story Summary

Over the last decade, lobbyists employed by foreign entities spent over a hundred million dollars lobbying various levels of the United States government under a lobbying act riddled with loopholes, a review of lobbying disclosures submitted to the Senate and the House of Representatives shows.

These lobbying maneuvers were regulated under the Lobbying Disclosure Act (LDA), which significantly curtailed the potency of the Foreign Agents Registration Act (FARA), the law originally designed to regulate lobbying linked to foreign countries. 

Under current legal requirements, a lobbyist — even if working for a foreign client — can avoid a higher level of scrutiny and disclosure requirements under FARA if they disclose limited information under LDA, as long as their client was not any foreign government or political party.

However, an analysis of data gleaned from lobbying databases maintained by the Senate and the House of Representatives portrays a stark difference in the issue areas for foreign entities and domestic entities. Foreign entities are pursuing issues in D.C. that may be more consistent with the governmental agenda of their respective countries.

For the U.S.-based entities, for example, health issues and budget-related issues have been the top two priorities. In contrast, foreign entities lobbied to influence taxation and trade-related issues in the U.S. the most.

Among foreign entities, those based in 15 countries identified as top ‘tax heaven’ by the advocacy group Tax Justice Network were mainly interested in taxation in the U.S, the analysis shows. 

**As expert sources, I incorporated in the story quotes from two individuals: Nicholas Shaxson of the Tax Justice Network, a London-based advocacy group on tax avoidance, and Craig Holman of Public Citizen, a D.C.-based non-profit that promoted government accountability and transparency. The full story has been submitted on bCourse. For future reporting, I intend to contact William H. Minor, a partner at DLA Piper who specializes in lobbying compliance matters (william.minor@dlapiper.com) and Peter Courtney, an intelligence analyst with the FBI who co-authored a research paper in 2020 into the exploitation of LDA by foreign entities: https://www.linkedin.com/in/peter-courtney-62391a15a/)**


*Datasets used for the analysis were sourced from the Senate and the House of Representatives. The Senate dataset contained the money spent by lobbyists, while the House dataset contained areas or issues that these lobbyists covered. The Senate dataset was available thanks to [a new project](https://publicaccountability.org/datasets/427/foreign-entities/#) by the Investigative Reporting Workshop at American University, while the latter was derived from [an interactive searchable database](https://disclosurespreview.house.gov/) maintained by the House. The first database was compiled as .csv files [here](https://github.com/the-nazmul/j296/blob/main/lda_client-foreign%20.csv) and the second, [here](https://github.com/the-nazmul/j296/blob/main/Final_assignment_Data_journalism%20-%20General%20Data.csv).*




### Data Analysis

#### 1. Top countries where foreign entities are located

![Top 10 countries where foreign entities are based in](https://github.com/the-nazmul/j296/blob/main/Screen%20Shot%202022-05-04%20at%201.18.51%20AM.png)

##### Sheet Used: *lda_client-foreign* tab of the [*lda_client-foreign*](https://github.com/the-nazmul/j296/blob/main/lda_client-foreign%20.csv) 
**Data Analysis Process:**
- Created a pivot table using *Entity Country* as row and (unique) *client IDs* as values.
- Copied the resultant table and pasted it in a new tab. Sorted to find the highest value. 

#### 2. Top issues that foreign entities lobbied on

![Top issues that foreign entities lobbied on](https://github.com/the-nazmul/j296/blob/main/Screen%20Shot%202022-05-04%20at%201.29.59%20AM.png)

##### Sheet Used: *Foreign Entities* tab of the [*Final Project_Data Journalism*](https://github.com/the-nazmul/j296/blob/main/Final_assignment_Data_journalism%20-%20General%20Data.csv) 

**Data Analysis Process:**
- I created a table using data derived from the House database. The table contained the list of countries where foreign entities were located and the number of disclosures that those entities submitted over the years. 
- I then sorted the column containing the number of disclosures by Z to A to find the highest values.

#### 3. Top issues that lobbyists for entities based in ‘tax haven’ countries covered

![Top issues covered by foreign entities based in tax haven countries](https://github.com/the-nazmul/j296/blob/main/Screen%20Shot%202022-05-04%20at%201.41.57%20AM.png)

##### Sheet Used: *Tax Haven* tab of the [*Final Project_Data Journalism*](https://github.com/the-nazmul/j296/blob/main/Final_assignment_Data_journalism%20-%20General%20Data.csv) 


**Data Analysis Process:**
- I created a table using data derived from the House database. The table contained the list of 15 top tax haven countries (as per the Corporate Tax Haven Index) where foreign entities were located and the number of disclosures that those entities submitted over the years. 
- I then sorted the column containing the number of disclosures by Z to A to find the highest values.

#### 4. Priorities of domestic entities and foreign entities were not the same

![Top issues by foreign entities, entities based in tax haven countries, and U.S. domestic entities](https://github.com/the-nazmul/j296/blob/main/Screen%20Shot%202022-05-04%20at%201.54.23%20AM.png)

##### Sheet Used: *Tax Haven* tab of the [*Final Project_Data Journalism*](https://github.com/the-nazmul/j296/blob/main/Final_assignment_Data_journalism%20-%20General%20Data.csv) 

**Data Analysis Process:**
- Employing the previous analysis on general data, U.S. domestic entities, and foreign entities excluding tax haven countries, I prepared a comparative table.
- I calculated the share of lobbying areas for each of the five categories.
- Marked the first three categories for each entity type with Red, Yellow, and Green, respectively.

#### 5. LDA registration pattern after Justice Dept crackdown in 2017

In 2017, after the Muller investigation, the Justice Department vigorously enforced FARA, which led to a 30% increase in FARA registrations. However, my analysis would show that LDA registrations also increased, after the initial shock in the 2017-18 period.

![LDA registration numbers by years](https://github.com/the-nazmul/j296/blob/main/Screen%20Shot%202022-05-04%20at%201.58.59%20AM.png)

**Data Analysis Process:**
- On the House database, I simply narrowed down the yearly number of disclosures by Registration (and Registration Amended) disclosures to find out yearly new registrations.
- I then created a line chart to show the differences. The data viz is included in the following section.

#### 6. Money spent by foreign entities on lobbying (by countries)

![Money spent by foreign entities by countries](https://github.com/the-nazmul/j296/blob/main/Screen%20Shot%202022-05-04%20at%202.09.58%20AM.png)

##### Sheet Used: *Money Spent* tab of the [*lda_client-foreign*](https://github.com/the-nazmul/j296/blob/main/lda_client-foreign%20.csv) 

**Data Analysis Process:**
- Created a pivot table using *Entity Country* as row and (unique) *client IDs* and *Sum of Entity Contribution* as values.
- Copied the resultant table and pasted it in a new tab. Sorted to find the highest values. 


## Data Vizualization

*The following is [a line chart](https://datawrapper.dwcdn.net/JynIC/1/) showing the increase in LDA registrations following a reduction in registrations in 2018, following the Justice Department’s crackdown a year earlier.*

![lobbying registration by year](https://github.com/the-nazmul/j296/blob/main/JynIC-lda-disclosures-by-years.png)

*The following is [a split bar chart](https://datawrapper.dwcdn.net/1Ossc/1/) depicting the top 25 lobbying issue areas for different types of foreign and domestic entities.*

![top 25 lobbying areas](https://github.com/the-nazmul/j296/blob/main/top-areas-lobbying.png)

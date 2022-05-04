# How foreign actors evade scrutiny while lobbying U.S. govt
## By Nazmul Ahasan

### Story Summary

Over the last decade, lobbyists employed by foreign entities spent over a hundred million dollars lobbying various levels of the United States government under a lobbying act riddled with loopholes, a review of lobbying disclosures submitted to the Senate and the House of Representatives shows.

These lobbying maneuvers were regulated under the Lobbying Disclosure Act (LDA), which significantly curtailed the potency of the Foreign Agents Registration Act (FARA), the law originally designed to regulate lobbying linked to foreign countries. 

Under current legal requirements, a lobbyist — even if working for a foreign client — can avoid a higher level of scrutiny and disclosure requirements under FARA if they disclose limited information under LDA, as long as their client was not any foreign government or political party.

The analysis of data gleaned from lobbying databases maintained by the Senate and the House of Representatives suggests that foreign entities and domestic entities are not interested in the same type of issues.

For the U.S.-based entities, the health issues and budget-related issues have been the top two priorities. In contrast, foreign entities lobbied to influence taxation and trade-related issues in the U.S. the most.

Among foreign entities, those based in 15 countries identified as top ‘tax heaven’ by the advocacy group Tax Justice Network were mainly interested in taxation in the U.S, the analysis shows. 

*Datasets used for the analysis were sourced from the Senate and the House of Representatives. The Senate dataset contained the money spent by lobbyists, while the House dataset contained areas or issues that these lobbyists covered. The Senate dataset was available thanks to [a new project](https://publicaccountability.org/datasets/427/foreign-entities/#) by the Investigative Reporting Workshop at American University, while the latter was derived from [an interactive searchable database](https://disclosurespreview.house.gov/) maintained by the House.

### Data Analysis

#### 1. Which are the top countries where foreign entities are located?

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

#### 3. Issues that entities based in ‘tax haven’ countries covered

![Top issues covered by foreign entities based in tax haven countries](https://github.com/the-nazmul/j296/blob/main/Screen%20Shot%202022-05-04%20at%201.41.57%20AM.png)

##### Sheet Used: *Tax Haven* tab of the [*Final Project_Data Journalism*](https://github.com/the-nazmul/j296/blob/main/Final_assignment_Data_journalism%20-%20General%20Data.csv) 


**Data Analysis Process:**
- I created a table using data derived from the House database. The table contained the list of 15 top tax haven countries (as per the Corporate Tax Haven Index) where foreign entities were located and the number of disclosures that those entities submitted over the years. 
- I then sorted the column containing the number of disclosures by Z to A to find the highest values.

#### 4. Priorities of domestic entities and foreign entities were not the same

[Top issues by foreign entities, entities based in tax haven, and U.S. domestic entities](https://github.com/the-nazmul/j296/blob/main/Screen%20Shot%202022-05-04%20at%201.54.23%20AM.png)

##### Sheet Used: *Tax Haven* tab of the [*Final Project_Data Journalism*](https://github.com/the-nazmul/j296/blob/main/Final_assignment_Data_journalism%20-%20General%20Data.csv) 

**Data Analysis Process:**
- Employing the previous analysis on general data, U.S. domestic entities, and foreign entities excluding tax haven countries, I prepared a comparative table.
- I calculated the share of lobbying areas for each of the five categories.
- Marked first three categories for each entity type with Red, Yellow, and Green, respectively.

#### 5. LDA registration pattern after Justice Dept crackdown in 2017

In 2017, after the Muller investigation, the Justice Department vigorously enforced FARA, which led to a 30% increase of FARA registrations. However, my analysis would show that LDA registrations also increased, after initial shock in the 2017-18 period.

[LDA registration numbers by years](https://github.com/the-nazmul/j296/blob/main/Screen%20Shot%202022-05-04%20at%201.58.59%20AM.png)

**Data Analysis Process:**
- On the House database, I simply narrowed down the yearly number of disclosures by Registration (and Registration Amended) disclosures to find out yearly new registrations.
- I then created a chart to show the differences. The data viz is included in the following section.

#### 6. Money spent by foreign entities on lobbying (by countries)

[Money spent by foreign entities by countries](https://github.com/the-nazmul/j296/blob/main/Screen%20Shot%202022-05-04%20at%202.09.58%20AM.png)


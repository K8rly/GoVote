# GoVote

### Selected topic
Analyzing voter registration in Cuyahoga County by Age and Precinct in order to determine trends in voting patterns and party affiliation

### Reason we selected the topic
The United States is experiencing high levels of political turmoil, making this topic extremely relevant. Our group would like to identify potential factors contributing to voting trends within our shared home county, and analyze voter data to relate generational identification to voting patterns. In analyzing this data we hope to predict which party affiliation groups are more likely to vote for based on demographic and geographic features.

### Description of the source of data
The Cuyahoga County Board of Elections serves its citizens by conducting the fundamental and vital functions of the election process. The Cuyahoga County Board of Elections has many datasets available to the public on their website [here](https://boe.cuyahogacounty.gov/maps-and-data). We chose to use a government site as opposed to a less credible source in order to ensure we are using clean and accurate data. 



### Questions we hope to answer with the data

What age group is more likely to vote? More likely to vote Republican or Democrat?

What zip code is more likely to vote? More likely to vote Republican or Democrat?

What geographical area has a higher percentage of voters/highest number of boomers, gen z, etc
**Prediction: Which age groups/zip codes are more likely to vote Republican or Democrat?


### Description of the data exploration phase
Data Cleaning:
Removed unneeded columns (special elections are not county-wide and were not relevant)
Removed voter personal information (names and addresses)
Cleaned columns with prefixes to make ML easier
Reformatted zip codes to 5 digits for consistency (some were 9 digits)
Renamed Columns

### Description of the analysis phase
Data Analysis:
Divided data into specific dataframes
Joined data from primary elections, general elections, and voter demographic info
Organized data in bins based on generational groups/birth year
Performed counts on total number of voters for: party affiliation, generational group

### ERD with Relationships

!["ERD"](Images/ERD_final.png)


### Questions you should be asking yourselves as a team:
What story do you want your data to tell? 
 - We want our data to tell a story about voting trends within Cuyahoga County and how age and city affect these trends. We also want to highlight different generational groups in order to show differences between not only age, but entire generations.

Do you have a goal? 
 - Our goal is to ultimately develop a predictive tool to showcase voting potential for a given user. We also hope to paint a picture of current voting trends within a user's geographic location in order to help the user personally relate to the project and their own community's voting patterns.

What kind of message will your dashboard display? 
 - We want to show historical voting data for presidential elections over the last 14 years and how it compares to each generation group. Combining this analysis with location mapping will hopefully enable users to shed light on their community and it's voting practices. 

Think of the top 5 things you want users to take away from your dashboard about your data.
- The user's voting trends vs others in their community
- The user's voting trends vs others in their generational group
- Prediction of the user's voting party affiliation in the next presidential election
- A sense of the voting trends all over Cuyahoga County and party affiliation in the last 4 primary elections
- A sense of the voting trends all over Cuyahoga County for the last 4 presidential elections


### Schema
Please reference included Schema showing the work that has been completed in PGAdmin




### Additional Questions/Notes

Features:
Zip Code
Election type
Election year
Party affiliation
City

Count - people registered vs people voting (%, mean etc)
Count - based on generational identification (age ranges)

Generational Age ranges:  
Born 1928-1945 Silent  
Born 1946-1964 Boomers  
Born 1965-1980 Generation X  
Born 1981-1996 Millenials  
Born 1997-2012 Generation Z  


### Role Distribution

Circle - Database (Katterli)
Square - Github (Leiana)
Triangle - ML Model (Emad)
X - Technologies used (Sarah)


### Communication Protocols

Group meetings will be conducted via Zoom or in person as needed. Communications related to the deliverables will take place in our "final-group-2" Slack channel. We will continue to use our DM channel for side conversations and additional discussion, and in case of an emergency messages would be sent via Slack as we currently utilize Slack daily.

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

What city has a higher percentage of voters/highest number of boomers, gen z, etc
**Prediction: Which age groups/zip codes are more likely to vote Republican or Democrat?


### Description of the data exploration phase
Data Cleaning:
Removed unneeded columns (special elections are not county-wide and were not relevant)
Removed voter personal information (names and addresses)
Cleaned columns with prefixes to make ML easier
Reformatted zip codes to 5 digits for consistency (some were 9 digits)

### Description of the analysis phase
Data Analysis:
Divided data into specific dataframes
Performed counts on total number of voters 

### Questions you should be asking yourselves as a team:
What story do you want your data to tell? We want our data to tell a story about voting trends within Cuyahoga County and how age and city affect these trends.

Do you have a goal? Our goal is to ultimately develop a predictive tool to showcase voting potential for a given user. 

What kind of message will your dashboard display? We want to show historical voting data for presidential elections over the last 14 years, combined with location mapping to show our vision. 

Think of the top 5 things you want users to take away from your dashboard about your data.
-
-
-
-
-


The included Schema shows the work that has been completed in PGAdmin

Machine Learning Model (30 points)
The team members are expected to submit the code for the machine learning model, as well as the following:




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

Which voters voted in all elections vs only key elections (2008/2020 vs 2012/2016)?
Presidential election vs all elections?

Which voters were registered but didn't vote?
Which districts/zip codes have more people who are registered but not voting? Is this related to access?
Which voters vote by mail vs in person?
Voters who registered in a different zip than their home


For application/webpage:
Heat map to visualize by precinct
Put in DOB, district/zip code, etc. predict what party someone will vote for

Splitting dataset: demographic and election info

### Role Distribution

Circle - Database (Sarah)  
Square - Github (Katterli)  
Triangle - ML Model (Emad)  
X - Technologies used (Leiana)  


### Communication Protocols

Group meetings will be conducted via Zoom or in person as needed. Communications related to the deliverables will take place in our "final-group-2" Slack channel. We will continue to use our DM channel for side conversations and additional discussion, and in case of an emergency messages would be sent via Slack as we currently utilize Slack daily.

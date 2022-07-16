# GoVote

# Technologies Used

## Data Cleaning and Analysis
Pandas is utilized to clean our Cuyahoga County voting data, while completing an exploratory analysis on 
different aspects of the dataset. Using OnehotEncoding to determine party loyalty/switch to prepare for ML

## Database Storage 
PgAdmin (SQL) is the database we intend to use, while integrating the data into Tableau for visual effects.

**Table split**
Demographics of voter
voting record - primary election (OneHotCoding - party affiliation D/F/N) - issues only ballot if non-partisan(N)
voting record - general election with voter ID (Y = 1, Null = 0)

## Machine Learning
SciKitLearn is the ML library we will be using to create a classification model. Our training and testing
set up is 80/20. We will also possibly use a clustering model testing with voting age groups/districts

**Age Groups: Generational Age ranges: Born 1928-1945 Silent Born 1946-1964 Boomers Born 1965-1980 
Generation X Born 1981-1996 Millenials Born 1997-2012 Generation Z


## Dashboard
We will be using Tableau to display our findings, as well as Google slides for our overall presentation. 
The plan is to create an application that will allow entry of Birth year and Zip code to predict voting 
patterns if time permits.

First Segment Technology.md (7/17/2022)
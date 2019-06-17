The Public Health Dataset

Release Date: June 11, 2019

----------------------------------------------------------------------

README CONTENTS
0.1 Contact Information
0.2 Other
0.3 Folder Contents

1.0 Data Information
1.1 CDC data 
1.2 CHC data
1.3 FIPS code data

2.0 Data Tables
2.1 MASTER table

3.0 Challenges
3.1 Selenium
3.2 Looking Ahead
----------------------------------------------------------------------
0.1 Contact Information

This dataset was compiled by Geethanjali Krishnappa, Kevin Parrott, 
Jacob Rosen, and Manoj Venkatachalaiah for DSCS 511, Spring 2019. 

Please reach out with questions or concerns to jkr58@drexel.edu

----------------------------------------------------------------------
0.2 Other

Because this data was made from data taken from government websites,
it has all of the same free use protections as that data. In other 
words, this data can be used for research but cannot be used for 
things such as profit or identifying individuals.

----------------------------------------------------------------------
0.3 Folder Contents

FinalNotebook.ipynb	Code to create the final dataset (dataset.csv)

dataset.csv		Final dataset in CSV format

CHC_location.csv	Data on every community health center as CSV

----------------------------------------------------------------------

1.0  Data Information

----------------------------------------------------------------------
1.1 CDC Data

Interactive Map- https://www.cdc.gov/heartdisease/maps_data.htm

Tables- https://nccd.cdc.gov/DHDSPAtlas/Reports.aspx

CDC's Sources- https://www.cdc.gov/dhdsp/maps/atlas/data-sources.html

----------------------------------------------------------------------
1.2  CHC Data

Interactive Map- https://findahealthcenter.hrsa.gov/

Data Download (Health Center Service Delivery and Look–Alike Sites)
	- https://data.hrsa.gov/data/download

----------------------------------------------------------------------
1.3  FIPS Code Data

FIPS codes- http://datadictionary.naaccr.org/?c=11

----------------------------------------------------------------------

2.0  Data Tables

----------------------------------------------------------------------
2.1  MASTER table

Columns:

FIPS Code		5-digit Federal Information Processing Standard 
			Publication code
County Name		Name of US county or territory 

State Abbreviation	2 letter abbreviation of state name

State Name		Full state name

CV Death per 100K	Cardiovascular deaths per 100,000 people 

Population		Total population, 2013-2017 (5-year)

Poverty %		Percent of population at or below povery line 

% Older than 65		Percent of population 65 or older

Median Household Income	Median household income in dollars

Median Home Value	Median home value in dollars

Food Stamp Recipient %	Percent of population on food stamps

Edu. < College %	Percent of population with greater than college 
			education

Edu. < Highschool %	Percent of population with greater than high
			school education

# of Health Centers	Number of community health centers in county

People/Health Centers	Population divided by # of Health Centers

----------------------------------------------------------------------

3.0  Challenges

----------------------------------------------------------------------
3.1  Selenium

Although we confirmed that our notebook works many times, it will 
throw random errors. We believe this is because Selenium is fickle
software as the fix was simply restarting the kernel and running the 
code again.

----------------------------------------------------------------------
3.2  Looking Ahead

Time moves on and the country changes. How often CDC and the other sites
update their data is a decision they make. We certainly hope a researcher
in 5 years isnt pulling the same values that we are today. 
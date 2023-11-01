# Assignment 3

Find a dataset you can analyze for your final project (or a related topic, if you haven't yet assembled data that you need for your project). Ensure it is clean, then use a Pivot Table to ask an "interesting question" of the data.

# Census Bureau Data

I sourced 3 separate spreadsheets to create the dataset I needed, all from the [U.S. Census Bureau](https://data.census.gov/table/ACSDT1Y2022.B08105A?q=worked+from+home+in+district+of+columbia+in+2022).

Each spreadsheet held the "Means of Transportation to Work" under the following areas:
* 2022
* "Alone" (I am confused as to if this means single or single-household?)
* Above 16 years old

The difference -- the race.

## Cleaning the Data

1. I cleaned the data by adding all three spreadsheets to one master spreadsheet that I called "Alone workers commute style 2022."
2. I named the columns by data points: Year, Race, Age, Commute Type, Estimated # of Individuals, Total Surveyed, Margin of Error, Other
* the Total Surveyed column is blank for most fields, and only filled for the total # per race.
* The Margin of Error is per commute style and per total surveyed
* Other refers to that mystery demographic "alone", just so I didn't lose it.

## The Question
What relationship is there between race and work-from-home employment/commute style, in 2022?

## The Answer
My PivotTable broke down the following:
* Row: Race
* Column: Commute Type
* Value: Sum of Estimated # of Individuals

I found: 

| Race | # of Individuals who worked from home | 
| --- | ---|
| White | 71031|
| Asian | 6598|
| Hispanic or Latino |15856|

Answer: Work-from-home employees are most likley to be White, and least likely to be Asian. 

# More Work
Apply similar data to other major cities, and see what the difference in race demographics are. Examples: 

(East Coast)
* Philadelphia
* Baltimore
* Providence
* New York (this will be skewed in terms of population)
* Boston
(South)
* Richmond
* Raleigh
* Austin
* Dallas
* Chattanooga
(Midwest)
* Chicago
* Minneapolis
* St. Louis
* Clevland
(West)
* LA
* San Diego
* Seattle
* Portland
* San Fran
* Sacremento
* Anchorage
* Honolulu

Or, apply to the top tech citites in the U.S.: 

* Seattle
* Austin
* Atlanta
* Washington, D.C.
* San Francisco
* Boston
* Dallas
* Raleigh
* Huntsville
* Baltimore
* San Jose
* Denver
* Chicago
* New York
* Charlotte
* Los Angeles
* Boulder
* Colorado Springs
* Trenton
* Durham
* Salt Lake City
* San Diego
* Philadelphia
* Portland
* Detroit
* Columbus
* Madison
* Phoenix
* Tampa
* Kansas City
* Minneapolis
* Miami
* Cincinnati
* Des Moines
* Lansing
* Hartford
* Tallahassee
* East Lansing
* Houston
* Pittsburgh
* Sacramento
* Cambridge
* Irvine
* Provo
* Jacksonville
* Corvallis
* Omaha
* Sierra Vista

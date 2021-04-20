# project_one

Project_One; Example 1; Covid vaccinations by supplier
Team:  Tarak Patel, Nicole Lund, Anne Niemiec

Subject/Core Message:  We will review Covid vaccines by three suppliers in each state to include, trends and relationships between the suppliers.  We will review Covid vaccines by three suppliers in each state to include, trends and relationships between the suppliers.  Determine the number of people, per state, has recieved their second dose.

Potential Hypothesis:  We expect to see a significant ramp-up as suppliers have higher distribution in markets. Anomolies would include inclimate weather (i.e. Texas storm).  Evaluate the congruancy between first and second dose.  Expect to see a higher ratio of Maderna and Pfizer with be reflective of states with greater density in population.

URLs:  
## Pfizer Data
https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/saz5-9hgg

## Maderna Data
https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/b7pe-5nws

## Jurisdiction-Janssen-
https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/w9zu-fywh

Source:  HHS ASPA (all three suppliers)

Summary of dataset: Allocation of vaccinations to state, by supplier, timeframe (week), etc.

Data exploration and cleanup: 
-Compare 1st and 2nd dose by supplier versus
    state/region (bar chart)
    timeframe (line chart)
-Map total allocation by state (heatmap)
-Summarize weekly data by state and timeframe (plot chart)
-Compare number of vaccinations by type, per week/month
-Outliers with anomolies (i.e. freeze in Texas) (box/whiskers chart)
-# of doses, by supplier, administered per day by state (scatter)
-Varied datasets (row, columns); create one dataframe
-Anomoly is J&J supplier since it only includes one dose versus two doses
-Disclaimer needs to denote the number of vaccinations allocated versus received
-Evaluate null data values
-Scrub data to ensure accuracy and anomolies (i.e. Guam)
-Varied release dates (deployment) by supplier
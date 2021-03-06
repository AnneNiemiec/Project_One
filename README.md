# UofA Data Analytics Bootcamp Group Project 1

-----

**Team**:  Tarak Patel, Nicole Lund, and Anne Niemiec

**Field of Investigation**: Covid-19 Health Data

## Project Description

**Subject/Core Message**:  We will review Covid vaccine allocation trends to various states in the US for all three suppliers.  This will be contrasted with Covid death rates over that period and state populations from Census data.

**Data Hypothesis:**

* We expect to see a significant ramp-up in vaccine allocation with time. Aside from known anomolies like the Texas storm in March.
* We believe the distrubition ratios between the first and second dose will invert over time with early dates showing a higher level of 1st dose allocations and later dates showing a higher level of 2nd dose allocations.
* We expect to see larger quantities of Pfizer vaccines being allocated to states with the greatest population density due to storage requirements and larger quantities of Johnson and Johnson vaccines being allocated to states with lower population densities.

**Data Sources**

* Pfizer Vaccine Allocation Data: https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/saz5-9hgg

* Maderna Vaccine Allocation Data: https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/b7pe-5nws

* Johnson & Johnson Vaccine Allocation Data: https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/w9zu-fywh

* Covid Cases and Deaths Data: https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36

* State Abbreviations List: https://www.infoplease.com/us/postal-information/state-abbreviations-and-state-postal-codes

## Repository Structure

* data_manipulation: Contains source data, data cleanup notebooks and cleaned data
* merged_data_analysis: Contains the merged analysis notebook and final figures
* presentation: Contains finished presentation and incorporated figures
* group1_analysis: Tarak Patel's analysis notebook and figures
* group2_analysis: Anne Niemiec's analysis notebook and figures
* group3_analysis: Nicole Lund's analysis notebook and figures

## Planned Visualizations

### Group 1 Charts authored by Tarak Patel (group1_analysis folder)

#### Chart-1  Line Plot showing National Summarized Vaccine Allocations by Date

* x-axis = Date (The data is reported weekly. To simplify the labels, convert the dates to a week number and then label by month.)

* y-axis = 
    * Line 1 - Pfizer + Moderna 1st dose allocation
    * Line 2 - Pfizer + Moderna 2nd dose allocation
    * Line 3 - J&J allocations
    * Note: y-axis data is a summation for all states
* Legend labels = Pfizer + Moderna 1st dose, Pfizer + Moderna 2nd dose, J&J Single dose

#### Chart-2  Line Plot showing National Vaccine Allocations by Date
* x-axis = Date (The data is reported weekly. To simplify the labels, convert the dates to a week number and then label by month.)

* y-axis = 
    * Line 1 - Pfizer 1st dose allocation
    * Line 2 - Moderna 1st dose allocations
    * Line 3 - Pfizer 2nd dose allocations
    * Line 4 - Moderna 2nd dose allocations
    * Line 5 - J&J allocations
    * Note: y-axis data is a summation for all states

* Legend labels = Pfizer 1st dose, Moderna 1st dose, Pfizer 2nd dose, Moderna 2nd dose, J&J Single dose

#### Chart-3  Line Plot showing Individual State (Arizona) Vaccine Allocations by Date
* x-axis = Date (The data is reported weekly. To simplify the labels, convert the dates to a week number and then label by month.)

* y-axis = 
    * Line 1 - Pfizer 1st dose allocation
    * Line 2 - Moderna 1st dose allocations
    * Line 3 - Pfizer 2nd dose allocations
    * Line 4 - Moderna 2nd dose allocations
    * Line 5 - J&J allocations

* Legend labels = Pfizer 1st dose, Moderna 1st dose, Pfizer 2nd dose, Moderna 2nd dose, J&J Single dose

#### Chart-4  Bonus Line Plot showing Individual State (User Choice) Vaccine Allocations by Date
* x-axis = Date (The data is reported weekly. To simplify the labels, convert the dates to a week number and then label by month.)

* y-axis = 
    * Line 1 - Pfizer 1st dose allocation
    * Line 2 - Moderna 1st dose allocations
    * Line 3 - Pfizer 2nd dose allocations
    * Line 4 - Moderna 2nd dose allocations
    * Line 5 - J&J allocations

* Legend labels = Pfizer 1st dose, Moderna 1st dose, Pfizer 2nd dose, Moderna 2nd dose, J&J Single dose


#### Chart-5  Chart showing the Total Dose Allocated, Total Dose Administered And Total Population by State   
* x-axis = State  
* y-axis =   
	* Bar 1: Total Vaccine Administered by State  
	* Bar 2: Total Vaccines Allocated by State   
	* Bar 3: Total Population of the State  

#### Chart-6  Chart showing the % of Total Allocate Vaccines by CDS Vs % of Dose Administered by State (% calculated by dividing the Total Allocated and daily Vaccines by Each States Total Population)
* x-axis = State
* y-axis =
	* Bar 1: Total Vaccine Administered as % of Population of State * Bar 2: Total Vaccines Allocated as % of Population of State  
	
Note, the data for Vaccines Adminstered are not separated by state between 12/14/2020 to 1/13/2021

### Group 2 Charts authored by Anne Niemiec (group2_analysis)

#### Stacked Bar Plot showing Vaccine Allocations by State on latest date present in the data

* x-axis = State

* y-axis = 
    * Bar 1: Pfizer cumulative 1st dose allocation
    * Bar 2: Pfizer cumulative 2nd dose allocation
    * Bar 3: Moderna cumulative 1st dose allocation
    * Bar 4: Moderna cumulative 2nd dose allocation
    * Bar 5: Johnson & Johnson cumulative single dose allocation
    
#### Stacked Bar Plot showing Vaccine Allocations Normalized by State Population by State on latest date present in the data

* x-axis = State

* y-axis = 
    * Bar 1: Pfizer cumulative 1st dose allocation / State Population
    * Bar 2: Pfizer cumulative 2nd dose allocation / State Population
    * Bar 3: Moderna cumulative 1st dose allocation / State Population
    * Bar 4: Moderna cumulative 2nd dose allocation / State Population
    * Bar 5: Johnson & Johnson cumulative single dose allocation / State Population 

#### 3 plot figure of Stacked Bar Plots showing Vaccine Allocations by State on latest date present in the data

* x-axis = State
    * Note, this is common to all 3 figures and should only be displayed on the bottom figure.

* Plot 1, y-axis:
    * Bar 1: Pfizer cumulative 1st dose allocation
    * Bar 2: Pfizer cumulative 2nd dose allocation
* Plot 2, y-axis:
    * Bar 1: Moderna cumulative 1st dose allocation
    * Bar 2: Moderna cumulative 2nd dose allocation
* Plot 3, y-axis:
    * Bar: Johnson & Johnson cumulative single dose allocation

### Group 3 Charts authored by Nicole Lund (group3_analysis)

#### Line Plot showing Cumulative National Vaccine Allocations and Reported deaths by date

* x-axis = Date

* Left y-axis = Total vaccine doses allocated cumulative across states
    * Note, reported weekly 

* Right y-axis = New deaths reported cumulative across states
    * Note, reported daily

#### Line Plot showing Cumulative National Vaccine Allocations and Reported deaths by week

* x-axis = Date (weekly on Mondays)

* Left y-axis = Total vaccine doses allocated cumulative across states

* Right y-axis = New deaths reported cumulative across states

#### Line Plot showing Cumulative National Vaccine Regimens and Reported deaths by date

* x-axis = Date (weekly on Mondays)

* Left y-axis = Total vaccine regimens allocated
    * Note, cumulative across states

* Right y-axis = New deaths reported weekly

#### Scatter Plot showing Reported Covid-19 Case Rate vs Poverty Rate by State

* x-axis = Poverty Rate (Percentage)

* y-axis = Reported Covid-19 Case Count / Population (Percentage)

* Include regression analysis

#### Scatter Plot showing Reported Covid-19 Death Rate vs Poverty Rate by State

* x-axis = Poverty Rate (Percentage)

* y-axis = Reported Covid-19 Death Count / Population (Percentage)

* Include regression analysis

#### Line Plot showing Cumulative Arizona Vaccine Allocations and Reported deaths by week

* x-axis = Date (weekly on Mondays)

* Left y-axis = Total vaccine doses allocated to Arizona

* Right y-axis = New deaths reported in Arizona

### Group 4 Charts to be considered later
* Line Plot showing State Level (User Selected) Vaccine Allocations and Reported deaths by date
* Map total allocation by state (heatmap)
* Identify Outlier anomolies, i.e. freeze in Texas (box/whiskers chart)

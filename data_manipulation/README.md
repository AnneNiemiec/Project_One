# UofA Data Analytics Bootcamp Group Project 1

-----

**Data Sources**

* Pfizer Vaccine Allocation Data: https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/saz5-9hgg

* Maderna Vaccine Allocation Data: https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/b7pe-5nws

* Johnson & Johnson Vaccine Allocation Data: https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/w9zu-fywh

* Covid Cases and Deaths Data: https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36

* Vaccinations Administered Data:
https://ourworldindata.org/us-states-vaccinations

* State Abbreviations List: https://www.infoplease.com/us/postal-information/state-abbreviations-and-state-postal-codes


## Planned DataFrames

### Vaccine Allocation DataFrame

#### Orignal Files
* COVID-19_Vaccine_Distribution_Allocations_by_Jurisdiction_-_Pfizer.csv
* COVID-19_Vaccine_Distribution_Allocations_by_Jurisdiction_-_Moderna.csv
* COVID-19_Vaccine_Distribution_Allocations_by_Jurisdiction_-_Janssen.csv
* state_code.csv

#### Clean File
* Combined_Vaccine_df.csv

#### Columns
* state_name
* state_code
* date
* day_num (count the days since 12/14/2020)
* pfe_dose_1
* pfe_dose_2
* mrna_dose_1
* mrna_dose_2
* jnj_dose_1

#### Invalid Data Removed From DataFrame
* ???



### Covid-19 Cases & Deaths DataFrame

#### Orignal Files
* United_States_COVID-19_Cases_and_Deaths_by_State_over_Time.csv
* state_code.csv

#### Clean File
* c_d_withstate_df.csv

#### Columns
* state_name
* state_code
* date
* day_num (count the days since 12/14/2020)
* total_cases
* confirmed_cases
* probable_cases
* new_cases
* pnew_case (probable_new_cases ???)
* total_deaths
* confirmed_deaths
* probable_deaths
* new_deaths
* pnew_deaths (probable_new_deaths ???)
* consent_cases (???)
* consent_deaths (???)
* created_at

#### Invalid Data Removed From DataFrame
* ???

### Census DataFrame

#### Orignal Data
* Census API
* state_code.csv

#### Clean File
* Population.csv

#### Columns
* state_name
* state_code
* population
* median_age
* household_income
* per_capita_income
* poverty_count
* poverty_rate
* unemployment_count
* unemployment_rate

#### Invalid Data Removed From DataFrame
* ???
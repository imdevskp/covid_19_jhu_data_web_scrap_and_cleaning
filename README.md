# covid_19_jhu_data_web_scrap_and_cleaning
This repository contains data and code used to get and clean data from 
1. https://github.com/CSSEGISandData/COVID-19 and 
2. https://www.worldometers.info/coronavirus/

## JHU data
* https://github.com/CSSEGISandData/COVID-19 contains the data that supports JHU's dashboard at https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6

## worldometer data
* According to worldometer 
> "For the COVID-19 data, we collect data from official reports, directly from Government's communication channels or indirectly, through local media sources when deemed reliable. We provide the source of each data update in the "Latest Updates" (News) section. Timely updates are made possible thanks to the participation of users around the world and to the dedication of a team of analysts and researchers who validate data from an ever-growing list of over 5,000 sources." - https://www.worldometers.info/about/

## Files

### Notebooks
* > *data_cleaning.ipynb* - Notebook used to get, clean and save data from https://www.worldometers.info/coronavirus/
* > *flurish_script.ipynb* - Notebook used to create flurish running bar chart at https://app.flourish.studio/visualisation/1571387
* > *worldometer_site_web_scrapping.ipynb* - Notebook used to scrap data from https://www.worldometers.info/about/

### Data    
* > *covid_19_clean_complete.csv* - Country wise day to day cases dataset  
* > *usa_county_wise.csv* - US county day to day cases dataset  

* > *full_grouped.csv* - Day to day country wise no. of cases (Has County/State/Province level data)  
* > *country_wise_latest.csv* - Latest country level no. of cases  
* > *day_wise.csv* - Day wise no. of cases (Doesn't have country level data)  
  
* > *worldometer_data.csv* - Data from https://www.worldometers.info/about/
   
* > *time_series_covid19_confirmed_global.ipynb* - Has day to day global confirmed cases data  
* > *time_series_covid19_deaths_global.ipynb* - Has day to day global deaths data  
* > *time_series_covid19_recovered_global.ipynb* - Has day to day global recovered data  
    
* > *time_series_covid19_confirmed_US.ipynb* - Has day to day US confirmed cases data  
* > *time_series_covid19_deaths_US.ipynb* - Has day to day US deaths data  

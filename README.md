# 498_winter_group_bfmnt

## Repo Layout

*./eda*: This holds our EDA notebook

*./etl*: Contains the ETL process. Does not include BigQuery SQL based ETL. Please refer to the saved queries in BigQuery

*./modeling*: contains a folder for supervised and another for unsupervised



## GCP Links

GCS 

https://console.cloud.google.com/storage/browser/capstone-team51-data;tab=objects?forceOnBucketsSortingFiltering=true&project=capstone-team51

BQ

https://console.cloud.google.com/bigquery?project=capstone-team51

**Note used the prod dataset for production work. Dev dataset is a sandbox. 

## Chicago Data Sources 

Environmental Data - https://data.cityofchicago.org/Environment-Sustainable-Development/CDPH-Environmental-Complaints/fypr-ksnz/data_preview

Crimes Data - https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data

Sex offenders Data - https://data.cityofchicago.org/Public-Safety/Sex-Offenders/vc9r-bqvy/data_preview *NOTE: SINCE ADDRESSES ARE ANONYMIZED, THE X ANONYMIZED VALUES ARE REPLACED WITH 0 SO 11XXX S STATE ST BECOMES 11000 S STATE ST TO APPROXIMATE THE LOCATION

311 Data - https://data.cityofchicago.org/Service-Requests/311-Service-Requests-Request-Types/dgc7-2pdf/about_data

Community Areas - https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6

Police Stations - https://data.cityofchicago.org/Public-Safety/Police-Stations/z8bn-74gv/about_data

Weather Data - https://meteostat.net/en/station/72534?t=2024-01-27/2024-02-03 (see https://dev.meteostat.net/api/stations/daily.html for API reference)

DATA401
Project-1
10/12/18
Team:

Members:
Likhita Narayana
Joseph Hurst
Anna Rulloda
Thomas Gerrity

The entire dataset can be found at this link: https://drive.google.com/open?id=1U5Yueqwcxn53WrMHn5RYaJiHjDMYCLvb

Dataset Columns:

'City'
'Date' - currently the data is aggregated by city at the day level

The next 9 columns are the sales distributions for the major alcohol types observed in the data.
'aggVODKA'
'aggRUM',
'aggBRANDIES',
'aggSCHNAPPS',
'aggWHISKIES',
'aggTEQUILA',
'aggSCOTCH',
'aggOTHER',
'aggLIQUEURS',

'numRecords', - The number of transactions aggregated - used to calculate the sales distributions

Dependant variable columns:
'Volume Sold (Liters)',
'Bottles Sold',
'Sale (Dollars)',

Census Data columns :

'Population',
'HousingUnits',
'AreaSQMT',
'DensitySQMP',
'DensitySQMH',

Dependent variable columns divided by the population column
'Volume Per Capita',
'Bottles Per Capita',
'Sales Per Capita'


The next 417 columns are the One-Hot-Encoded Cities

Split-Date columns:
'Dayofweek',
'Week', - the week of the year 1-52
'Month',
'Holiday' - a boolean column that was generated using the Holidays python module

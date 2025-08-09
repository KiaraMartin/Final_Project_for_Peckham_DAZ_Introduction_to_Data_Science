
# Final Project

This is the final project of Kiara Martin for the Peckham Digital Accelerator Zone: Introduction to Data Science course. 

I will be cleaning annual Chlamydia diagnoses in people aged 15 to 24 years, sunshine and rainfall data in England from 2015 to 2024. I will then compare the weather data against Chlamydia diagnostic data in attempts to identify a possible correlation between the two datasets.


## Installation instructions

Python version = Python 3.13.5

When installing Final_Project_V1.ipynb for the first time remove "#" in the first cell to install all the necessary libraries (these can be replaced afterwards), restart the Kernal and select "Run All".

### Python Packages Used

 - pandas
 - pandas matplotlib
 - plotly
 - nbformat

## Data Sources and Acquisition

 - Sunshine dataset (Met Office, 2025)
   Select "Year ordered statistics", Region as "England", Parameter as "Sunshine".
   This dataset measures monthly, seasonal and annual total duration of bright sunshine for England since 1910.
   
 - Rainfall dataset (Met Office, 2025)
   Select "Year ordered statistics", Region as "England", Parameter as "Rainfall".
   This dataset measures monthly, seasonal and annual total precipitation amount for England since 1836.

 - Chlamydia diagnoses dataset (GOV.UK, 2025)
   Select "NCSP: chlamydia testing data in people aged 15 to 24 years in England, 2015 to 2024", and sheet "Table_2_Genderidentity_age".
   This dataset measures Chlamydia tests and diagnoses by gender identity and age group in people aged 15 to 24 years, England, 2015 to 2024. (As acquired data is not always squeaky clean, please note the data in the row with the age group 15 - 24 was created by myself using the in the file using the sum of the 15 to 19 and 20 to 24 age groups, then saving this in the Chlamydia.csv file.)


## Acknowledgements

I would like to express my sincere gratitude to the team at Peckham DAZ and to my mentor, Yifan Feng, for their invaluable guidance and support throughout the duration of this course.


## References 

National chlamydia screening programme (NCSP): annual data (2025) GOV.UK. Available at: https://www.gov.uk/government/statistics/national-chlamydia-screening-programme-ncsp-data-tables (Accessed: 31 July 2025). 

UK and Regional Series (2025) Met Office. Available at: https://www.metoffice.gov.uk/research/climate/maps-and-data/uk-and-regional-series (Accessed: 31 July 2025). 


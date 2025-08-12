# Project Thought Process and Reflections


## Initial thoughts and project planning process

Initial hypothesis: When the rainfall volume decreases and the hours of sunshine increase so will the diagnostic rate of sexually transmitted infection (STI)s increase due to more socialisation between sexual partners.

Initially I wanted to be comparing UK weather sunshine and rainfall data (Met Office, 2025) comparing it against UK diagnosed sexually transmitted infection (GOV.UK, 2025) to identify a possible correlation.

If identified this data would be useful to UK public health authorities in preventing the spread of STIs. This could allow for targeted public health promotions and more effective advertising opportunities for companies selling contraceptive in line with weather predictions. However, I found the parameters of this investigation to be too vast, as a result I needed to narrow them. 

I narrowed all STIs of all ages to focus of sexually transmitted infections to Chlamydia in people aged 15 to 24 years. I selected Chlamydia as this is the most commonly diagnosed STI in the UK (GOV.UK, 2025).	I narrowed the geographical range of the UK to just England so to match the weather dataset with the Chlamydia diagnoses dataset. The option to use regional data withing England was available however, it is not clear what the exact geographical boundaries of regions are for both datasets for example the boundaries of Midlands and East of England could vary between the datasets.


## Mid-Project Feedback

“This looks amazing. The insights are clear. I love that you figured out how to make multiple plots in the same graph. 

Some minor suggestions: 
* Consider more interactive plot using plotly or modify existing data viz [visualisation] to be more accessible (for visually impaired people for instance).
* Clean up comments and avoid overuse. Only leave relevant comments to explain core structurs of your code. 
* Add some reflections on data collection and cleaning process - for example, what impacts will you get once you throw N/A or null data points? .
* README.md file: modify based on “best practices" https://medium.datadriveninvestor.com/how-to-write-a-good-readme-for-your-data-science-project-on-github-ebb023d4a50e 
* Advanced Practice: can you do other data analysis in addition to data viz [visualisation]? — this requires you to learn more advanced DA [data analytial] skills :)”

As a result of this feedback, I incorporated interactive graphs using Plotly to compare diagnostic rates between the two age groups (15 – 19 and 20 – 24). This allowed for a clear visualisation showing that approximately one-third of diagnoses occur in the 15 – 19 age group, while two-thirds occur in the 20 – 24 age group. These insights suggest that future public health campaigns promoting safe sex could be more effectively targeted towards the latter group.

I also refined my code by reducing excessive comments and ensuring concise, purposeful annotations. Additionally, I included reflective notes within the code on the data collection and cleaning processes. Beyond the code, I updated the README.md file and created a supplementary document providing a more detailed account of the project design process. Moving forward, I am committed to expanding my skill set in data analysis and visualisation, and I am actively working to integrate these enhanced capabilities into my next project.

## Limitations 

Factors that could interfere with the Chlamydia diagnoses data include the Covid-19 pandemic ranging from the years 2020 to 2021. The data sourced states that there 'is notably lower than previous years due to the reconfiguration of sexual health services during the national response to the COVID-19 pandemic.' Other factors that alter Chlamydia diagnostic rate include age, socioeconomic status (Crichton, J. et al., 2015), gender, sexual orientation, sexual behaviour (GOV.UK, 2025).

It is noted that the 'Data presented in relation to gender identity may, or may not, be the same as sex registered at birth. The data total may include people who are gender diverse or those reported with an unknown gender. Therefore, the sum of data for men and women may not equal the data total'(GOV.UK, 2025). To combat this, I will use only the data in the 'Total' rows of the Gender column not the data in the rows labelled 'Male' and 'Female'. 


## Final thoughts

There appears to be no trend with annual rainfall and sunshine in England and the Chlamydia diagnoses of people aged 15 to 24 years in England between 2015 to 2024. 

This could be due to the number of factors that influence Chlamydia diagnostic rates such as age, socioeconomic status (Crichton, J. et al., 2015), gender, sexual orientation, sexual behaviour (GOV.UK, 2025).

A lack of trend identification may also be due to a lack of data points that cannot be seen in annual data and would instead require monthly data. However, this limitation may be overcome if monthly data for Chlamydia diagnoses in people aged 15 to 24 years in England between 2015 to 2024 was available. This could them be compared with the available monthly rainfall and sunshine in England data (Met Office, 2025). A trend may be seen as weather may have an impact on socialising and partaking in more risky sexual behaviour. 

This could still be beneficial information for the UK public health authorities in predicting increases in Chlamydia diagnostic rates using weather forecasts. As a result, public health authorities could implement targeted campaigns to groups most affected by high rates of diagnosed Chlamydia. Also, this information could be useful for companies that sell contraceptives that would be able to improve marketing tactics by using weather forecasts to predict when to boost marketing campaigns.

Proposed hypothesis for future work: When the monthly rainfall volume decreases and the monthly hours of sunshine increase so will the monthly diagnostic rate of Chlamydia increase due to more socialisation between sexual partners.


## References 

Crichton, J. et al. (2015) ‘Socioeconomic factors and other sources of variation in the prevalence of genital chlamydia infections: A systematic review and meta-analysis’, BMC Public Health, 15(1). doi:10.1186/s12889-015-2069-7. 

National chlamydia screening programme (NCSP): annual data (2025) GOV.UK. Available at: https://www.gov.uk/government/statistics/national-chlamydia-screening-programme-ncsp-data-tables (Accessed: 31 July 2025). 

Sexually transmitted infections and screening for Chlamydia in England: 2024 report (2025) GOV.UK. Available at: https://www.gov.uk/government/statistics/sexually-transmitted-infections-stis-annual-data-tables/sexually-transmitted-infections-and-screening-for-chlamydia-in-england-2024-report (Accessed: 31 July 2025). 

Sexually transmitted infections and screening for Chlamydia in England: 2024 report (2005) GOV.UK. Available at: https://www.gov.uk/government/statistics/sexually-transmitted-infections-stis-annual-data-tables/sexually-transmitted-infections-and-screening-for-chlamydia-in-england-2024-report#populations-with-greater-sexual-health-needs (Accessed: 31 July 2025). 

UK and Regional Series (2025) Met Office. Available at: https://www.metoffice.gov.uk/research/climate/maps-and-data/uk-and-regional-series (Accessed: 31 July 2025). 


# UK Housing Market Analysis

## Description
Given my previous experience as a mortgage adviser and the state of the economy being reported on in the UK recently e.g. increasing inflation, increasing interest rates and the 'cost of living crisis', I proposed and undertook the following group project with some colleagues:

Analyse the UK housing market (such as property prices, sales numbers etc) and compare this with UK economic data (such as inflation rate, mortgage interest rates etc) to try and establish any trends or interesting insights.

## Objectives
- Use the skills and technical knowledge learnt in our training at Albany Beck to carry out this assessment i.e. SQL, Excel, Power BI, Python.
- Find credible and publically available sources of raw data as required to perform such an analysis.
- Use agile working practices and tools to co-ordinate, collaborate and complete the project (e.g. Confluence, Jira, Github etc).
- Use ETL techniques on the raw datat to create cleaned datasets in readiness for analysis.
- Consider transforming data into tables for use within an SQL database and having this centrally accessible and maintainable within the cloud.
- After performing analysis on the data, present any interesting trends, insights and rationale within a dashboard and/or Powerpoint presentation.

## Process Undertaken
- Using agile principles, we held regular meetings as a group to discuss, assign and update our progress on tasks with this being recorded and montiored using tools such as the ticketing system in Jira.
- Raw data was collected which included data in .csv (comma separated value) or .xls or .xlsx (Microsoft Excel worksheet) formats. These were gathered from various sources such as UK Land Registry, Bank of England etc - see links to the data sources in the last slide of the powerpoint presentation <a href="https://github.com/davidip86/UK_Housing_Market_Analysis/blob/main/Presentation%20-%20UK%20Housing%20Market.pptx">here</a>.
- ETL techniques including use of Python and Excel were used to transform the raw datasets into clean sets of data in .csv format.
- Cleaned dataset was used to populate tables for a local SQL database (some files included in this repository to demonstrate this) as well as a cloud based SQL database on AWS.
- Datasets were loaded and transformed into visulisations using both Power BI and Excel with observations and insights summarised in a Powerpoint presentation.

## Visualisations & Insights
![Average House Price By Country](https://github.com/davidip86/UK_Housing_Market_Analysis/assets/136905010/e2da7b2a-268f-404a-ae61-700d921315ef)

#### Observations
- Northern Ireland had the highest average house price of all UK countries in Q1 2007 at £204,276.
- From this point Northern Ireland’s average house price continued to fall until it then became the country with the lowest average house price in Q2 2010 and its lowest average figure over this sample period was £105,413 in Q1 2013 – approximately a 49% drop since 2007.
- Northern Ireland's average house price has gradually increased since Q1 2013 however it still remains as the country with the lowest average in the UK at £167,142 as of Q2 2023.

#### Possible explanations
- The global financial crisis that occured in 2007-08 led to a phenomenon coined the 'credit crunch' which brought about tighter lending controls and led to reduced access and availability of mortgage lending. This is likely to have caused more difficulty in buying a home, leading to decreased demand to purchase and hence falling house prices.
- Prior to the financial crisis there was a period of rapid house price growth in all countries of the UK. Some of this growth was driven by speculative investing and the perception that house prices would continue to rise indefinitely. However, as the bubble burst, it led to a correction in house prices as can be seen for a period post 2007.
<br>

![Property Sale Numbers](https://github.com/davidip86/UK_Housing_Market_Analysis/assets/136905010/3c058c28-9e31-4e72-b154-e5a72266bf90)

#### Observations
- Q3 2007 – Q1 2009: Property sale numbers underwent a sustained and substantial reduction from approx 387,000 per quarter down to 103,000 per quarter. 
- Q2 2020 – Q2 2021: Sales numbers increased significantly from approx 116,000 to 323,000 per quarter between Q2 2020 and Q2 2021.  
- Q3 2022 – Q2 2023: Sales numbers have reduced substantially from approx 244,000 to 38,000 per quarter. 

#### Possible explanations
- Q3 2007 – Q1 2009: Most probably due to the effects of the global financial crisis which led to a lack of confidence in banking and housing by the public. This in turn seems to have led to a reduction in average house prices across the UK over a similar period.
- Q2 2020 – Q2 2021: Likely due to the availability of record low mortgage interest rates as well as a government introduced stamp duty holiday between 8th July 2020 and 30th June 2021 meaning there was no stamp duty payable on properties worth up to £500k. This is surprising given COVID-19 which introduced restrictions at the time, however viewings were still allowed and the appetite for people to move home (typically to somewhere larger and more remote) was also strong during this time.
- Q3 2022 – Q2 2023: This is likely due to the current economic circumstances which includes much higher CPIH (Consumer Prices Index, including housing costs) inflation and higher mortgage interest rates.
<br>

![Properties Sold vs Interest Rates](https://github.com/davidip86/UK_Housing_Market_Analysis/assets/136905010/da714f62-c598-4e1d-9ee7-d436a756625d)

#### Observations
- 2012-2014: The number of properties sold can be seen to be significantly increasing from around 2100 per quarter to close to 3000 per quarter.
- Q4 2019 - Q4 2020: A sharp decline in properties sold can be seen from about 2700 per quarter to about 2250 per quarter. 
- Q4 2021 - Q2 2023: A vary sharp decline in the number of properties sold can be seen from about 3000 per quarter to about 1000 per quarter. 

#### Possible explanations
- 2012-2014: Over this period Bank of England's base rate holds at historic lows and inflation as measured by the CPIH rate (Consumer Prices Index including owner occupiers' housing costs) as well as the average mortgage interest rate across housing stock reduces significantly. This combination likely contributes to the consumers feeling more financially secure and increasing the appetite to take on a mortgage and purchase a peoperty hence the increase in properties sold.
- Q4 2019 - Q4 2020: During this period interest rates don't appear to change significantly are are still some of the lowest seen in the graphed period. The drop in sales is likely due to the effects of the COVID-19 pandemic in this period which led to people having more restrictions on their movements, mortgage lenders being more cautious and restrictive with lending due to people being placed on furlough at the time and the legal process to complete a property transaction taking much longer than usual due to many people having to work from home.
- Q4 2021 - Q2 2023: As can be seen the UK is experiencing large rises in interest rates and in particular inflation. There has been a knock on effect with the Bank of England increasing the base rate many times over this period and this then being passed on by mortgage lenders as can be seen my the average mortgage interest rate increasing too. All of this has combined and the UK is within the midst of a 'cost of living' crisis therefore this has almost certainly led to the sharp decrease in the number of properties sold.

### UK Housing Market Prediction 
Based on the current dataset, average UK property prices are still on a slight upward trajectory however as can be seen in graph above the numbers of properties sold has sharply reduced. With a sharp decrease in demand it's reasonable to expect that average UK property values may experience a decrease similar to the period after the global financial crisis in 2007-08. 



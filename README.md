# Phoenix Data Analysis / Dashboard

## Introduction
- This project was inspired after reading this [article](https://www.phoenix.gov/newsroom/housing/1409), which details govermental reforms to address the housing shortage in Phoenix.  
- The article details how the rent of an 2-bedroom apartment requires an hourly wage of $21, which is $9 above the minimum wages
- So, to get a more broader perspective, I decided to look at demographic changes in Phoenix throughout this past decade.

## Dataset
 - I explored US Census Bureau data on Phoenix. The datasets span from demographics, economics, and housing data from 2008-2019. The datasets can be found [here](https://www.phoenixopendata.com/organization/external-data).
    - The original datasets can be found in `data/original`
    - The modified datasets can be found in `data/cleaned`
- All analysis and graphics were conducted using R.
    - There is both a pdf version of the Rmd file in the main directory and the original Rmd file under `code`
- Additionally, I compiled my results in a dashboard, which can be accessed [here](https://rpubs.com/mkato124/963718)
    - The code for this dashboard is also under `code`

## Finding
- The median income increased from $50,140-$60,931, while the median gross rent has increased from $876-$1107 in this past decade
    - To put this into perspective, the US median is $69,560 in 2019 ([source](https://www.census.gov/library/publications/2021/demo/p60-273.htm))
    - Based on inflation rates alone, income should have increased to $60,990.60 and gross rent should have increased to $1,065.57. (calculated using the Bureau's CRI calculator [source](https://www.bls.gov/data/inflation_calculator.htm))
    - This means that income has barely keeped up with inflation, while rent is increasing beyond inflation.
- Occupied housing units have increased by 18%, while vacancy rates have decreased by 40%
    - Specifically, occupied units have increased by 92,980, while vacant units have decreased by 32,792
    - Additionally, the total housings unit have increased by 60,188
- Concerning education, there are increases across multiple degrees (Bachelor, associate, masters, GED)
- The age demographic is relatively stable in this past decade with a slight increase in the older generations.
- Poverty levels have also dropped with more people above the poverty line and less below the poverty line.

## Conclusion
- Overall, the demographic data sugget signs of increasing buyer demands and decreasing supply
- For buyer demands:
    - more houses are occupied despite stagnant income
    - generally, Phoenix is becoming more prosperous (higher education, lower poverty), which may lead to more people willing to buy homes
- For lower supply:
    - Although the vacancy rate as of 2019 (7.9%) is not low, the trend is definitely concerning 


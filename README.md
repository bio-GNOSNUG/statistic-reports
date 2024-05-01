# statistic-reports
Example statistical reports developed during MSc Data Science and Artificial Intelligence studies

## Analysis of Texas bridges
Demonstrating exploratory analysis and use of regression modelling to look at the effect of predictor variables on a target variable.

Data sourced from the US National Bridge Inspection, collated by the Federal Highways Agency (FHWA) and can be found in the [National Bridge Inspection](https://www.fhwa.dot.gov/bridge/nbi/ascii.cfm) section of the FHWA's web site. For the purpose of this report, we focus on the state of Texas, USA, on a subset of columns of interest to our analysis. Predominantly, the columns below:

| Variable      |      Description             | Type | 
|:--------------|:-----------------------------|:------:|
|Year           | The year the bridge was built                             | continuous | 
|AverageDaily   | The average daily traffic (number of vehicles)            | continuous |
|Trucks_percent | The percent of traffic made up of 'trucks' (i.e. lorries) | continuous |
|Material       | The dominant material the bridge is made from             | category |
|Design         | The design of the bridge                                  | category |
|Deck_rating    | The condition of the deck of the bridge                   | ordinal |
|Superstr_rating| The condition of the bridge superstructure                | ordinal |
|Substr_rating  | The condition of the bridge substructure (foundations)    | ordinal |

## Exploring changes in UK property price

Using data and statistical analysis to understand more about changes in property prices across regions of the UK.

The dataset used in this report is of the average price of properties over 36 months, from September 2016 to September 2019 in different areas of the UK. There are four different types of property listed: 'Detached', 'Semi', 'Terraced' and 'Flat'. Our analysis will focus on 'Detached' and 'Flat' data to identify patterns in property prices across regions, time and property type. 

The file `average-property-price.csv` contains information about the average price of properties (including detached, semi-detached, terraced, and flat) over 36 months in different areas of the UK.

| Field     | Description                                               |
|-----------|-----------------------------------------------------------|
| Name      | - Date <br> - Description                                 |
| Date      | A date, which is the first of the month, between September 1st, 2016 and August 1st, 2019. 36 months in total. |
| Area      | - The name of an area (or region). <br> - The code for the area (or region). |
| Code      | Unique identifier for the area.                           |
| Detached  | Average sale price of a detached property in this area in the month. |
| Semi      | Average sale price of a semi-detached property in this area in the month. |
| Terraced  | Average sale price of a terraced property in this area in the month. |
| Flat      | Average sale price of a flat property in this area in the month. |

## Statistical association of storks and births 

Investigating the hypothesis that storks deliver babies whilst gaining an understanding of the different socioeconomic and geoographic factors that may influence birth rate and its statistical association with storks. 

Data used in the analysis of this report has been taken from the paper 'Storks Deliver Babies (p = 0.008)' by Robert Matthews (2000) [1]. It includes information on the area (in km<sup>2</sup>), stork pair number, humans (10<sup>6</sup>) and birth rate (10<sup>3</sup>/year) for 17 European countries. Demographic information was sourced from the Britannica Yearbook for 1990 and stork breeding pair data directly from Chris Harbard of the Royal Society for the Protection of Birds. 

Additionally, a column has been incorporated into the dataset to include GDP per capita ($) for each of the 17 countries.

**Citation:**
Matthews, R. (2000). *Storks Deliver Babies (p = 0.008)*. Teaching statistics 22(2). Wiley: 36–38. https://doi.org/10.1111/1467-9639.00013



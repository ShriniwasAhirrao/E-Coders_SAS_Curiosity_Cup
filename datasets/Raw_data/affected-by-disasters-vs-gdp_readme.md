# People affected by disasters vs. GDP per capita - Data package

This data package contains the data that powers the chart ["People affected by disasters vs. GDP per capita"](https://ourworldindata.org/grapher/affected-by-disasters-vs-gdp?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Annual rate of people affected from all disasters excluding extreme temperatures – EM-DAT
Rate of people per 100,000 affected by a natural disaster.
Last updated: April 11, 2024  
Next update: April 2025  
Date range: 1900–2024  
Unit: affected per 100,000 people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
EM-DAT, CRED / UCLouvain (2024); Population based on various sources (2023) – with major processing by Our World in Data

#### Full citation
EM-DAT, CRED / UCLouvain (2024); Population based on various sources (2023) – with major processing by Our World in Data. “Annual rate of people affected from all disasters excluding extreme temperatures – EM-DAT” [dataset]. EM-DAT, CRED / UCLouvain, “Natural disasters”; Various sources, “Population” [original data].
Source: EM-DAT, CRED / UCLouvain (2024), Population based on various sources (2023) – with major processing by Our World In Data

### What you should know about this data
* EM-DAT counts injured as people with physical injuries, trauma, or illness requiring immediate medical assistance due to the disaster.
* Affected people are those requiring immediate assistance due to the disaster.
* EM-DAT counts homeless as people requiring shelter due to their house being destroyed or heavily damaged during the disaster.
* The total number of affected people is the sum of those injured, affected, and left homeless after a disaster.
* EM-DAT defines a disaster as a situation or event which overwhelms local capacity, necessitating a request to the national or international level for external assistance; an unforeseen and often sudden event that causes great damage, destruction, and human suffering. Of all EM-DAT disasters, we select geophysical, meteorological, hydrological, and climatological events, which include droughts, earthquakes, extreme temperatures, floods, glacial lake outburst floods, mass movements, extreme weather events, volcanic activity, and wildfires.
* Drought is defined as an extended period of unusually low precipitation that produces a shortage of water for people, animals, and plants. Drought is different from most other hazards in that it develops slowly, sometimes even over the years, and its onset is generally difficult to detect.
* An earthquake is defined as a sudden movement of a block of the Earth's crust along a geological fault and associated ground shaking. The data includes the impacts of earthquake events, aftershocks and tsunamis.
* Extreme temperature is used as a general term for temperature variations above (extreme heat) or below (extreme cold) normal conditions.
* Extreme weather events include tornadoes, hailstorms, thunderstorms, sandstorms, blizzards, and extreme wind events.
* Flood is used as a general term for the overflow of water from a stream channel onto normally dry land in the floodplain (riverine flooding), higher-than-normal levels along the coast (coastal flooding) and in lakes or reservoirs as well as ponding of water at or near the point where the rain fell (flash floods).
* Volcanic activity is defined as any type of volcanic event near an opening/vent in the Earth's surface including volcanic eruptions of lava, ash, hot vapor, gas, and pyroclastic material.
* A wildfire is defined as any uncontrolled and non-prescribed combustion or burning of plants in a natural setting such as a forest, grassland, brush land or tundra, which consumes natural fuels and spreads based on environmental conditions (e.g., wind, or topography). Wildfires can be triggered by lightning or human actions.
* A dry mass movement is defined as any type of downslope movement of earth materials under hydrological dry conditions.
* A wet mass movement is defined as a type of mass movement that occur when heavy rain or rapid snow/ice melt send large amounts of vegetation, mud, or rock down a slope driven by gravitational forces.
* Glacial lake outburst floods are defined as those that occur when water held back by a glacier or moraine is suddenly released. Glacial lakes can be at the front of the glacier (marginal lake) or below the ice sheet (sub-glacial lake).
* Fog is defined as water droplets that are suspended in the air near the Earth's surface. Fog is simply a cloud that is in contact with the ground. Currently, the only fog disaster recorded in EM-DAT is the Great Smog of London in 1952.

### Sources

#### EM-DAT, CRED / UCLouvain – Natural disasters
Retrieved on: 2024-04-11  
Retrieved from: https://emdat.be/  

#### Various sources – Population
Retrieved on: 2023-03-31  
Retrieved from: https://ourworldindata.org/population-sources  


## GDP per capita – In constant international-$ – World Bank
Average economic output per person in a country or region per year. This data is adjusted for inflation and for differences in living costs between countries.
Last updated: January 24, 2025  
Next update: January 2026  
Date range: 1990–2023  
Unit: international-$ in 2021 prices  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Data compiled from multiple sources by World Bank (2025) – with minor processing by Our World in Data

#### Full citation
Data compiled from multiple sources by World Bank (2025) – with minor processing by Our World in Data. “GDP per capita – World Bank – In constant international-$” [dataset]. Data compiled from multiple sources by World Bank, “World Development Indicators” [original data].
Source: Data compiled from multiple sources by World Bank (2025) – with minor processing by Our World In Data

### What you should know about this data
* Gross domestic product (GDP) is a measure of the total value added from the production of goods and services in a country or region each year. GDP per capita is GDP divided by population.
* This GDP per capita indicator provides information on economic growth and income levels from 1990.
* This data is adjusted for inflation and for differences in living costs between countries.
* This data is expressed in [international-$](#dod:int_dollar_abbreviation) at 2021 prices.
* For GDP per capita estimates in the long run, explore the [Maddison Project Database's indicator](https://ourworldindata.org/grapher/gdp-per-capita-maddison).

### How is this data described by its producer - Data compiled from multiple sources by World Bank (2025)?
GDP per capita based on purchasing power parity (PPP). PPP GDP is gross domestic product converted to international dollars using purchasing power parity rates. An international dollar has the same purchasing power over GDP as the U.S. dollar has in the United States. GDP at purchaser's prices is the sum of gross value added by all resident producers in the country plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant 2021 international dollars.

Statistical concept and methodology: For the concept and methodology of PPP, please refer to the International Comparison Program (ICP)’s website (https://www.worldbank.org/en/programs/icp).

### Source

#### Data compiled from multiple sources by World Bank – World Development Indicators
Retrieved on: 2025-01-24  
Retrieved from: https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators  


## World regions according to OWID
Last updated: January 1, 2023  
Date range: 2023–2023  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Our World in Data – processed by Our World in Data

#### Full citation
Our World in Data – processed by Our World in Data. “World regions according to OWID” [dataset]. Our World in Data, “Regions” [original data].
Source: Our World in Data

### What you should know about this data

### Source

#### Our World in Data – Regions


    
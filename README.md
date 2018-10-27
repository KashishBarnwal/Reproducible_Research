# Reproducible_Research
## By : Praveen kumar

# Impact of Severe Weather Events on Public Health and Economy in the United States
## Synonpsis

In this report, we aim to analyze the impact of different weather events on public health and economy based on the storm database collected from the U.S. National Oceanic and Atmospheric Administration’s (NOAA) from 1950 - 2011.

We will use the estimates of fatalities, injuries, property and crop damage to decide which types of event are most harmful to the population health and economy. From these data, we found that excessive heat and tornado are most harmful with respect to population health, while flood, drought, and hurricane/typhoon have the greatest economic consequences.

## Data Preprocessing and approch
- The dataset(available at [this link](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2)) consists of 902297x37 rows and columns.
- We trim the dataset according the question for which we need to do analysis and produce the expected outcome. This also helps us in triming the dataset to lower dimensions.
- Question 1: What are the total number of FATALITIES and INJURY caused by severe weather ?
- Question 2: Which weather event causes maximum ECONOMIC(Property & Crop) damage ?
- We plot the filtered data and process it & produce ggplots. Then analyse the result and then conclude the Hazardous events to answer the questions.

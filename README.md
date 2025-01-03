# New-Zealand-Crash-Analysis-System-CAS-Analysis
NZ Crash Analysis system contains data about all crashes reported to NZTA by the NZ police from 2000-2021.

Data downloaded through NZTA website
link: https://opendata-nzta.opendata.arcgis.com/datasets/NZTA::crash-analysis-system-cas-data-1/about

Uploaded Data using Kaggle API due to large file size.
Cleaned data using Python Pandas library. 
Cleaned table uploaded to BigQuery and analysis done through SQL BigQuery API and through Pandas.

**Summary and Insights**

Most crashes occured in the Auckland, Canterbury and Waikato Region note: 3084 crashes had unknown regions

Most injuries and fatalities followed the same trend as overall accidents. When accidents were at an all time high, so were injuries and fatalities. 
(Note: the number of accidents being much lower in 2021 may be due to incomplete data, so that number won't be taken into consideration).

In West coast, Northland and Waikato, around 2% of all crashes were fatal.

A sigificant amount of crashes occured at giveway sings (143645), then traffic signals (79555) and stop signs (49080).

2.5% of all crashes occured on Christmas and New years day. Around 1% of crashes occured on each Easter, Labour weekend and Queen's birthday.

The largest proportion of vehicles involved in both fatal/serious crashes and in general crashes were cars and station wagons.

The largest number of crashes occured within 50-100kmp/h areas, with the most crashes occuring on 50km/h roadsm and within 2-5 lanes.

Most fatal crashes occur in 100km/h areas.

644500 crashes occured on flat roads and 157225 occured on hilly roads.


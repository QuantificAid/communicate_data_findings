# Challenges of a Bike Sharing Business Model
## by Caspar Heidbrink

***Communicate Data Findings***
***A Project in Course of Udacity's Data Analyst Nanodegree Program***


## Dataset

- Data on **bike-sharing from baywheels** by Lyft for San Francisco, East Bay and San Jose
- Offer: bikes from docks/stations (also some dockless in San Jose)
- **3.6 million recorded trips** over the last **two years/24 months** (July 2017 to June 2019)
- Each dataset comprises information about **users** (having a subscription, gender, age), **time and duration** of the trip and start and end **location**

## Summary of Findings

Findings from univariate exploration:

- Most users are subscribers, but it was worthwhile to investigate on different user patterns.
- The general growth was impacted by a downturn in May/June 2019. This should was further investigated.
- Latitude and longitude can be used to create maps and to identify areas.  

Findings from bivariate exploration:

- Non-subscribers show a more homogenous pattern of usage during the day and tend to use the bikes longer.
- Whilst usage of both, subscribers and non-subscribers, dropped in May 2019, only non-subscribers bounced back in June.
- There are three operating areas, San Francisco, East Bay and San Jose, with San Francisco being the most significant one. 

Findings from multivariate exploration:  

- The drop in trips in San Francisco and East Bay in May 2019 also stays on in June 2019, whilst (more growing, but overall least significant) San Jose could recover.
- Bounce back from drop in May 2019 was partly driven by non-subscribers.
- There are stations in San Francisco and East bay that - although traffic is "breathing" - have an overall net-gain/-loss (which drives the need for actively relocating the bikes by baywheels)


## Key Insights for Presentation

- **Growth pattern influenced by the current challenges** regarding the law suit with the Bay's Metropolitan Transportation Commission as well as the deployment of ebikes.
- **Patterns of bike usage** by different user types **and opportunities to improve utilization**.
- **Need for actively managing localization** of the bikes (for docks in San Francisco and East Bay)

### Licence/Rights
The outline of the notebook have been provided by Udacity and the data is publicly available on from [baywheels](https://www.lyft.com/bikes/bay-wheels/system-data), whilst the answers to the questions and the code necessary to answer the questions have been created by the author.

### Setup
In order to run the notebook, you'll need to install:

Python 3.6
Jupyter (notebook or lab)
Pandas
Numpy
Matplotlib
Seaborn

This notebook will not be maintained.


# CSDA 1050


# CSDA 1050 - Final

## The Socioeconimics of Pedestrian Accidents
This project looks at the relationship between the average socioeconomic status of a toronto neighbourhood and the likelihood of a pedestrian being involved in a motor vehicle accident in that neighbourhood.

## Motivation
Every year pedestrians and transit users in the city of Toronto continue to be involved in motor vehicle collisions. Although the city continues to employ multiple methods to improve road safety for these users, the idea that inequality and safety are tied to the socioeconomic status of an area is prevalent. The purpose of this project is to study the relationship between a person’s socioeconomic status and their likelihood to be involved in a pedestrian – motor vehicle accident. This information can then be leveraged in determining locations where road safety improvements will have the biggest impact in lowering this socioeconomic inequality in the city of Toronto.

## Review
There are a number of papers and studies that have drawn the link between socioeconomic status and
the likelihood of being involved in a vehicular accident. These studies have often either taken a much broader approach to the impact of socioeconomics on vehicular accidents by looking at all accidents or have focused on a much narrower subset of data while pulling additional variables such as subset of pedestrian accidents been much more focused taking into account the prevalence of road features in each socioeconomic differed based on socioeconomics of the area and its impact on child safety.

## Build status
Build Complete
This project was completed following an Agile methodology.
There are 4 folder each containing slightly different data.

- Sprint 1 - contains all files, data sets and products created/used in Sprint 1

- Sprint 2 - contains all files, data sets and products created/used in Sprint 2

- Sprint 3 - contains all files, data sets and products created/used in Sprint 3

- Final - contains final versions of the markdown file, research paper, and guided presentation.

## Tech/framework used

<b>Built with</b>
- [RStudio](https://www.rstudio.com/)

## Data Sources
There are 5 main data sources.

[KSI Pedestrian Dataset](https://data.torontopolice.on.ca/datasets/pedestrians)

[KSI TTC/Municipal Vehicle Dataset](https://data.torontopolice.on.ca/datasets/ttc-municipal-vehicle)

[Simply Analytics - 2016 Census Tract](https://github.com/JacobGvs/CSDA-1050F18S1/tree/master/jacobgvs_304292/final/Datasets/SimplyAnalytics_C1)

[Simply Analytics - 2016 Dissemination Area](https://github.com/JacobGvs/CSDA-1050F18S1/tree/master/jacobgvs_304292/final/Datasets/SimplyAnalytics_C2)

[City of Toronto Neighbourhoods](https://open.toronto.ca/dataset/neighbourhoods/)


## Screenshots

![Accidents per Year by Average Income](https://github.com/JacobGvs/CSDA-1050F18S1/blob/master/jacobgvs_304292/final/Average%20Accidents%20by%20income%20yearly.PNG)

![Average Income by District](https://github.com/JacobGvs/CSDA-1050F18S1/blob/master/jacobgvs_304292/final/Income_by_District.PNG)

![Driver Influence by Average Income by Vehicle Action](https://github.com/JacobGvs/CSDA-1050F18S1/blob/master/jacobgvs_304292/final/Influence_by_Income_by_VehAction.PNG)

![Accident location by Average Income and Driver Influence](https://github.com/JacobGvs/CSDA-1050F18S1/blob/master/jacobgvs_304292/final/AccLoc_Income_DriverInfl.PNG)

## Installation
To intall this project you will need to download and opend the "Socioeconomics.Rmd" file.

You will also need to download the "/Datasets" folder. This needs to be saved to the same folder as the "Socioeconomics.Rmd" and contains the information downloaded from Simply Analytics.

To run the code, open the "Socioeconomics.Rmd" file in RStuio and select to run all chunks.

The code is written in such a way that it should automatically read all necessary files.

The "Socioeconomis.nb.html" file contains a preview of the results of running the provided code if you do not have Rstudio installed

## Results and Findings
- The overall number of pedestrian accidents in toronto does not fluctuate widely year over year

- Pedestrian accidents occur in the same district at approximately the same proportion year over year

- Pedestrians are still most likely to be involved in an accident in an area with average household income between 60k and 90k

- When an acciddent occurs at an intersection:
    - If the driver is driving aggressively, pedestrians are most likely to be hit while crossing at an intersection when they have the right of way because the driver is turning instead of proceeding through the intersection.
    - If the driver is under no influence, pedestrians are most likely to be hit while crossing at intersections where there is no traffic control or while crossing at intersections when they do not have the right of way and the driver is proceeding through the intersection
    -  If the driver is speeding, pedestrians are most likely to be hit while walking on the sidewalk or shoulder of the street and is struck or while crossing an intersection with or without the right of way and the driver is proceeding through the intersection.
    
- When an acciddent does not occur at an intersection: 
    - The impact speeding and aggressive driving on overall accident frequency is significantly diminished

- The data confirms that pedestrians walking in an area with a lower to mid average household income are at a higher risk of being involved in a motor-vehicle accident than if they were walking in an area with a higher average household income.

- There insufficient evidence in the data available to definitely identify average household income as the reason for this increased in risk.


[Jacob Geeves](https://github.com/JacobGvs)
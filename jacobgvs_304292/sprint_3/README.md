
# csda 1050


# CSDA 1050 - Sprint 2

## The link between Socioeconimics and pedestrian accidents
This project looks at the relationship between a person’s socioeconomic status and their likelihood to be involved in a pedestrian – motor vehicle accident in the city of Toronto.

## Motivation
Every year pedestrians and transit users in the city of Toronto continue to be involved in motor vehicle collisions. Although the city continues to employ multiple methods to improve road safety for these users, the idea that inequality and safety are tied to the socioeconomic status of an area is prevalent. The purpose of this project is to study the relationship between a person’s socioeconomic status and their likelihood to be involved in a pedestrian – motor vehicle accident. This information can then be leveraged in determining locations where road safety improvements will have the biggest impact in lowering this socioeconomic inequality in the city of Toronto.

## Review
There are a number of papers and studies that have drawn the link between socioeconomic status and
the likelihood of being involved in a vehicular accident. These studies have often either taken a much broader approach to the impact of socioeconomics on vehicular accidents by looking at all accidents or have focused on a much narrower subset of data while pulling additional variables such as subset of pedestrian accidents been much more focused taking into account the prevalence of road features in each socioeconomic differed based on socioeconomics of the area and its impact on child safety.

## Build status
Sprint 2 continues the data discovery phase of the project and moves into data manipulation and evaluation phases.
In this sprint we looked at:
- Spatial geometric manipulation    - using the "sf" package to manipulate and associate spatial polygons
- Spatial data manipulation         - using the "spatialEco" package to join spatial dataframes
- Spatial data modeling             - using the "spatialEco" package to correlate, cluster, and evaluate the data

A final copy of the project will be available in the "final" folder once the project has been completed.

## Tech/framework used

<b>Built with</b>
- [RStudio](https://www.rstudio.com/)

## Data Sources
All data sources are outlined in the sprint 1 and final README files.

There are 5 main data sources that will be used.

[Sprint 1 Link](https://github.com/JacobGvs/CSDA-1050F18S1/tree/master/jacobgvs_304292/sprint_1)

## Screenshots
The spatialEco package allowed us to identify if a spatial data point was within a polygon and automatically leftjoin the applicable polygon data to our SpatialPointsDataframe. 

![Associating Data with the spatialEco package](https://github.com/JacobGvs/CSDA-1050F18S1/blob/master/jacobgvs_304292/sprint_2/AssociatingDatasets.PNG)

This allowed us to begin reviewing the dataset and its relation to the average income of a census tract.

![Household Average Income Histogram](https://github.com/JacobGvs/CSDA-1050F18S1/blob/master/jacobgvs_304292/sprint_2/Income_histogram.PNG)

We were also able to begin joining all the variables together into one map.

![Leaflet Mapping - Neighbourhood, census tract, and dissemination area options](https://github.com/JacobGvs/CSDA-1050F18S1/blob/master/jacobgvs_304292/sprint_2/ksi_polygon_mapping.PNG)

![Leaflet Mapping - Data Point Labels](https://github.com/JacobGvs/CSDA-1050F18S1/blob/master/jacobgvs_304292/sprint_2/ksi_polygon_label.PNG)

## Installation
To intall this project you will need to download and opend the "Socioeconomics.Rmd" file.

You will also need to download the "/Datasets" folder. This needs to be saved to the same folder as the "Socioeconomics.Rmd" and contains the information downloaded from Simply Analytics.

To run the code, open the "Socioeconomics.Rmd" file in RStuio and select to run all chunks.

The code is written in such a way that it should automatically read all necessary files.

The "Socioeconomis.nb.html" file contains a preview of the results of running the provided code if you do not have Rstudio installed

## Results and Findings
- Discovered that some of the assumptions for next steps from Sprint 1 were incorrect. Specifically that in Rstudio there does not appear to be a need to reproject spatial data stored in a Lat/Long configuration into CSR inorder to associate them one to another.
- Unfortunately the discovery above is not well explained anywhere and it took multiple different attempts of various different ways to associate spatial data points to spatial data polygons before i was able to find a method that actually worked and maintained the geometry data that was required to generate the polygons.
- Although leaflet is a powerful package that makes mapping of spatial data very simple it appears some of the features that are used to cluster points based on the polygon they are associated to may not exist in Rstudio.

## Next Steps
- Establish income bandwiths and associate back to main datatable.
- Continue with frequency review and comparison of various variables that was only possible once they could be compared to household average income.
- Further work will be needed to review the clustering on the dataset. Currently clusters are unreadable due in part to the large variations in income data. thsi shoudl be improved once income can be placed into bandwiths.
- Review how to bind markers in leaflet to their polygon(s). Currently unclear if this feature is available in Rstudio or only available using the leaflet code html or leaflet in python.
- Continue working with the spatialEco package to model the datasets.


[Jacob Geeves](https://github.com/JacobGvs)
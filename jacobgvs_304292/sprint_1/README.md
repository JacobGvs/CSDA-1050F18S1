
## CSDA 1050 - Sprint 1

## The link between Socioeconimics and pedestrian accidents
This project looks at the relationship between a person’s socioeconomic status and their likelihood to be involved in a pedestrian – motor vehicle accident in the city of Toronto.

## Motivation
Every year pedestrians and transit users in the city of Toronto continue to be involved in motor vehicle collisions. Although the city continues to employ multiple methods to improve road safety for these users, the idea that inequality and safety are tied to the socioeconomic status of an area is prevalent. The purpose of this project is to study the relationship between a person’s socioeconomic status and their likelihood to be involved in a pedestrian – motor vehicle accident. This information can then be leveraged in determining locations where road safety improvements will have the biggest impact in lowering this socioeconomic inequality in the city of Toronto.

## Build status
Sprint 1 represents the data aquisition and discovery phase of the project.
A final copy of the project will be available in the "final" folder once the project has been completed.

[![Build Status](https://travis-ci.org/akashnimare/foco.svg?branch=master)](https://travis-ci.org/akashnimare/foco)
[![Windows Build Status](https://ci.appveyor.com/api/projects/status/github/akashnimare/foco?branch=master&svg=true)](https://ci.appveyor.com/project/akashnimare/foco/branch/master)

## Screenshots
Include logo/demo screenshot etc.

## Tech/framework used

<b>Built with</b>
- [RStudio](https://www.rstudio.com/)

## Review
There are a number of papers and studies that have drawn the link between socioeconomic status and
the likelihood of being involved in a vehicular accident. These studies have often either taken a much broader approach to the impact of socioeconomics on vehicular accidents by looking at all accidents or have focused on a much narrower subset of data while pulling additional variables such as subset of pedestrian accidents been much more focused taking into account the prevalence of road features in each socioeconomic differed based on socioeconomics of the area and its impact on child safety.

## Data Sources
There are 2 main data sources that will be used.
[KSI Pedestrian Dataset](https://data.torontopolice.on.ca/datasets/pedestrians)
[KSI TTC/Municipal Vehicle Dataset](https://data.torontopolice.on.ca/datasets/ttc-municipal-vehicle)
[Simply Analytics - 2016 Census Tract](https://github.com/JacobGvs/CSDA-1050F18S1/tree/master/jacobgvs_304292/final/Datasets/SimplyAnalytics_C1)
[Simply Analytics - 2016 Dissemination Area](https://github.com/JacobGvs/CSDA-1050F18S1/tree/master/jacobgvs_304292/final/Datasets/SimplyAnalytics_C2)
[City of Toronto Neighbourhoods](https://open.toronto.ca/dataset/neighbourhoods/)

## Code Example
Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Installation
To intall this project you will need to download and opend the "Socioeconomics.Rmd" file.

You will also need to download the "final/Datasets" folder housed in the final folder in the github. This needs to be saved to the same folder as the "Socioeconomics.Rmd".

To run the code, open the "Socioeconomics.Rmd" file in RStuio and select to run all chunks.

The code is written in such a way that it should automatically read all necessary files.

The "Socioeconomis.nb.html" file contains a preview of the results of running the provided code if you do not have Rstudio installed

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests
Describe and show how to run the tests with code examples.

#### Results and Findings
- All data sets have been obtained and one additional dataset has been identified that may be required to facilitate clustering views.
- I had anticipated that the census data would group economic results at neighbpouhood level and that is not the case.
- I have identified most if not all the necessary data sets and succesfully mapped the spatial coordinates and polygons.
- I have identified a package that makes the mapping and review of spatial data relatively easy.

#### Next Steps
- Spatial data needs to be modified form a Lat/Long configuration to CSR
- All accients need to be associated to a census dissemination area, census tract, and city neighbourhood polygon.
- We will need to see if there is any corrolation between average income in a given area and frequency of accidents.


[Jacob Geeves](https://github.com/JacobGvs)



##### Results and Findings:
  - All data sets have been obtained and one additional dataset has been identified that may be required to facilitate clustering views.
  - I had anticipated that the census data would group economic results at neighbpouhood level and that is not the case.
  - I have identified most if not all the necessary data sets and succesfully mapped the spatial coordinates and polygons.
  - I have identified a package that makes the mapping and review of spatial data relatively easy.




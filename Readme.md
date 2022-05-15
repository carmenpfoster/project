# Proposal for Semester Project

**Patterns & Trends in Environmental Data / Computational Movement
Analysis Geo 880**

| Semester:      | FS22                              |
|----------------|---------------------------------- |
| **Data:**      | Wild Boar Movement Data           |
| **Title:**     | The influence of temperature and precipitation on the movement and use of habitat of wild boar in Switzerland         |
| **Student 1:** | Carmen Pfoster               |
| **Student 2:** | Vibiga Vinotharajah                |

## Abstract 
An important factor, which affects environmental conditions of animals, is weather. A few studies show that wild boar decrease their movement at low temperatures and increase their movement in late summer. Thus, this project will analyse the connection between weather and wild boar movement, to reassure that there are effects of weather on wild boar movement. 

## Research Questions
Our aim in this project is to find out if the weather effects the wild boar movement and model the effects of weather. In addition, we want to present these effects and differences. Therefore our research question is as following:
Is there a seasonal difference in the wild boar moving pattern (clustering vs moving but also regarding the location and properties of their habitat)?


## Results / products
As a few studies already found out with their wild boar movement data, we expect that weather affects the wild boar movement (Thurjfell et al. 2014; Lemel, 1999; Morelle et al. 2015). These effects are dependent on time and season of day (Thurjfell, 2014: 470). Possibly, the visualization will show the difference between summer and winter. Overall wild boar tend to increase their movement speed with high temperatures. 

## Data
We will use the provided wild boar movement data. Additionally, we will use/need weather data from the study area from wild boar movement data. We have already asked Nils if this is possible. He reassured that, there is a possibility to get those weather data. But firstly, he has to prepare those data so that it can be used. Additionally the Arealstatistik will be used to see whether the use of space changes with the weather.

## Analytical concepts

<!-- Which analytical concepts will you use? What conceptual movement spaces and respective modelling approaches of trajectories will you be using? What additional spatial analysis methods will you be using? -->
We will mostly use descriptive analytics, because our data and our research question is in the past. We want to see what has happened. Therefore, descriptive concepts will be suitable.
We will model our space as a 2D Euclidean space.The wild boar are free to move and the only obstacles they have are mostly buildings. Our space can be modeled with the filed or entity conceptual model.The trajectories from wild boars will be modeled as straight line connectors between the time-stamped locations.The 3D space can be used in our project, but depending our research question, we prefer 2D space.What other spatial analysis methods we will be using, is still unclear for us.

## R concepts
<!-- Which R concepts, functions, packages will you mainly use. What additional spatial analysis methods will you be using? -->We think that we mainly will use dplyr, tidyverse, sf, lubridate. For the homerange analysis, a suitable package would be "adehabitatHR". Depending on how the weather data is structured some additional packages might be applied.


## Risk analysis
<!-- What could be the biggest challenges/problems you might face? What is your plan B? -->
We don't know how the weather data is, how we have to clean it up and how we can combine it with our wild boar data. If it is possible, we want to make different kind of comparisons. For example, wild boar movement in winter vs. summer, the difference in movement by precipitation. But again depending on the weather data, we need to find out what all we can do.
If the weather data is not suitable, we have to find other weather data.

## Questions? 
If there are weather data for our project and if it is available and suitable? How it is set up (is it usable)?
Do we need any other R packages and if our plan is okay?

## References
Lemel, J., Truve, J.& Soderberg, B. (2003): Variation in ranging and activity behaviour of European wild boar Sus scrofa in Sweden. Wildl Biol 9, 29–36.Mammal Review, 45, 15-29.

Morelle, K. Podgroski, T., Prévot, C., Keuling, O., Lehaire, F. & Leheune, P. (2014): Towards understanding wild boar Sus scrofa movement: a synthetic movement ecology approach. 

Thurfjell, H., Spong, G.& Ericsson, G. (2014): Effects of weather, season, and daylight on female wild boar movement. Acta Theriol, 59, 467-472.

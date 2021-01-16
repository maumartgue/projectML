# projectML
Note: this is a project for ML

The primary goal of this project is to maximize the power energy produced in given period of any wind power engine. The power energy produced is a convolution of the probability distribution of wind speed at a given location with the power curve of the wind turbine.
The probability distribution of wind speed is the most uncertain function since it depends on the location. In order to determine this probability distribution one needs to calculate it as a function of the wind speed by making use of the recently Global Wind Atlas [1]. Using these data, I plan to generate a three-dimensional curve fitting by considering the Kernel Density Estimation (KDE) technique. This non-parametric method provides an accurate description of the probability distribution and thus, it is one of the most technical features of this project. For the power curve I will simply considering the ideal wind turbine which depends on the cut-in, cut-off and rated speeds as well as the rated power. In this case it is enough to consider the generic parameters indicated by the New York Wind Energy Guide for Local Decision Makers [2]. 

[1]. The information regarding the average wind speed can be found in this link: https://globalwindatlas.info/area/United%20States%20of%20America/North%20Carolina
[2]. See https://www.nyserda.ny.gov/All-Programs/Programs/Clean-Energy-Siting/Wind-Guidebook


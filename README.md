===========================================================================
# An Analytical Approach to Meteorological Database
The National Solar Radiation Database (NSRDB) is a serially complete collection of hourly and half-hourly values of meteorological data and the three most common measurements of solar radiation: global horizontal, direct normal, and diffuse horizontal irradiance.

It covers the United States and a growing subset of international locations. These data have been collected at a sufficient number of locations and temporal and spatial scales to accurately represent regional solar radiation climates. For a given location covered by the dataset, it is possible to see the amount of solar energy that was at a given time and to predict the potential future availability of solar energy based on past conditions.

</br></br>

![alt text](https://github.com/shahriar-rahman/Analytics-NSRDB-Meteorological-Data/blob/main/img/nsrdb_img1.jpg)

</br></br>

### ◘ Introduction
Typical Meteorological Year (TMY) is a widely used type of data available through the NSRDB. TMYs contain one year of hourly data that best represents median weather conditions over a multiyear period.

The data are considered "typical" because the entirety of the original solar radiation and meteorological data is condensed into one year's worth of the most usual conditions. Although a TMY can be thought of as a median, the methods used to calculate it consider many factors beyond a simple calculation of median values, including solar resource data and weather data such as wind speed and ambient temperature.

</br></br>

### ◘ Objective
The primary incentive of this research is to:
* Analyze the integrity of the dataset, and check for missing values, duplicated values, and so forth.
* Perform various clean-ups, if required, and improve accessibility for more convenient exploratory analysis.
* Conduct exploratory analysis using a myriad of analysis and graphing tools to reach a conclusion.
* To reach a proper decision on which model to apply to the processed dataset in a future project to achieve the ideal optimization tuning and hopefully, a better outcome in the model's generalization.

</br></br>

### ◘ Approach
This research is classified into 2 steps:
1. Data Preprocessing: Where the dataset is extracted, tested, cleaned, processed, and stored in memory.
2. Feature Exploration: Where the processed data is then explored thoroughly to acquire a viable insight.

</br></br>

![alt text](https://github.com/shahriar-rahman/Analytics-NSRDB-Meteorological-Data/blob/main/img/FlowChart.png)

</br></br>

### ◘ Methodologies & Technologies applied
* Resolve and Diagnose structural errors
* Check and Clean data
* Address duplicates & outliers
* Logical feature amalgamation to construct a unique variable
* Univariate inspection
* Bivariate inspection
* Feature correlations
* Seaborn & Matplotplib visualizations

</br></br>

### ◘ Required Libraries
* pandas~=2.0.3
* missingno~=0.5.2
* seaborn~=0.12.2
* matplotlib~=3.7.0
* numpy~=1.23.5



### Readme Construction is still in Progress...
===========================================================================

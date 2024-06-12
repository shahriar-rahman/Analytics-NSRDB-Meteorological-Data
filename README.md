===========================================================================
# An Analytical Approach to NSRDB Meteorological Database
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

</br></br>

### ◘ Jupyter core packages
* IPython : 8.10.0
* ipykernel : 6.19.2
* ipywidgets : 7.6.5
* jupyter_client : 7.3.4
* jupyter_core : 5.2.0
* jupyter_server : 1.23.4
* jupyterlab : 3.5.3

</br></br>

### ◘ Project Organization
------------
    ├── LICENSE
    │
    ├── README.md          # The top-level README for developers using this project.
    │
    ├── dataset
    │   └── processed      # The final, canonical data sets for modeling.
    │   └── raw            # The original, immutable data dump.
    │
    │
    ├── notebook           # Jupyter notebook for EDA
    │                         		
    │
    ├── graphs            # Generated graphics and figures to be used in reporting using Jupyter Notebooks
    |
    │
    ├── img              # Project related files
    │
    ├── requirements.txt    # The requirements file for reproducing the analysis environment, e.g.
                              generated with `pip freeze > requirements.txt`

--------

<br/><br/>

### ◘ Installation (using pip)
In Jupyter, the console commands can be executed by the *‘!’* sign before the command within the cell. For example, If the following code is written in the Jupyter cell, it will execute as a command in CMD.
To intall any modules effectively, the sys python package is used and works as follows:
```
import sys
!{sys.executable} -m pip install [package_name]                               
```
1. For Pandas, run:
```
!{sys.executable} -m pip install pandas                                                  
```
2. To install missingNo:
```
!{sys.executable} -m pip install missingno                                                   
```
3. Matplotlib can be installed by running the following command:
```
!{sys.executable} -m pip install matplotlib                  
```
4. Next for Numpy, run the following command:
```
!{sys.executable} -m pip install numpy                
```
5. Lastly, for seaborn:
```
!{sys.executable} -m pip install seaborn              
```

<br/><br/>

### ◘ Import Packages
To *import* the dependencies, simply open the preferred IDE or Notebook: 
1. For Pandas, run the following command:
```
import pandas as pd                                   
```
2. To use missingno, run:
```
import missingno as msn                                      
```  
3. Import matplotlib using:
```
import matplotlib.pyplot as plt                                     
```
4. Import numpy using:
```
import numpy as np                                    
```
5. Seaborn can be accessed by:
```
import seaborn as sns                                      
```
<br/><br/>

### ◘ Supplementary Resources
* https://pypi.org/project/pandas/
* https://pypi.org/project/matplotlib/
* https://pypi.org/project/seaborn/
* https://pypi.org/project/missingno/
* https://pypi.org/project/numpy/

<br/><br/>

### ◘ MIT License

Copyright (c) 2023 Shahriar Rahman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

<br/><br/>

===========================================================================

# R-tists-final


**Team Name:** R-tists

**Members:** Zainab Danish (zdanish@usfca.edu), Derek Welborn (dnwelborn@usfca.edu)

# Introduction

This project aims to look at the crude prevalence of diseases and disease indicators in the US by state, gender and race in order to gain a better understanding of geography impacts diseases and their indicators.

# Data

* This dataset is available for public use at: [disease data](https://catalog.data.gov/dataset/u-s-chronic-disease-indicators-cdi-e50c9)
* The dataset spans various years - our project focuses on the most recent data from 2014.


# Prototype

The idea was to make the plots click-interactive so one plot would lead to a UI or another plot. As the screenshot below shows, the first plot is a chloropleth shaded by Mortality Rate. Clicking on a particular state reveals a checkbox interface which allows the user to select the Topic of their choosing. The topic then results in a treemap.

<img src="https://github.com/usfviz/R-tists-final/blob/master/prototype.png" alt="alt text" width="400" height="250">

# Final Version

The final version goes further from the treemap to produce a dropdown menu depending on which section of the tree is clicked by the user. The dropdown has options for further stratifying the indicator into:

* Race
* Ethnicity

## Here is a step by step visual:

### Tab 1:

#### 1. Starts with the chloropleth colored by Mortality Rates:


<img src="https://github.com/usfviz/R-tists-final/blob/master/Final%20Images/1.png" alt="alt text" width="550" height="300"> 

#### 2. Moves on to the indicators related to the state clicked on:


<img src="https://github.com/usfviz/R-tists-final/blob/master/Final%20Images/2.png" alt="alt text" width="700" height="300">

#### 3. The topic selected then yields a treemap of indicators for the state in question:


<img src="https://github.com/usfviz/R-tists-final/blob/master/Final%20Images/3.png" alt="alt text" width="600" height="300">

#### 4. The indicator from the treemap yields a dropdown menu which has options for stratification:


<img src="https://github.com/usfviz/R-tists-final/blob/master/Final%20Images/4.png" alt="alt text" width="900" height="300">

#### 5. Based on the selected stratification, a donut chart showing the breakup is created:


<img src="https://github.com/usfviz/R-tists-final/blob/master/Final%20Images/5.png" alt="alt text" width="600" height="300">

### Tab 2:

This tab shows a cartogram of the deadliest of all diseases by inidcator. The cartogram shows rates both by percentage and by 100,000 people of both different types of cancers as well as the preventative measures such as mammograms that can be taken against it.

The drop down menu on the right includes different indicators for the various types of cancer.

<img src="https://github.com/usfviz/R-tists-final/blob/master/Final%20Images/6.png" alt="alt text" width="650" height="300">

We thought it would be interesting to see how the states rates differed and whether higher rates of precautionary and preventative measures resulted in reduced death rates.

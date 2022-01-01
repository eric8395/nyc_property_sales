# NYC Property Sales Exploratory Data & Regression Analysis 

<p align="center">
  <img src = "https://cdn.vox-cdn.com/thumbor/XIlndqD57Aww4DFv1a143stOhBA=/0x0:2000x1333/1200x800/filters:focal(840x507:1160x827)/cdn.vox-cdn.com/uploads/chorus_image/image/58058203/170927_12_41_13_5DS26500.0.jpg" width = 500 height=300 />


#### The objective of this notebook is to apply exploratory analysis and regression techniques to identify which features affect housing property sales the most in New York City and come up with reasonable conclusions. 

Are there noticeable trends in the market that can predict sale value in the future? Are there any suprising observations or conclusions that can be made based on an analysis of the dataset?
  
This project also provided an opportunity to clean an otherwise, messy data-set and outliers in the data. 
  
# The Dataset: 

The dataset is retrieved from  New York City Department of Finance's Rolling Sales dataset and can be found on the [Kaggle](https://www.kaggle.com/new-york-city/nyc-property-sales) website. 
  
# Observations & Insights
 
* All boroughs (with the exception of Manhattan) consist of properties with a similar price for properties. Manhattan has the most expensive sale prices with a median sale price at about $1.7 million. Brooklyn comes in second with a median price at about $900k, and Queens in third with a median price at about $800k. The Bronx and Staten Island have median prices around $500k.


* As can be expected, properties identified as Tax Class 2 have the highest median price. Tax Class 2 properties consist of co-ops and condos. 


* The median price for pre-War properties (built before 1945) are more expensive (about $300k - $400k) than properties built post-war. 


* The most expensive neighborhood average price of a property is Park Slope South followed by Bedford Stuyvesant and Astoria. 
  
# Correlations: 
### Weak Positive Correlation
* Residential Units and Price

* Total Units and Price

* Gross Square Feet and price


### Moderate Positive Correlation
* Age and Price

As can be expected, increases in total units or residentail units is positively correlated with total and gross square footage of a property. 
  
<p align="center">
  <img src = "https://cdn.vox-cdn.com/thumbor/XIlndqD57Aww4DFv1a143stOhBA=/0x0:2000x1333/1200x800/filters:focal(840x507:1160x827)/cdn.vox-cdn.com/uploads/chorus_image/image/58058203/170927_12_41_13_5DS26500.0.jpg" width = 500 height=300 />

<p align="center">
  <img src = "https://cdn.vox-cdn.com/thumbor/XIlndqD57Aww4DFv1a143stOhBA=/0x0:2000x1333/1200x800/filters:focal(840x507:1160x827)/cdn.vox-cdn.com/uploads/chorus_image/image/58058203/170927_12_41_13_5DS26500.0.jpg" width = 500 height=300 />

<p align="center">
  <img src = "https://cdn.vox-cdn.com/thumbor/XIlndqD57Aww4DFv1a143stOhBA=/0x0:2000x1333/1200x800/filters:focal(840x507:1160x827)/cdn.vox-cdn.com/uploads/chorus_image/image/58058203/170927_12_41_13_5DS26500.0.jpg" width = 500 height=300 />

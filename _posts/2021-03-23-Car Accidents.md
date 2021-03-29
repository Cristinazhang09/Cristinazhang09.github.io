---
title: "Car Accidents"
date: 2021-03-23
tags: [data science]
header:
  image: "/images/jasper-geys-NyRe1Mj1pm4-unsplash.jpg"
excerpt: "Data Wrangling, Data Science"
mathjax: "true"
---

The purpose of my project is to use find out the importance of different climatic factors correspond to the accidents and severity. My data is a countrywide traffic accident dataset. The dataset covers 49 states of the United States, and the data are collected form February 2016 to December 2019, approximately 3 million accident records in this dataset. This project uses statistical analysis to find the relaionship between climatic factors and accidents severity. 

## Installation
The code requires Python versions of 3.* and general libraries.

## Project Motivation and Description
According car accidents statistics, there are nearly 6 million car accidents in the United States every year. Approximately 1.25 million people die in road crashed each year, in addition, 20-50 million people are injured, many of them even have long-term disabilities. Due to car accidents, many people lose properties, health, especially, people lose their loved ones. Thus, I determine to analyze a countywide car accident dataset,  

### There different models I used in this project.
* Multiple Linear Regression
* Support Vector Regression
* Random Forest Regression

In addition to evaluate how these three models can predict housing price, I used two differet performance metrics:
* Mmean Squared Error
* R-squared Value

## Results
* It can be found that livable area had an approximately linear relationship with the housing prices. I think this is in consist with common sense that the more livable area a house has, the higher of the house price will be.
* The number of bedrooms, bathrooms and garages can affect the housing prices. In general, the more bedrooms, bathrooms and garages a house has, the higher the price is. This also agrees with common sense, because more bedroom and bathrooms generally indicate a larger living area.
* The houses in school rating 10 have relatively higher prices.
* The house with window air conditions has relatively lower housing price
* Among different kinds of roof, tile roof, metal roof and flat roof have relatively higher housing prices. 
* Compared there different models, Radom Forest model performs best.

## Limitations
Tt is noticed the model performance is not quite good at the current stage, and I think there are multiple reasons for this:
* The model hyper parameters have not been optimized yet, grid search or randomized search with cross validation could be performed in the future to identify the best hyper parameters for the models.
* More features could be collected to complement the current dataset. It would also be interesting to increase the size of the dataset by collecting house information from east coast and west coast and see the determining factors of housing price vary with the geographical information.

## Licensing, Authors, Acknowledgements
The data used for analysisi is from [Zillow](https://www.zillow.com/)


# H1 Heading

## H2 Heading

### H3 Heading

Here's some basic text.

And here's some *italics*

Here's some **bold** text.

What about a [link](https://github.com/dataoptimal)?

Here's a bulleted list:
* First item
+ Second item
- Third item

Here's a numbered list:
1. First
2. Second
3. Third

Python code block:
```python
    import numpy as np

    def test_function(x, y):
      z = np.sum(x,y)
      return z
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_file.csv")
head(df)
```

Here's some inline code `x+y`.

Here's an image:
<img src="{{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg" alt="linearly separable data">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg)

Here's some math:

$$z=x+y$$

You can also put it inline $$z=x+y$$



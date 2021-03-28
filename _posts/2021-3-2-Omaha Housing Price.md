---
title: "Omaha Housing Prices"
date: 2018-01-28
tags: [data science]
header:
  image: "/images/john-fornander-tVzyDSV84w8-unsplash.jpg"
excerpt: "Data Wrangling, Data Science"
mathjax: "true"
---


The purpose of my project is to use real world house information to predict the house price. My dataset is collected by scrapping the house information from Zillow.com, the dataset includes information like the number of bedrooms, home type, year built, school rating and so on. All the houses are in Omaha metro.This project uses Multiple Linear Regression, Support Vector Regression and Random Forest Regression. These three models was compared using mean squared error.

# Demo-Preview

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



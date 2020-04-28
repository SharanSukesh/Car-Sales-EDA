# Exploratory Data Analysis of Car Sales

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Libraries used](#libraries-used)
* [Profiling Documents](profiling-documents)
* [Dataset used](#dataset-used)
* [Built on](#built-on)
* [Questions answered](#questions-answered)
* [Hypotheses tested](#hypotheses-tested)
* [Ackowledgements](#ackowledgements)
* [Author](#author)

## About the Project 

Exploratory Data Analysis of our Car Sales dataset which contains information such as body type, engine type and year of purchase.

The python notebook __"Car_Sales_Project"__ contains an initial EDA of car sales data and analyzes how different features impact car sales. It also suggests actionable insights as well as the best features to include in car production to increase sales based on the data. 

## Libraries used
* Numpy
* Pandas
* Matplotlib
* Seaborn

```bash
import numpy as np                                                
import pandas as pd                                               
import pandas_profiling
import matplotlib.pyplot as plt
import seaborn as sns            
%matplotlib inline
```

## Profiling Documents 
The documents below were used to profile the data before and after we processed the data :
 * __car_sales_preprocessing_df__ - Shows data profile before processing
 * __car_sales_postprocessing_df__ - Shows data profile after processing

## Dataset used 
* __INSAID__ - car_sales.csv

## Built with
* Jupyter Notebook

## Questions answered 
1. What is the price distribution of cars in the data set?
2. How does car body influence sales?
3. How does body type influence efficiency?
4. How does price influence efficiency with respect to body?
5. How does engine type influence sales?
6. How does engine type influence price?
7. How does price influence efficiency with respect to engine type?
8. How does engine drive influence sales?
9. How does engine drive influence price?
10. How does price influence efficiency with respect to drive?
11. How are car sales affected by year?
12. How is efficiency score influenced by year?
13. How does the engine volume differ with year?
14. How is mileage influenced by year?
15. How are price trends influenced by year?

## Hypotheses tested
1. Engine efficiency has played a role in car sale trends over the last 5 years
2. Engine efficiency to price plays an important role in car sale trends with respect to engine drive and car body
  * With respect to engine drive
  * With respect to the car body

## Ackowledgements
* <a href='https://www.insaid.co'> INSAID </a> - Dataset

## Author - Sharan Sukesh

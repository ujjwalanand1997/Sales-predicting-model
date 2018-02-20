# Dependency of Car Sales in Norway

## Project Description
Collecting data on sales of cars in Norway, petrol prices, rate of inflation and any other significant economic variable, and Examine if a predictive model could be developed for projecting car sales in Norway.

## Getting Started
So, We will analyze if sales of car is affected by different fuel models produced by the Company, or the inflation/deflation in the country. After analyzing we will make a predictive model for car sales in Norway.
 
## Hypothesis
According to us, sales of car depends upon a bunch of factors and we take fuel prices, quantity of diesel car sold, inflation/deflation in year 2007-2016.
As from our perspective, the variable fuel price will not affect the sales of car, as people do not consider fuel prices when buying a car, so we will not take fuel prices in our analysis, next variable quantity of diesel car sold will affect the sales of car, as people consider if the car is diesel model or petrol model, and by taking this we do not need to take petrol model cars in our analysis as it can be derived by difference of total car sold and diesel car sold. Other variable to consider is inflation/deflation of that year, as it affects the jobs of people. And without jobs or problem in jobs, people do not give priority to the cars and other desires, so we will consider inflation/deflation in our analysis.

## Data
Data of total car sold and diesel car sold is taken from the kaggle.com which is a trusted website for datasets.

The other data of inflation/deflation is taken by the data.worldbank.com which is the official website to get datasets which are financially related to any country.

Then we filtered the data according to the use.

![Filtered data](https://github.com/ujjwalanand1997/Sales-predicting-model/blob/master/Analysis%20Images/Filtered_data.png?raw=true)

## Dependency factors on Sales of car
As, Sales of car may depend on many factors, but from our perception we had considered fuel options in car and inflation in the country during the period.
 
As people do not consider fuel prices when buying a car, so we will not take fuel prices in our analysis.

![Dependency](https://github.com/ujjwalanand1997/Sales-predicting-model/blob/master/Analysis%20Images/dependency.png?raw=true)

The graph is looking quite convincing and looks like there may exist a dependency of total diesel model sold and inflation during the year , on the total car sale in Norway. 

After 2012, the graph is showing that total car sale is increasing in spite of the fact that plot of diesel models sold and inflation is going down.

## Inflation/deflation in Norway in 10 years

Norway’s market is quite good, if we see the graphs of 10 years.

It is seen that in 2008 it got much inflation and 2009 got a set back.

Other than these years Norway’s market is quite mild a consistent. 

![Inflation](https://github.com/ujjwalanand1997/Sales-predicting-model/blob/master/Analysis%20Images/inflation_bar.png?raw=true)

## Diesel Cars in Total cars sold

As We can see that Diesel Cars contribute a major share in Total car sold per year, but there from 2012 we are seeing a decrease in diesel model cars sold. 

The Decrease may be seen due to coming of different concept cars like cars running in battery or there may be a cause that diesel models make more pollution.

![Filtered data](https://github.com/ujjwalanand1997/Sales-predicting-model/blob/master/Analysis%20Images/diesel_sale.png?raw=true)

## MODEL

**Multiple linear regression** model is used to evaluate the datasets. Year, Inflation/Deflation, Diesel model sold as the independent variables and Total car sold as the dependent variable.

The model is quite efficient also as it shows the efficiency greater than 75%(r2 value is 0.791).

**ANALYSIS**
The Graph is quite good and productive.

![Filtered data](https://github.com/ujjwalanand1997/Sales-predicting-model/blob/master/Analysis%20Images/Analysed.png?raw=true)

Through the analysis, It states that sales of car is depending on inflation/deflation in the country, also it depends on the diesel model cars provided by the car producing companies.

**ERROR IN MODEL**

**Causes of Error in Model**
-The one year 2009, where our model is showing a large difference in our predicted data

-Possible causes of error for that year:
 -There is a deflation during 2009, which can be cause of less car sales in that year.

![Filtered data](https://github.com/ujjwalanand1997/Sales-predicting-model/blob/master/Analysis%20Images/error1.png?raw=true)
![Filtered data](https://github.com/ujjwalanand1997/Sales-predicting-model/blob/master/Analysis%20Images/error2.png?raw=true)


### Prerequisites


### Installing

## Usage

## Deployment


## Authors

* **Ujjwal Anand** - *Includes coding as well as Data Management* - [linkedin profile](https://www.linkedin.com/in/ujjwal-anand-653623151/)
* **Abhishek Kumar** - *Includes coding* -

## Acknowledgments

* This whole Model is made to get the concepts of Data Analysis.
* I got much help from google.
* Thanks to [Udemy.com](Udemy) to give such a handfull of tutorials free to use and learn.


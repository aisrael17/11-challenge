# 11-challenge
Challenge 11 for Columbia FinTech Bootcamp

## Technologies
I completed this challenge using Google Colab and the following external libraries:
* pandas
* holoviews
* prophet (Prophet)
* datetime
* hvplot.pandas
* numpy
* google.colab (files)

## Data
We used 3 datasets for this challenge:
1. Google search traffic for MercadoLibre (hourly from 6/1/16 00:00:00 to 9/8/20 00:00:00
2. MercadoLibre daily sales from 1/1/19 to 5/14/20
3. MercadoLibre daily stock price (hourly closes) from 1/2/15 9:00:00 to 7/31/20 15:00:00

## Challenge  Description
First, we looked at the search traffic in May 2020 to see if MercadoLibre's financial results being released corresponded with increased search traffic. It appears that this did occur. Then, we looked at seasonality in the search trends data, concluding that search traffic drops significantly on weekends, especially from 10am to 1pm. 

Next, we tried to assess whether or changes in MercadoLibre's stock price corresponded with changes in search trends. We concluded that on the aggregate, it does not.

Finally, we used the all-powerful Prophet library to predict google search trends for MercadoLibre, finding that midnight on Tuesday is the most popular time for search traffic, with mid-October being the lowest point in the calendar year. 

Last, I took a crack at the optional section and found that peak revenue days for MercadoLibre are Mon-Wed, with Wednesday as the peak. 

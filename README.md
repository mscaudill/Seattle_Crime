# Seattle_Crime: Analysis of crimes in the city of Seattle

<img src =
"https://github.com/mscaudill/Seattle_Crime/blob/master/data/choropleth.png" height="500" align="left">

This python project analyzes the number of assault offenses in the city of Seattle for the last 7 years. The
[data](https://dev.socrata.com/foundry/data.seattle.gov/y7pv-r3kh) for this
project is available through the Seattle open data API provided by Socrata.

______

## Summary 
The Seattle police department records the time and location(latitude, longitude) for all offenses that occur in its 51 police beats across the city. In this project we examine the number of assaults across police beats and across the seven reporting years. Two observations lead to two predictive models for assaults.

First, we find that assaults are correlated with a subset of the 51 non-assault offenses. We build a model to predict the number of assaults(response) given this subset of offenses (predictors).

Second, we find that there are sustained periods of time where assaults are
high or low in specific districts. We model this timecourse
to make a prediction for the number of assaults on a month-by-month basis.

Corrections and suggestions are always welcome!

## Dependencies
[Jupyter](http://jupyter.org/)<br>
[Numpy](http://www.numpy.org/)<br>
[Scipy](https://www.scipy.org/)<br>
[Pandas](http://pandas.pydata.org/)<br>
[Scikit-learn](http://scikit-learn.org/stable/)<br>
[Statsmodels](http://statsmodels.sourceforge.net/)<br>






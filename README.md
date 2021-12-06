# Economic Indicator Analysis

## What is it about?

Our project attempts to investigate economic indicators responsible for the economic growth of India, we wish
to learn how the economic indicators are correlated with each
other. We have accumulated data from 1960-2020 to do a timeseries analysis. We will take a deep dive into the trends witnessed
over the years and how they affected other economic indicators.
We will also study what economic indicators are highly correlated
with GDP as GDP is commonly accepted as the primary source
of judging economic growth.

## Files
Preprocessing_the_initial_csv.ipynb : Remove null values and redundant features.

EDA.ipynb : Explanatory Data Analysis of the data.

Forecasting.ipynb : Use various time series forecasting models to predict GDP.

FBProphet.ipynb : Time series forecasting use the FBProphet library of Facebook. 

## Our Dataset

We choose data collected by the World Bank in the form of the the [World Development Indicators](https://databank.worldbank.org/source/world-development-indicators).
They allowed us to tailor a custom dataset through the vast number of indicators they have collected data for. Our dataset only took indicator data for India, as our study pertains to that. The dataset is available in the form of `Data.csv`.

## Our approach to the problem

Our team started off by understanding all the indicators and their relavence by performing Exploratory Data Analysis in the form of `EDA.ipynb`. Before we could perform this however, our dataset was raw and had to be preprocessed before we could do anything which we did via `Preprocessing the initial csv file.ipynb` which produced `final.csv`. We gathered insights by plotting graphs in `plots_complete.ipynb`. Since our data was timeseries data, we making models and tested them in `Forecasting.ipynb`.

## Libraires Used
`Standard python library`
`numpy`
`pandas`
`matplotlib`
`seaborn`
`scikit-learn`
`statsmodels`
`scipy`
`fbprophet`

## Team Name
AlphaCube_024_042_056_165





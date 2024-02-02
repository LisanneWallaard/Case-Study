# Case-Study
Modelling temperature persistence in Europe by group PCS-23.

## Table of Contents
1. [General info](#general-info)
2. [Technologies](#dependencies)
3. [Installation](#installation)

## General info
This research investigates the changes in temperature extremes and persistence over time in Europe using a periodic quantile autoregression model (PQAR) with one lag.  The quantiles 0.1 and 0.9 are considered for the low and high temperature extremes, respectively, while the 0.5 quantile is used for comparison with the periodic autoregression model model(PAR) with one lag. The models are run on data from 12 different weather stations in Europe across different climate systems for the periods 1900-1940 and 1980-2020:
- `PCS_Group23.ipynb` is a notebook containing code that implements the PAR(1) & PQAR(1) model and produces plots of the estimated parameters.
- `data` is a folder of text files containing the mean temperature of 11 weather station (the data of one weather station is directly retrieved from the internet).
- `dataframes` is a folder of pandas DataFrames containing the estimated parameters of a certain model per weather station.
- `plots` is a folder of plots containing the $\hat{\phi}$, $\hat{\alpha}$ and $\hat{\mu}$ of the different models per weather station.

## Dependencies
The notebook consists of text and code cells in `python`. It uses the following libraries:

## Installation
No installation should be needed. Just download the notebook and open it in an editor where you are able to run the code. It is the most convenient to download both the dataframes as data folder into your Google Drive and mount your notebook with your Drive.

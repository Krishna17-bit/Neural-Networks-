## Overview
This repository houses Python scripts designed for building and evaluating machine learning models to predict outcomes in different scenarios. Currently, it features two primary models:

Turbine Energy Yield Prediction - Utilizes data from gas turbines to forecast the energy output based on environmental and operational parameters.
Forest Fire Area Prediction - Predicts the area affected by forest fires using meteorological data and other relevant variables.

## Project Structure
The repository is organized as follows:

- NN Gas_turbine.ipynb: Script for predicting turbine energy yield.
- NN forest_fire.ipynb: Script for predicting the area burned in forest fires.

## Data Description
Turbine Energy Yield Prediction
The turbine dataset comprises several operational and environmental variables, such as:

- AT (Ambient Temperature): Temperature in Celsius.
- AP (Ambient Pressure): Pressure in millibar.
- AH (Ambient Humidity): Humidity in percentage.
- AFDP (Air Filter Differential Pressure): Differential pressure in millibar.
- GTEP (Gas Turbine Exhaust Pressure): Exhaust pressure in millibar.
- TIT (Turbine Inlet Temperature): Temperature at the turbine inlet in Celsius.
- TAT (Turbine After Temperature): Temperature after the turbine in Celsius.
- TEY (Turbine Energy Yield): Energy output in MWh (target variable).
- CDP (Compressor Discharge Pressure): Discharge pressure in millibar.
- CO (Carbon Monoxide): CO levels in mg/m^3.
- NOX (Nitrogen Oxides): NOx levels in mg/m^3.

## Forest Fire Prediction
The forest fire dataset features weather and fire-related variables, including:

- month: Month when the fire occurred.
- day: Day of the week.
- FFMC: Fine Fuel Moisture Code index from the FWI system.
- DMC: Duff Moisture Code index from the FWI system.
- DC: Drought Code index from the FWI system.
- ISI: Initial Spread Index from the FWI system.
- temp: Temperature in Celsius.
- RH: Relative Humidity in percentage.
- wind: Wind speed in km/h.
- rain: Precipitation in mm/m^2.
- area: Burned area in hectares (target variable).

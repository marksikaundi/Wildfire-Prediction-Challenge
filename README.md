# About Wildfire Prediction Challenge
Can you predict the burned area of wildfires in ZInbabwe?

## Description

Welcome to our beginner-friendly Machine Learning Hackathon! This challenge is specially designed for first-time participants, offering a safe and supportive environment where you can learn, collaborate, ask questions and grow with fellow newcomers.

Each year, thousands of fires blaze across the African continent. Some are natural occurrences, part of a ‘fire cycle’ that can actually benefit some dryland ecosystems. Many are started intentionally, used to clear land or to prepare fields for planting. And some are wildfires, which can rage over large areas and cause huge amounts of damage. Whatever the cause, fires pour vast amounts of CO2 into the atmosphere, along with smoke that degrades air quality for those living downwind.
> --
Figuring out the dynamics that influence where and when these fires occur can help us to better understand their effects. And predicting how these dynamics will play out in the future, under different climatic conditions, could prove extremely useful.
> --
The objective of this challenge is to create a machine-learning model capable of predicting the burned area in different locations over 2014 to 2016.
> --
We’ve aggregated data on burned areas across Zimbabwe for each month since 2001. You’ll be given the burn area data up to the end of 2013, along with some additional information (such as rainfall, temperature, land cover etc) that extends into the test period.
> --
We’ve split up Zimbabwe into 533 equal areas, centered around the locations provided in the lat/lon columns. The target variable, burn_area, is the percentage of the area that has been burned in a given month. Due to the way it’s measured, there may be some overlap of burned areas for two successive months, and so the total burned area over a time period isn’t necessarily equal to the sum of the ‘burn_area’ figures for all months. You are not permitted to use external data in this competition.

> The additional data included in the test and train files is as follows:

Climate: All columns climate_[variable] derived from https://developers.google.com/earth-engine/datasets/catalog/IDAHO_EPSCOR_TERRACLIMATE - see the image bands listed for more information.
Land Cover: The percentage of the area falling into each of the LC_Type4 land cover types https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MCD12Q1 - see for details.
UN-Adjusted Population Density (estimated number of persons per square kilometer) from https://developers.google.com/earth-engine/datasets/catalog/CIESIN_GPWv411_GPW_UNWPP-Adjusted_Population_Density
Mean elevation in meters, from https://developers.google.com/earth-engine/datasets/catalog/USGS_GMTED2010
Monthly Precipitation Estimates - https://developers.google.com/earth-engine/datasets/catalog/TRMM_3B43V7
# About Wildfire Prediction Challenge
Can you predict the burned area of wildfires in ZInbabwe?



We’ve split up Zimbabwe into 533 equal areas, centered around the locations provided in the lat/lon columns. The target variable, burn_area, is the percentage of the area that has been burned in a given month. Due to the way it’s measured, there may be some overlap of burned areas for two successive months, and so the total burned area over a time period isn’t necessarily equal to the sum of the ‘burn_area’ figures for all months. You are not permitted to use external data in this competition.

> The additional data included in the test and train files is as follows:

Climate: All columns climate_[variable] derived from https://developers.google.com/earth-engine/datasets/catalog/IDAHO_EPSCOR_TERRACLIMATE - see the image bands listed for more information.
Land Cover: The percentage of the area falling into each of the LC_Type4 land cover types https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MCD12Q1 - see for details.
UN-Adjusted Population Density (estimated number of persons per square kilometer) from https://developers.google.com/earth-engine/datasets/catalog/CIESIN_GPWv411_GPW_UNWPP-Adjusted_Population_Density
Mean elevation in meters, from https://developers.google.com/earth-engine/datasets/catalog/USGS_GMTED2010
Monthly Precipitation Estimates - https://developers.google.com/earth-engine/datasets/catalog/TRMM_3B43V7
# Aviation Accident Analysis

## Project Overview
This project analyzes aviation accident data to find safer airplane makes/models and factors that may affect accident severity.

## Business Understanding
The client is interested in professionally built airplanes that may still be active. The goal is to recommend safer aircraft makes and identify factors that affect injury and destruction rates.

## Data Cleaning
I cleaned the data by:
- keeping only airplanes
- keeping only non-amateur aircraft
- keeping accidents from 1983 onwards
- removing missing Make and Model values
- creating injury rate and destruction columns
- removing columns with too many missing values

## Analysis Summary
I compared aircraft makes using injury rate and destruction rate. I also compared small and large planes using a passenger threshold of 20.

The analysis showed that larger planes generally had lower injury rates than smaller planes. Weather conditions also appeared to affect injury rates, with poor weather showing higher average injury rates.

## Recommendations
Based on the analysis, aircraft makes such as Embraer, Boeing, and Airbus showed lower injury rates and are better options to consider.

Two important safety factors were:
1. Plane size
2. Weather condition

Engine type and number of engines were also explored, but they appeared to have a smaller effect than plane size and weather.

## Files
- Aviation_Accidents_Cleaning.ipynb
- Aviation_Accidents_Data_Analysis.ipynb
- cleaned_aviation_data.csv
# Project: Smoking vs. poverty rates by US county

## Overview

Initial data (geo and rates) of percent rates of smoking and poverty by population for every US county in 2015 and 2016.

## Project structure

Follows the general structure of [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) for a logical, reasonably standardized, flexible and reproducible project structure for doing and sharing data science work.

## Data sources

1. [US Census Bureau 10m TopoJSON](https://github.com/topojson/us-atlas) topology containing three geometry collections: _counties_, _states_, and _nation_.
2. Poverty Rate by County and Adult Smoking Prevalance by State and County from [DataUSA](https://datausa.io):
    * Adult Smoking Prevalence (%)
    * Population in Poverty
    * Overall Population

## Purpose

Initial exploratory dataset review to determine geospatial trends and inter-relationships between smoking and poverty rates across the United States by County in preparation for a data science project such as predicting future rates and relationships.

## Visualizations

1. *us-county-smoking-2015*: Percent of adult population that smoke per US county in 2015. Missing data colored white. Hover over county for tooltip with location and value. A quantize scale is used to divide the color range into 10 discrete, uniformly-spaced bins.
2. *us-county-poverty-2015*: Percent of population in poverty per US county in 2015. Missing data colored white. Hover over county for tooltip with location and value. A quantize scale is used to divide the color range into 10 discrete, uniformly-spaced bins.
3. *us-county-poverty-vs-smoking-2015*: Interactive scatter plot of percent adult population that smoke vs. percent population in poverty per US county in 2015. Drop-down located in the _bottom-left_ can be adjusted to display specific state or all states. Hover over data point for tooltip with location.

# Phase 3 project: Tanzania Water Wells
#### Author: Jelimo Marion


## Overview

##                                 Enhancing Lives through Well Waters

![image-1](https://www.worldvision.org/wp-content/uploads/2017/09/D055-0831-36_631640-2x1100.jpg) <br />


Several countries struggle with providing easily accessible, inexpensive, and  clean water to its citizens. Tanzania, a developing country, with a population of 57, 000, 000 is one of these countries. As a solution, the government has established wells in numerous places in the country to cater to her citizens

However, the government currently faces a predicament in maintaining the wells as some break down and others fail completely. Therefore, there is need for a means to ensure that the wells that have broken down are repaired and that future wells that are built have reduced if not eliminated break-down possibility. This project oversees the attempt to fill the gap at hand.

## Business Understanding

### Business Problem

The Government of Tanzania wants to repair the wells that have broken down in their country and build new wells with minimized if not eliminated break-down rate. However, they need to identify and locate these wells as well as identify reasons of breakdown for future building.

### Problem Statement

The task at hand is to create a classifier algorithm that predicts the condition of the water well, using information gathered from existing wells.

### Objectives

- To create a classifier algorithm that predicts the condition of a water well
- To predict how likely a well is to break down
- To identify which wells are in need of repair
- To reduce the break-down rate of future wells

## Data Understanding

### Data Sources

[Training set values](https://drivendata-prod.s3.amazonaws.com/data/7/public/4910797b-ee55-40a7-8668-10efd5c1b960.csv?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARVBOBDCYQTZTLQOS%2F20231129%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231129T174425Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8fcfe12f8d01e28baee0064992a62bcd3b96d77890cc955105770c25c58ea3cc): The independent variables that need predictions


### Features

- amount_tsh - Total static head (amount water available to waterpoint)
- date_recorded - The date the row was entered
- funder - Who funded the well
- gps_height - Altitude of the well
- installer - Organization that installed the well
- longitude - GPS coordinate
- latitude - GPS coordinate
- wpt_name - Name of the waterpoint if there is one
- num_private -
- basin - Geographic water basin
- subvillage - Geographic location
- region - Geographic location
- region_code - Geographic location (coded)
- district_code - Geographic location (coded)
- lga - Geographic location
- ward - Geographic location
- population - Population around the well
- public_meeting - True/False
- recorded_by - Group entering this row of data
- scheme_management - Who operates the waterpoint
- scheme_name - Who operates the waterpoint
- permit - If the waterpoint is permitted
- construction_year - Year the waterpoint was constructed
- extraction_type - The kind of extraction the waterpoint uses
- extraction_type_group - The kind of extraction the waterpoint uses
- extraction_type_class - The kind of extraction the waterpoint uses
- management - How the waterpoint is managed
- management_group - How the waterpoint is managed
- payment - What the water costs
- payment_type - What the water costs
- water_quality - The quality of the water
- quality_group - The quality of the water
- quantity - The quantity of water
- quantity_group - The quantity of water
- source - The source of the water
- source_type - The source of the water
- source_class - The source of the water
- waterpoint_type - The kind of waterpoint
- waterpoint_type_group - The kind of waterpoint

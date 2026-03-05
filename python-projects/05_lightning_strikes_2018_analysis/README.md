# Lightning Strikes Analysis 2018

This project analyzes lightning strike activity recorded by NOAA in 2018.

## Dataset Source

The dataset used in this project comes from the NOAA Lightning Strike dataset available on Kaggle.

It contains records of lightning strike activity detected within geographic grid cells across the United States.

Dataset link:  
[NOAA Lightning Strikes Dataset – Kaggle](https://www.kaggle.com/datasets/likhari/lightening-strikes-dataset-noaa)

## Data Structure

The dataset contains the following variables:

- **date** – date when lightning activity was recorded  
- **number_of_strikes** – number of lightning strikes detected in a geographic grid cell  
- **center_point_geom** – geographic point representing the location of the grid cell

Example format:

POINT(-75 27)

During the analysis, this column is parsed to extract longitude and latitude values.

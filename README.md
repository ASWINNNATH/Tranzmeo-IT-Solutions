NOAA Temperature Analysis
This repository contains a Python script to analyze and visualize temperature data from the National Oceanic and Atmospheric Administration (NOAA) near Ann Arbor, Michigan, United States.

Dataset
The dataset used in this analysis is a subset of the Daily Global Historical Climatology Network (GHCN-Daily) dataset, which is comprised of daily climate records from thousands of land surface stations across the globe. The dataset is stored in two CSV files: temperature.csv and BinSize.csv.

Analysis
The script performs the following analysis:

Loads the dataset and preprocesses the data by converting the date column to datetime format and extracting the day of the year.
Filters the data for the period 2005-2014 and removes leap days.
Calculates the record high and record low temperatures by day of the year.
Plots a line graph of the record high and record low temperatures by day of the year, with the area between the two lines shaded.
Overlays a scatter plot of the 2015 data for points where the ten-year record high or record low was broken.
Visualizes the stations on a map using the folium library.
Plots a Temperature Summary for 2015 near Ann Arbor, Michigan, United States.

Requirements

Python 3.x
pandas
matplotlib
numpy
folium
Usage

Clone the repository to your local machine.
Install the required libraries using pip install -r requirements.txt.
Run the script using python script.py.
View the output plots and maps.


Author
Aswin O

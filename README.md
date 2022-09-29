# Quickstart_EDA_visualizations

This repository contains two Jupiter notebooks: 

- EDA_quickstart_airports
- Visualizations_quickstart_airports

The notebooks explore commercial airplane flight delays in the United States from 2011 to 2020 using Python's visualization capabilities in Matplotlib and Seaborn. 
The botebooks are designed to be quickstart guides for: 

- Performing EDA with the most common Python methods and functions 
- Analyzing a dataset using the most common visualizations in Matplotlib and Seaborn and producing an html presentation with certain level of detail.    

## EDA_quickstart_airports
The data was downloaded from the Bureau of Transportation Statistics website https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp. The EDA notebook loads the data and performs a series of commands to format, clean, feature engineer and perform exploratory analysis. 

The corresponding csv files are:  
- airline_delay_causes.rar
- airport_latlong.csv

The first dataset contains flight statistics for all airports in the United States. Each observation is reported by month, year, airport, and airline. Flights can be categorized as on time, delayed, canceled or diverted. Flight delays are attributed to five causes: carrier, weather, NAS, security, and late aircraft.This work analyses the data through the lenses of seasonality, airport traffic, and airline performance. The second csv contains the latitude and longitude of all US airports to merge into the main dataset. The notebook also exports the clean dataset, which contains 157,906 observations. 

## Visualizations_quickstart_airports 

The clean data set (delays_clean.csv) is analyzed using the following visualizations: 

- Bar chart
- Bar chart subplots 
- Lollipop chart
- Tree maps 
- Line plot
- Histogram
- Histogram subplots
- Horizontal stacked bar chart
- Ranked horizontal bar chart
- Box plot
- Pareto chart - double axis
- Marginal histogram 
- Pie charts
- Scatter plot
- Violin plot
- Map chart
- Linear regression

The repository also holds html summary presentation. 

**Additional resources:** 
Here are some of the materials I consulted while builiding this project:

- **General and comprehensive (also additional ideas for plots):**  
https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/

- **Georeferencing:**   
https://towardsdatascience.com/the-easiest-way-to-plot-data-from-pandas-on-a-world-map-1a62962a27f3
https://stackoverflow.com/questions/72476936/how-to-map-geographical-data-from-dataframe-on-map
https://geopandas.org/en/stable/gallery/plotting_basemap_background.html

- **Horizontal stacked bar charts:**  
https://stackoverflow.com/questions/16653815/horizontal-stacked-bar-chart-in-matplotlib

- **Markers and tick labels:**  
https://matplotlib.org/stable/api/markers_api.html
https://www.delftstack.com/howto/matplotlib/how-to-set-tick-labels-font-size-in-matplotlib/

- **Colors and palettes:**  
https://matplotlib.org/2.0.2/examples/color/named_colors.html
https://seaborn.pydata.org/tutorial/color_palettes.html



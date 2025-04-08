# Code examples

## Convert Units

This subdirectory contains example code for converting units (from aboveground biomass to aboveground carbon density) and renaming columns using SQL.

[convert-units](convert-units)

## Export GeoTIFF

This subdirectory contains example code for creating a raster file and saving it as a GeoTIFF using xarray and rioxarray. 

[export-geotiff](export-geotiff)

## Filter Values

This subdirectory contains example code for filtering a dataset to remove certain values (in this case, removing values with aboveground live carbon density equal to zero). 

[filter-values](filter-values)

## Join Datasets

This subdirectory contains example code for joining variables from two distinct datasets and returning a single combined dataset. In this example, we access data from Chloris and Planet, rename variables, and then visualize the joined dataset in a series of scatter plots. This example code introduces the concept of using SQL aliases to refer to separate datasets, and demonstrates how to perform an outer join.

[join-datasets](join-datasets)

## Map Data

This code example outlines different ways to plot data for one variable and one year in a map format. 
The following five methods are demonstrated: 
1. Plotting directly from a pandas dataframe
2. Plotting from xarray (as scatter plot and as heatmap)
3. Plotting using geopandas with pixel boundaries.
4. Plotting static map on a basemap using cartopy.
5. Plotting an interactive map on basemap using folium.

[map-data](map-data)
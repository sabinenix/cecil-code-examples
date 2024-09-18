# Code examples

## Convert Units

This subdirectory contains example code for converting units (from aboveground biomass to aboveground carbon density) and renaming columns using SQL.

[convert-units](convert-units)

## Create Raster

This subdirectory contains example code for creating a raster file and saving it as a GeoTIFF using xarray and rioxarray. 

[create-raster](create-raster)

## Join Datasets

This subdirectory contains example code for joining variables from two distinct datasets and returning a single combined dataset. In this example, we access data from Chloris and Planet, rename variables, and then visualize the joined dataset in a series of scatter plots. This example code introduces the concept of using SQL aliases to refer to separate datasets, and demonstrates how to perform an outer join.

[join-datasets](join-datasets)

## Plot Raster Map

This code example outlines different ways to plot data for one variable and one year in a raster map format. 
The following three methods are demonstrated: 
1. Plotting directly from a pandas dataframe
2. Plotting from xarray (directly and via matplotlib)
3. Plotting using pixel boundaries and geopandas.
4. Plotting on a basemap using cartopy.

[plot-raster](plot-raster)
# Code examples

## Convert Units

This code example demonstrates how to convert from aboveground biomass to aboveground carbon density by multiplying by 0.476 in SQL. 
The example also shows how to rename columns after doing unit conversion and display the results in a scatter plot.

[convert-units](convert-units)

## Join Datasets

This code example demonstrates how to access variables from two different datasets (Chloris and Planet), convert and 
rename variables, and then perform an outer join to combine data from both datasets into a single new dataset in SQL.
The example also displays the results stored in the combined dataset in a series of scatter plots.

[join-datasets](join-datasets)

## Plot Raster Map

This code example outlines different ways to plot data for one variable and one year in a raster map format. 
The following three methods are demonstrated: 
1. Plotting directly from a pandas dataframe
2. Plotting from xarray (directly and via matplotlib)
3. Plotting on a basemap using cartopy.

[plot-raster](plot-raster)
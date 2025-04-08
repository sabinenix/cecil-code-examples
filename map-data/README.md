# Code Example: Map Data

This subdirectory contains example code for plotting data extracted from the Cecil platform as map visuals. The notebook demonstrates five different plotting methods:

1. **Plotting from Pandas DataFrame** – Basic scatter plotting using `pandas` and its integrated plotting capabilities with `matplotlib`. 
2. **Plotting from XArray Dataset** – Plotting using `xarray` with its direct plotting functionality and combined with `matplotlib` - demonstrating both scatter and heatmap functionality.
3. **Plotting from Geopandas** – Plotting the data using the pixel boundary and CRS to minimze distortion.
4. **Plotting using Cartopy (Static map with basemap)** – Plotting the data using `cartopy` for geospatial visualization over a basemap.
5. **Plotting using Folium (Interactive map with basemap)** – Plotting the data using `folium` to create an interactive map with basemaps that can be toggled on and off.

The example code is included in a Jupyter Notebook (`map-data.ipynb`).




# Code Example: Plotting a Raster Map

This subdirectory contains example code for plotting data extracted from the Snowflake database as raster data using three different methods:

1. **Plotting directly from Pandas** – Basic raster data plotting using `pandas` and its integrated plotting capabilities.
2. **Plotting using Xarray** – Raster data plotting using `xarray` with its direct plotting functionality and combined with `matplotlib`.
3. **Plotting using Cartopy on top of a basemap** – Plotting raster data using `cartopy` for geospatial visualization over a basemap.

The example code is included in a Jupyter Notebook (`plot-raster.ipynb`).

## Requirements

The requirements for this code example are included in the `requirements.txt` file.

## Snowflake Database Access

In the code example, access credentials to the Snowflake database are stored in a configuration file (`config.yml`). You can either:
- Create a configuration file with the same structure as shown below, or
- Directly paste the access credentials where indicated in the Jupyter Notebook.

### Example Structure of Configuration File (`config.yml`):

```yaml
database-info:
  account: "[account_name]"
  user: "[username]"
  password: "[password]"
  warehouse: "[warehouse]"
  database: "[database_name]"

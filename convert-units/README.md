# Code Example: Convert Units

This subdirectory contains example code for converting units (from aboveground biomass to aboveground carbon density) 
and renaming columns using SQL. The code also pulls the data into a pandas dataframe and plots the two columns in a
scatter plot to visualize the relationship between the variables.

The example code is included in a Jupyter Notebook (`convert-units.ipynb`).

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

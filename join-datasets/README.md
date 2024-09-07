# Code Example: Join Datasets

This subdirectory contains example code for joining variables from two distinct datasets and returning a single
combined dataset. In this example, we access data from Chloris and Planet, convert the Planet aboveground carbon
density data into aboveground biomass data using SQL so that it can be directly compared to aboveground biomass data from 
Chloris, rename variables, and then visualize the joined dataset in a series of scatter plots. This example code
introduces the concept of using SQL aliases to refer to separate datasets, and demonstrates how to perform an outer join.

The example code is included in a Jupyter Notebook (`join-datasets.ipynb`).

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

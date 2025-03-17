# Python - NYC Basketball Courts Data Wrangling

## Project Overview
In this project, I performed data wrangling using Python to clean and analyze data on NYC basketball courts and NYPD arrest records. The goal was to assess the relationship between the availability of sports facilities and crime rates in different neighborhoods. Using Python's data manipulation libraries, I gathered, assessed, and cleaned datasets from multiple sources, then used the cleaned data to create visualizations and explore this potential connection.

## Dataset Information
The project uses two datasets:
- **NYC Basketball Courts**: Data pulled from the NYC Department of Parks & Recreation API. It contains information on the number of basketball courts at various locations across New York City.
- **NYPD Arrest Data**: Manually downloaded from the NYC Open Data portal. This dataset provides details on arrests made in NYC, including crime type, location, time of arrest, and suspect demographics.

The analysis focused on whether the availability of basketball courts in different boroughs correlates with lower arrest rates.

## Project Files
- **Raw Data**:
  - `NYC_Basketball_Courts.csv` - Contains data on basketball courts from the NYC Parks & Recreation Department.
  - `NYPD_Arrest_Data.csv` - Contains NYPD arrest data.

- **Cleaned Data**:
  - `clean_basketball_courts_data.csv` - Cleaned version of the basketball courts data.
  - `clean_nypd_arrest_data.csv` - Cleaned version of the NYPD arrest data.
  - `clean_data_by_borough.csv` - Cleaned data aggregated by borough for analysis.

- **Jupyter Notebook**:
  - `data_wrangling_project_starter.ipynb` - The Jupyter Notebook containing the full data wrangling process, including data gathering, cleaning, and analysis. This file can be viewed on GitHub or downloaded and run locally using Jupyter Notebook. Ensure the raw data files are in the same directory if running it locally.

- **HTML Version**:
  - `data_wrangling_project_starter.html` - An HTML version of the Jupyter Notebook, viewable in any browser if downloaded.

The Jupyter Notebook and HTML file document the entire wrangling process, along with visualizations and insights drawn from the cleaned datasets.
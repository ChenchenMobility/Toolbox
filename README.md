# Transportation Data Toolbox

This repository is a collection of tools designed to assist researchers and professionals in the field of transportation studies. The tools provided here aim to simplify the process of working with large transportation datasets and are freely available for anyone to use. Each tool has a specific focus, making it easier to manage and analyze different types of transportation data.

## Tools in this Repository

### 1. OSM_Regional_Road_Length.ipynb
This tool calculates the total road length within a circular zone, using OpenStreetMap (OSM) data and the Overpass API. Users can specify a longitude, latitude, and radius to define the circular area for which they want to measure road length.

- **Inputs**: Longitude, latitude, radius
- **Outputs**: Total road length within the defined zone
- **Requirements**: Access to the Overpass API

### 2. CO_OPS_Data_Scraper.ipynb
This tool scrapes data from CO-OPS weather stations, providing online access to historical and real-time weather data. It automates the data retrieval process for transportation studies that require accurate weather information from CO-OPS stations.

- **Inputs**: CO-OPS weather station identifiers, date range
- **Outputs**: Weather data in a structured format (e.g., CSV)
- **Requirements**: Internet access to retrieve data from CO-OPS

### 3. US_AIS_Downloader.ipynb
This tool downloads Automatic Identification System (AIS) data from the U.S. Marine Cadastre website. AIS data is essential for studying vessel movements and understanding maritime transportation patterns.

- **Inputs**: AIS data download parameters (e.g., time period, region)
- **Outputs**: AIS data files
- **Requirements**: Internet access to download data from [Marine Cadastre Vessel Traffic](https://hub.marinecadastre.gov/pages/vesseltraffic)

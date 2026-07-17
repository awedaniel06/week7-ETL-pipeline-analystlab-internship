# 🌦️ Week 7 Project: ETL Pipeline Using OpenWeather API

**Data Analytics Internship – AnalystLab Africa (Week 7)**

## Project Overview

This project was completed as part of my Data Analytics Internship at AnalystLab Africa (Week 7). The objective was to build a simple ETL (Extract, Transform, Load) pipeline using the OpenWeather API. The pipeline extracts real-time weather data, transforms it into a clean and structured format, stores it as a CSV file, and performs basic analysis.

ETL pipelines play an important role in data engineering and analytics by automating the process of collecting, cleaning, transforming, and storing data. This project demonstrates how Python can be used to automate these tasks using real-time weather data obtained from an external API.

## Data Source

**Source:** OpenWeather API

The OpenWeather API provides real-time weather information for cities around the world. The API returns weather data in JSON format, making it easy to retrieve and process using Python.

**Cities Used**
- Lagos
- Abuja
- Benin City

**Weather Variables Collected**
- City Name
- Country
- Temperature (°C)
- Feels Like Temperature (°C)
- Humidity (%)
- Atmospheric Pressure (hPa)
- Weather Condition
- Wind Speed (m/s)
- Date and Time

## ETL Process

### Extract

The Extract stage involved retrieving real-time weather information from the OpenWeather API.

**Activities performed:**
- Created an OpenWeather account
- Generated a personal API key
- Connected to the API using Python's Requests library
- Sent HTTP GET requests for Lagos, Abuja, and Benin City
- Retrieved weather data in JSON format
- Extracted only the required weather attributes

**Output:** Successfully connected to the API, retrieved real-time weather data, and extracted relevant weather information for the selected cities.

### Transform

The Transform stage focused on cleaning and preparing the extracted data for analysis.

**Activities performed:**
- Converted the JSON response into a Pandas DataFrame
- Selected only the required fields
- Renamed columns for better readability
- Converted Unix timestamps into a human-readable date and time format
- Structured the dataset into rows and columns
- Verified that the dataset was ready for analysis

**Output:** Clean and structured weather dataset ready for analysis.

### Load

The Load stage involved storing the transformed dataset for future use.

**Activities performed:**
- Exported the processed dataset as a CSV file
- Saved the file as `weather_data.csv`
- Verified that the file was successfully created

**Output:** Processed weather dataset stored successfully.

## Tools Used

- Python
- Pandas
- Requests
- OpenWeather API
- Jupyter Notebook / Visual Studio Code
- Git
- GitHub

## Steps Taken

1. Created a free OpenWeather account
2. Generated an API key
3. Installed the required Python libraries
4. Connected to the OpenWeather API
5. Retrieved weather data for Lagos, Abuja, and Benin City
6. Converted the JSON response into a Pandas DataFrame
7. Cleaned and transformed the extracted data
8. Saved the processed dataset as `weather_data.csv`
9. Performed basic exploratory analysis
10. Uploaded the completed project to GitHub

## Basic Analysis

After completing the ETL process, a simple exploratory analysis was carried out on the processed dataset. The analysis included:

- Displaying the complete weather dataset
- Comparing temperatures across Lagos, Abuja, and Benin City
- Identifying the city with the highest humidity
- Comparing weather conditions across the selected cities
- Identifying the hottest city
- Identifying the coldest city
- Calculating the average temperature across all cities

These analyses provided a quick overview of the weather patterns across the selected locations.

## Key Findings

- Temperature varied across the selected cities
- Humidity levels differed from one location to another
- Weather conditions were different across the cities
- The ETL pipeline successfully automated the extraction, transformation, and storage of real-time weather data
- The processed dataset is ready for further analysis, reporting, and visualization

## Project Structure

```
week7-etl-pipeline/
│
├── weather_etl.py
├── weather_data.csv
├── README.md
└── requirements.txt
```

## Conclusion

This project successfully demonstrated how to build a simple ETL pipeline using Python and the OpenWeather API. By completing the Extract, Transform, and Load stages, I gained practical experience in working with APIs, processing JSON data, transforming data with Pandas, storing datasets, and performing basic exploratory analysis.

The project also strengthened my understanding of how automated data pipelines support data-driven decision-making and prepare raw data for further analysis.

## Author

**Awe Daniel**
Data Analytics Intern
AnalystLab Africa
Week 7 – Data Pipelines & Automation

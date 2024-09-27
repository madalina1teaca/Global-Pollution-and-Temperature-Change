# Temperature and Pollution Analysis Project

## Introduction
This project aims to analyze environmental data, specifically focusing on temperature change and air pollution from the years 2000 to 2019. The datasets are processed and cleaned to facilitate further analysis and visualization of trends in these environmental factors.

## Project Structure

The project consists of the following components:

- **Data Folder**: Contains the raw data files:
  - `Environment_Temperature_change_E_All_Data_NOFLAG.csv`: Dataset containing temperature change data.
  - `Air Pollution.csv`: Dataset containing air pollution data.

- **Main Script**: A Python script that imports necessary libraries,loads the datasets, cleans the data, and prepares it for analysis.

## Libraries Used
This project utilizes the following libraries:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization.
- `seaborn`: For enhanced visualization capabilities.

## Data Loading and Preparation

### Temperature Dataset
- **Loading**: The temperature dataset is loaded from `Data/Environment_Temperature_change_E_All_Data_NOFLAG.csv`.
- **Filtering**: The script selects data from the years 2000 to 2019 by dropping irrelevant columns.
- **Renaming Columns**: The year columns are renamed for clarity.
- **Null Values Check**: The script checks for any null values in the dataset.

### Pollution Dataset
- **Loading**: The pollution dataset is imported from `Data/Air Pollution.csv`.
- **Filtering**: Rows are filtered to keep only data from the years 2000 to 2019.
- **Null Values Check**: Any necessary data cleaning steps can be included based on the specific requirements of the analysis.

## Analysis
With the cleaned datasets, further analysis can be performed to visualize trends in temperature changes and air pollution levels. This would typically include generating graphs and charts using Matplotlib and Seaborn.

## Requirements
To run this project, ensure you have the following installed:
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn

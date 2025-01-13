# Berlin Low-Scale Crime Analysis (2012–2019)
![Berliner_Polizei](https://github.com/user-attachments/assets/bc6e375b-e4e8-427d-99f9-bd8bc1ccc972)
![CareerFoundry-fulllogo-white](https://github.com/user-attachments/assets/68115cf5-1edb-4981-82ce-168c3963a445)


## Project Summary  
This project was completed as part of the CareerFoundry Data Analytics Program and focuses on analyzing low-scale crimes in Berlin from 2012 to 2019. The primary aim was to uncover patterns in crime trends, identify correlations between different types of crimes, and determine which districts in Berlin were most affected. Using Python and Excel, the analysis employed a range of techniques, including geospatial, regression, and cluster analysis, to derive actionable insights.  

## Objectives  
- **Trend Analysis**: Determine whether crime rates in Berlin increased or decreased during the study period.  
- **Correlation Analysis**: Identify potential relationships between different types of crimes.  
- **Geospatial Analysis**: Pinpoint the districts in Berlin most affected by crime.  

## Skills Demonstrated  
- **Python Programming**: Data cleaning, exploratory data analysis (EDA), and visualization.  
- **Data Visualization**: Creation of scatterplots, correlation heatmaps, pair plots, and categorical plots.  
- **Geospatial Analysis**: Mapping crime data using shapefiles.  
- **Statistical Analysis**: Regression and cluster analysis.  
- **Time-Series Analysis**: Examining trends over time.  
- **Interactive Dashboards**: Development of an interactive Tableau dashboard to present findings.  

## Tools and Systems Used  
- **Python**: Pandas, Matplotlib, Seaborn, Geopandas, and Scikit-learn.  
- **Excel**: Data organization and preprocessing.  
- **Tableau**: Interactive dashboard creation.
- **Development Environment:** Jupyter Notebook, Anaconda

## Folders
### 01. Project Management
  - Project Brief
### 02. Data
  - Original Data
  - Prepared Data
### 03. Scripts
### 04. Analysis
  - Visualizations

## Dataset Information
### - Source:###
The dataset used in this project combines data from multiple reliable sources:
  - **Berlin Crimes Dataset:** Originally published by the [Berlin Police](https://www.berlin.de/polizei/) in their biennial [“Berlin Crime Atlas”](https://www.berlin.de/polizei/service/kriminalitaetsatlas/), this dataset provides detailed insights into the small-scale distribution of crime in Berlin. The publicly available data was curated and consolidated into a single dataset by Danil Zyryanov on [Kaggle](https://www.kaggle.com/datasets/danilzyryanov/crime-in-berlin-2012-2019/data). The dataset includes translations and aggregation of yearly crime reports into a unified time series format.
  - **Berlin District Map Shapefiles:** Geographic shapefiles of Berlin districts were sourced from [ODIS - Open Data Informationsstelle Berlin](https://odis-berlin.de/) [dataset link](https://daten.odis-berlin.de/en/dataset/bezirksgrenzen/) for Python-based geospatial analysis. Additional shapefiles for Tableau visualizations were retrieved from [GitHub](https://github.com/ljwolf/geopython/blob/master/data/berlin-neighbourhoods.geojson), providing a more granular view of Berlin’s neighborhoods.

### - Contents###
The dataset captures small-scale crime statistics across Berlin districts from 2012 to 2019. It comprises:
  **- Rows:** 1,200
  **- Columns:** 20, representing crime types and related information, such as:
  **- Temporal:** Year
  **- Spatial:** District, Code, Location
  **- Crime Categories:** Robbery, Street Robbery, Injury, Aggressive Assault, Threat, Theft, Car Theft, Theft from Car, Bike Theft, Burglary, Fire, Arson, Damage, Graffiti, Drugs, and Local.
  
### - Data Size###
The dataset file is 124,093 bytes.


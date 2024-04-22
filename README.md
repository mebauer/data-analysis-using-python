# Data Analysis Using Python: A Beginner’s Guide Featuring NYC Open Data

Author: Mark Bauer  

The recording for this presentation can be viewed here: [![YouTube Video Views](https://img.shields.io/youtube/views/kobhJAxy3jQ?label=Watch%20Presentation&style=social)](https://www.youtube.com/watch?v=kobhJAxy3jQ)

Table of Contents
=================

   * [1. Introduction](#1-Introduction)
   * [2. Notebooks](#2-Notebooks)
   * [3. Data](#3-Data)
   * [4. Open Source Applications Used in Project](#4-Open-Source-Applications-Used-in-Project)
   * [5. Additional Resources](#5-Additional-Resources)

# 1. Introduction

NYC Open Data provides a treasure-trove of information - all publicly available with a click of a button. While having access to data is great, its analysis is often a difficult process for beginners, potentially creating barriers in one's open data journey. Additionally, performing data analysis in a reproducible way is often limited or even discarded altogether.

*Data Analysis Using Python: A Beginner’s Guide Featuring NYC Open Data* is a four-part series as listed in the sections below. These collection of notebooks serve as references/user guides for how to apply Python to real-world Data Analysis projects. The repository features notebooks that will utilize the [Python programming language](https://www.python.org/) and datasets from [NYC Open Data](https://opendata.cityofnewyork.us/). This series exemplifies how data analytics can be used for discovering useful information and supporting decision-making.

Sections include:

**Part 1: Reading and Writing Files in Python**    
Demonstrates various ways to read (load) and write (save) data using the Python programming language. The datasets contain common file formats such as comma-separated values (csv), JavaScript Object Notation (json), shapefiles (i.e. format for geometric location and attribute information) and zip files.
 
**Part 2: Data Inspection, Cleaning, and Wrangling in Python**  
Demonstrates various ways to to inspect, clean, wrangle, and detect any outliers in your data.

**Part 3: Plotting and Data Visualization in Python**  
Demonstrates various examples of plotting and data visualizations.

**Part 4: Geospatial Data and Mapping**  
Demonstrates various workflows of working with geospatial data and mapping.

# 2. Notebooks

You can view these notebooks through your browser by clicking *View* under the *Static Webpage* column.  

| File Name | Description | Static Webpage |
| :-------- | :---------- | :------------- |
| [1-reading-writing-files.ipynb](https://github.com/mebauer/data-analysis-using-python/blob/master/1-reading-writing-files.ipynb) | Reading and Writing Files. | [View](https://nbviewer.org/github/mebauer/data-analysis-using-python/blob/master/1-reading-writing-files.ipynb) |
| [2-data-inspection-cleaning-wrangling.ipynb](https://github.com/mebauer/data-analysis-using-python/blob/master/2-data-inspection-cleaning-wrangling.ipynb) | Data Inspection, Cleaning, and Wrangling. | [View](https://nbviewer.jupyter.org/github/mebauer/data-analysis-using-python/blob/master/2-data-inspection-cleaning-wrangling.ipynb) |
| [3-plotting-visualizations.ipynb](https://github.com/mebauer/data-analysis-using-python/blob/master/3-plotting-visualizations.ipynb) | Plotting and Data Visualization. | [View](https://nbviewer.jupyter.org/github/mebauer/data-analysis-using-python/blob/master/3-plotting-visualizations.ipynb) |
| [4-geospatial-data-mapping.ipynb](https://github.com/mebauer/data-analysis-using-python/blob/master/4-geospatial-data-mapping.ipynb) | Geospatial Data and Mapping. | [View](https://nbviewer.jupyter.org/github/mebauer/data-analysis-using-python/blob/master/4-geospatial-data-mapping.ipynb) |

# 3. Data 

| Dataset | Description |
| :-------- | :---------- |
| [Building Footprints](https://data.cityofnewyork.us/Housing-Development/Building-Footprints/nqwf-w8eh) | Shapefile of footprint outlines of buildings in New York City. |
| [MapPLUTO](https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-pluto-mappluto.page) | MapPLUTO merges PLUTO tax lot data with tax lot features from the Department of Finance’s Digital Tax Map (DTM) and is available as shoreline clipped and water included. It contains extensive land use and geographic data at the tax lot level in ESRI shapefile and File Geodatabase formats. |
| [Schools](https://data.cityofnewyork.us/Education/School-Point-Locations/jfju-ynrr) | This is an ESRI shape file of school point locations based on the official address.  It includes some additional basic and pertinent information needed to link to other data sources. It also includes some basic school information such as Name, Address, Principal, and Principal’s contact information. |
| [Streets](https://data.cityofnewyork.us/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b) | The NYC Street Centerline (CSCL) is a road-bed representation of New York City streets containing address ranges and other information such as traffic directions, road types, segment types. |
| [Neighborhood Tabulation Areas (NTA)](https://data.cityofnewyork.us/City-Government/Neighborhood-Tabulation-Areas-NTA-/cpf4-rkhq) | Boundaries of Neighborhood Tabulation Areas as created by the NYC Department of City Planning using whole census tracts from the 2010 Census as building blocks. These aggregations of census tracts are subsets of New York City's 55 Public Use Microdata Areas (PUMAs). |
| [NYC Boroughs](https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm) | GIS data: Boundaries of Boroughs (water areas excluded). |

# 4. Open Source Applications Used in Project 

- [Anaconda](https://www.anaconda.com/): A distribution of the Python and R programming languages for scientific computing (data science, machine learning applications, large-scale data processing, predictive analytics, etc.), that aims to simplify package management and deployment.  
- [Project Jupyter](https://jupyter.org/index.html): Project Jupyter is a non-profit, open-source project, born out of the IPython Project in 2014 as it evolved to support interactive data science and scientific computing across all programming languages.  
    - [Jupyter Notebook](https://jupyter.org/try): The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.
    - [nbviewer](https://nbviewer.jupyter.org/): A web application that lets you enter the URL of a Jupyter Notebook file, renders that notebook as a static HTML web page, and gives you a stable link to that page which you can share with others.

# 5. Additional Resources

- [NYC Open Data](https://opendata.cityofnewyork.us/): Open Data is free public data published by New York City agencies and other partners.  
- [Sodapy Tutorial Using NYC Open Data](https://github.com/mebauer/sodapy-tutorial-nyc-open-data): This tutorial demonstrates how to use sodapy and provides examples of querying data using Socrata Query Language or SoQL.  


# Say Hello!   

I can be reached at:  

Twitter: [markbauerwater](https://twitter.com/markbauerwater)  
LinkedIn: [markebauer](https://www.linkedin.com/in/markebauer/)  
GitHub: [mebauer](https://github.com/mebauer)

Keywords: *Data Analysis, Data Science, Python, pandas, numpy, matplotlib, seaborn, GeoPandas, Jupyter Notebook, Anaconda, NYC Open Data, Building Footprints, PLUTO, Open Data, Open Source, Open Science, Exploratory Data Analysis, EDA*

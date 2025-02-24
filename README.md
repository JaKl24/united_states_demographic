# United States Demographic

## Overview
This repository contains an Exploratory Data Analysis (EDA) of a dataset providing a detailed breakdown of demographic information for counties across the United States. The dataset is derived from the U.S. Census Bureau's 2023 American Community Survey (ACS) and includes population counts by gender, race, and ethnicity. Each county is uniquely identified using State and County FIPS codes.

## Dataset Features

- **County**: Name of the county.
- **State**: Name of the state the county belongs to.
- **State FIPS Code**: Federal Information Processing Standard (FIPS) code for the state.
- **County FIPS Code**: FIPS code for the county.
- **FIPS**: Combined State and County FIPS codes, a unique identifier for each county.
- **Total Population**: Total population in the county.
- **Male Population**: Number of males in the county.
- **Female Population**: Number of females in the county.
- **Total Race Responses**: Total race-related responses recorded in the survey.
- **White Alone**: Number of individuals identifying as White alone.
- **Black or African American Alone**: Number of individuals identifying as Black or African American alone.
- **Hispanic or Latino**: Number of individuals identifying as Hispanic or Latino.

### Dataset Source
source: [Kaggle - Demographics: Population, Race, Gender Data County]('https://www.kaggle.com/datasets/ahmedmohamed2003/county-level-demographic-population-race-gender')


## Libraries Used
The following Python libraries were used to analyze and visualize the data:
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.graph_objects as go
import plotly.express as px
import folium
import requests
from branca.colormap import LinearColormap
```

## License
This project is for educational and research purposes only. Please refer to the dataset sources for respective licensing information.

---
### Author: Jana Kl. 
📅 Last Updated: February 2025
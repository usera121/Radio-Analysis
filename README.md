# Analysis of Polish Radio Stations - 2024-2025
Exploratory Data Analysis of Polish radio airplay: music trends and premieres (Python)
[Open the interactive HTML report (GitHub Pages)](https://usera121.github.io/Radio-Analysis/Analysis_of_Polish_Radio_Stations_Report.html)

## Project Overview

[This report](https://usera121.github.io/Radio-Analysis/Analysis_of_Polish_Radio_Stations_Report.html) presents an analysis of music tracks played across **13 Polish radio stations** between **January 1, 2024** and **June 16, 2025**.  

The analysis focuses on:

- Track and artist popularity
- Library uniqueness across stations
- The speed of premiere appearances
- Airplay frequency during different times of day

![Radio stations](radio_eng.png)

**Data sources**:

- [odsluchane.eu](https://odsluchane.eu) – radio airplay logs
- musicbrainzngs – MusicBrainz API for release date metadata

**Key figures**:

- Records analyzed: **1,835,671**
- Unique artists: **52,877**
- Unique tracks: **86,816**

**Main questions answered**:

- Who are the most played artists and songs?
- Which tracks are unique to specific stations?
- How fast do new tracks appear on the air?
- What are the airplay patterns throughout the day?
- Which radio stations are most likely to premiere songs that later become major hits? 
- How do new tracks travel from their premiere to wider popularity across the radio landscape?


---

## Technologies & Libraries

- Python
- pandas
- numpy
- matplotlib
- seaborn
- plotly (express, graph_objs)
- datetime
- glob
- os
- re
- musicbrainzngs

## Data

Raw data (not included here) consists of daily CSV files, each representing airplay logs from multiple radio stations.  
Files are named by date and aggregated during preprocessing.

## Outcomes

- [Open the interactive HTML report (GitHub Pages)](https://usera121.github.io/Radio-Analysis/Analysis_of_Polish_Radio_Stations_Report.html)
- Jupyter Notebook: full end-to-end analysis pipeline  
  - [View in Jupyter Notebook (.ipynb)](./Radio_Analysis_Notebook.ipynb)
  - [View as HTML (.html)](./Radio_Analysis_Notebook.html)


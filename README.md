## Overview
This interactive layout is a project I completed for my Advanced Cartography and Geovisualization course at Macalester College in Fall 2018. It is meant to be a simple, exploratory visualization of wildfire trends in the US from 1992-2015.

The code in hexmaps.html produces a univariate hexbin density map of wildfires that occurred in the US in a given year. Hexagons are colored from light yellow (fewer wildfires) to dark purple (more wildfires).

The code in index.html takes images of the maps produced from hexmaps.html and allows a user to interact with a slider to display the map for whichever year is selected on the slider. Two bar charts powered by Google Charts display the number of wildfires that occurred in the selected year by 1) size category (A, B, C, D, E, F, or G, ordered smallest to largest) and 2) cause code (from 1 to 13). Details on what these size categories and cause codes correspond to are as follows:

##### Size Classes
A: 0.01-0.25 acres <br>
B: 0.25-9.9 acres <br>
C: 10.0-99.9 acres <br>
D: 100-299 acres <br>
E: 300-999 acres <br>
F: 1000-4999 acres <br>
G: 5000+ acres
<br><br>
##### Cause Codes
1: Lightning <br>
2: Equipment Use <br>
3: Smoking <br>
4: Campfire <br>
5: Debris Burning <br>
6: Railroad <br>
7: Arson <br>
8: Children <br>
9: Miscellaneous <br>
10: Fireworks <br>
11: Powerline <br>
12: Structure <br>
13: NA

The data for these charts are hosted in two Google Sheets documents, but I've uploaded the .csv files here as well for reference (fire_classes.csv and fire_causes.csv).

## Sources
https://github.com/d3/d3-hexbin <br>
https://github.com/d3/d3-geo/blob/master/README.md#geoAlbersUsa <br>
http://blockbuilder.org/mbostock/4330486 <br>
https://bl.ocks.org/lelandlee/7ceeba3314b3013f47e2 <br>
https://developers.google.com/chart/interactive/docs/gallery/columnchart

Data from https://www.kaggle.com/rtatman/188-million-us-wildfires/home.


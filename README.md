## Project Scope
The study area comprises of 4 sites along the coast of Queensland, Australia selected from the dugong stranding data. These sites are Moreton Bay (152.9, -27.0), Hervey Bay (152.7, -25.2), Townsville (146.8, -19.2) and Cairns (145.8, -16.9).


<img src="https://user-images.githubusercontent.com/115133295/197077697-f602f7fc-7f07-48b4-83a0-36b1ef7fa720.png" width="250">


The variables of interest initially selected were _Nitrogen_, _Temperature_, _Salinity_ and _Light Intensity Above Seagrass_, but from using correlation heatmaps that compared variables, ocean temperature was removed from the project as it had little impact on seagrass density.

[See here for the full project report](https://docs.google.com/document/d/1OzrLt2eJxMpW0C1MZP3s-UoSD7J28XWGu1OpyyPE0wA/) 


## Dataset
Datasets were obtained from:
+ **eReefs BioGeoChemical Model (4km)**: ocean temperature, salinity, total nitrogen, light availablity and seagrass density.
+ **Queensland Government Open Data Portal**: Dugong strandings
+ **NOAA's International Best Track Archive for Climate Stewardshrip (IBTrACS)**: Cyclone Data


## Analysis
A data analysis was conducted in a Jupyter notebook using python and the matplotlib library within.
It is suggested to continue to use these programs to reconduct any analysis.

### Notebooks
We have provided 5 step-by-step notebooks with all coding needed to run the datasets through Jupyter:
1. `Extracting Data`: an overview of how to iput data into the notebook and visualise it

2. `Creating Correlation Heatmaps and GIFs`: an overview of creating correlation heatmaps to compare variables and making GIF's

3. `Timeseries and Slicing Data`: an overview of analysing variables over time and specific locations

4. `Cyclone Analysis`: an overview of the cyclone data analysis using bar graphs


## Contributors
Contributors to the ENVI5809 project include:

+ Claudia Le Quesne
+ Eda Dagli
+ Georgie Terrey
+ Naomi Johnston
+ Yidan Cui

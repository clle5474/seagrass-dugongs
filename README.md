# Dugong strandings: The impacts of extreme weather events and loss of seagrass density on _Dugong_ _Dugon_ strandings in the Great Barrier Reef

<img src="https://user-images.githubusercontent.com/115133295/197125391-b3489661-a23a-48c8-ba05-661a3ca0dcb3.jpg" width="150"> <img src="https://user-images.githubusercontent.com/7201912/197075152-068d0d01-706d-4753-9448-f86a643fa031.png" width="250"> 


## Introduction
The growing rate of global climate change seen in recent decades raises concerns about repercussions on the Earth's environment. The Great Barrier Reef in Queensland, Australia is not only the world’s largest and most diverse reef systems but also a protected World Heritage site. Unfortunately, over the last 20 years, areas of the Great Barrier Reef (GBR) have shown increased signs of environmental degradation mostly resulting from the effects of anthropogenic climate change, which is testing the resilience and threatening the future of the reef. It is having an increasing negative impact on a variety of species which are dependent on the reef for survival including dugongs. Our study and data analysis looks at the impacts of climate change via extreme weather events, namely cyclones and floods, on dugong strandings within the GBR. Our focus is primarily on the impact that these extreme weather events have on coastal seagrass communities that provide food and habitat for dugongs in the GBR and subsequent impact on dugong strandings.


## Project Scope
The study area comprises of 4 sites along the coast of Queensland, Australia selected from the dugong stranding data. These sites are Moreton Bay (152.9, -27.0), Hervey Bay (152.7, -25.2), Townsville (146.8, -19.2) and Cairns (145.8, -16.9).


<img src="https://user-images.githubusercontent.com/115133295/197077697-f602f7fc-7f07-48b4-83a0-36b1ef7fa720.png" width="250">


The variables of interest initially selected were _Seagrass Density_, _Total Nitrogen_, _Temperature_, _Salinity_ and _Light Intensity Above Seagrass_; however, utilising correlation heatmaps that compared variables revealed that temperature was not significantly correlated with seagrass density and was thus excluded from the project.

[See here for the full project report](https://docs.google.com/document/d/1OzrLt2eJxMpW0C1MZP3s-UoSD7J28XWGu1OpyyPE0wA/) 


## Dataset
Datasets were obtained from:
+ **eReefs BioGeoChemical Model (4km)**: Ocean temperature, salinity, total nitrogen, light availablity and seagrass density data
+ **Queensland Government Open Data Portal**: Dugong strandings data
+ **NOAA's International Best Track Archive for Climate Stewardshrip (IBTrACS)**: Cyclone data
+ **Bureau of Meteorology**: Rainfall and flooding data


## Analysis
Data analysis was conducted in Jupyter Notebook using python and the NumPy, pandas, Xarray, Cartopy and matplotlib libraries and packages within.
These are the libraries and packages we suggest to use to reconduct any analysis.

### Notebooks
We have provided 4 step-by-step notebooks with all coding needed to run the datasets through Jupyter:
1. `Extracting Data`: an overview of how to extract and visualise relevant data

2. `Creating Correlation Heatmaps and GIFs`: an overview of creating correlation heatmaps to compare variables and making GIFs to visualise how variables change over time for a particular site

3. `Timeseries`: an overview of analysing variables over time for specific sites with the impacts of relevant cyclone and floods

4. `Cyclone Plotting`: an overview of plotting the tracks of relevant cyclone


## Contributors
Contributors to the ENVI5809 project include:

+ [Claudia Le Quesne](https://github.com/clle5474)
+ [Eda Dagli](https://github.com/edadagli)
+ Georgie Terrey
+ [Naomi Johnston](https://github.com/njoh6333)
+ Yidan Cui

# Exploring False Color Imagery
## A case study about the Eaton and Palisades Fires
### EDS 220 - Homework 4

![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Palisades_Fire_%2854253581167%29.jpg/640px-Palisades_Fire_%2854253581167%29.jpg)

## About
This repository contains all code and outputs for this study on false color imagery. The Eaton and Palisades fire in Los Angeles County were devestating for local communities, damaging thousands of homes and many acres of ecological habitat, leaving deep scars in both the communities they affected and the land itself. In this study, we will visualize the extents of the Eaton and Palisades fires using false color imagery through landsat data and known perimeters of both fires.

These data and code were sourced and developed by Leela Dixit, in collaboration with students, Carmen Galaz García, and Annie Adams as part of a course in the [Master of Environmental Data Science ](https://bren.ucsb.edu/masters-programs/master-environmental-data-science)

## Repository Structure
```│
eds220-hwk4
├── README.md                     
├── hwk4-task2-fire-perimeter-YOURLASTNAME.ipynb # Jupyter notebook for analysis                       
├── .gitignore                    
|   ├── data/                       
│       ├── landsat-palisades-eaton NetCDF file 
│       ├── Eaton fire perimeter shapefile
│       ├── Palisades fire perimeter shapefile            
```
Data are not pushed to GitHub. This is the recommended file structure. See the data section below for downloading data.

## Data
Landsat data are from [Microsoft Planetary Computer data catalogue](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2). These data contain bands for red, green, blue, near-infrared and shortwave infrared, from the Landsat Collection 2 Level-2 collected by Landsat-8. Our data is cropped to areas surrounding the extent of the fires.

Perimeter data are from [Los Angeles County Dissolved Fire Perimeter Data](https://geohub.lacity.org/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about). These data originate from data containing daily snapshots of perimeters, but are dissolved into one layer for these data.

Fire perimeter data: https://geohub.lacity.org/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about
Landsat data: https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

## References
Microsoft Planetary Computer. (2024). Microsoft.com. *Landsat Collection 2 Level-2*.  https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2. Landsat 8-9 OLI/TIRS Collection 2 Level-2 : (10.5066/P9OGBGM6). 11/20/2025.

County of Los Angeles. *Palisades and Eaton Dissolved Fire Perimeters*. (2025). https://geohub.lacity.org/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about. 11/20/2025.

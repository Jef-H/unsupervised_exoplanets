# unsupervised_exoplanets


# TESS Clustering Analysis

## Overview

I'm exploring the clustering patterns between **TESS Project Candidates** and either the **Confirmed Planets** or the **TESS Confirmed Planets**. My goal is to compare these clustering patterns to identify potential similarities. 

This could help pinpoint TESS Project Candidates that exhibit characteristics similar to confirmed planets, potentially highlighting strong contenders for confirmation as exoplanets. Hopefully by the end of this project we'll be able to “cheer for” these candidates in their journey to becoming confirmed!

## Data Summary

- **Confirmed Planets:** 5,811
- **TESS Confirmed Planets:** 591
- **TESS Project Candidates:** 7,358

## Key Questions

1. Are the candidates similar to the planets? or something completely different? 
---

## data source

Alright so there's two data sources used here. The way you get them is go to 
https://exoplanetarchive.ipac.caltech.edu/index.html

- click on TESS Project Candidates
- click Download table on the toolbar
- select all rows and all columns and hit download
- save file as TESS_project_candidates.csv

go back to the home page  https://exoplanetarchive.ipac.caltech.edu/index.html

- click on confirmed planets
- click Download table on the toolbar
- select all rows and all columns and hit download
- save file as Confirmed_planets.csv 


## data files 

TESS_project_candidates.csv ( raw file, download with all rows all columns) 

confirmed_exoplanets_clean.csv (unwanted columns dropped, and in pandas readable) 

## Code

EDA = exploratory data analysis   https://github.com/Jef-H/unsupervised_exoplanets/blob/develop/Unsupervised_EDA.ipynb

majority of the source code = https://github.com/Jef-H/unsupervised_exoplanets/blob/develop/Final_Pass.ipynb



[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

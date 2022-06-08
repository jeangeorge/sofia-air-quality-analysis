# Project - Cloud Massive Data Processing - UFMG - 2021/02
Work of the discipline Cloud Massive Data Processing taught in 2021/02 in the Information Systems course at the Federal University of Minas Gerais (UFMG).

## Overview
Analyze the air quality indices of Sofia, Bulgaria.

## Dataset
We used the [Sofia Air Quality](https://www.kaggle.com/hmavrodiev/sofia-air-quality-dataset) dataset.

## Goal
* Perfm an analysis of the correlation between the attributes present in the database (pressure, temperature, humidity,
P1 (PM10) and P2 (PM2.5)).
* Try to determine which sensors would possibly be defective, performing a clustering of data by latitude and longitude and an analysis in time windows. For clustering, subdivide the bounding box of the city of Sofia into a predetermined number of areas. For each area, determine if there are sensors continuously reporting temperatures that are very different from their neighbors over time.
* Use a Machine Learning algorithm to predict the concentration of PM10 or PM2.5 particles at a given point in space (either continuously, via regression, or discretely, classifying concentrations into levels), using data such as pressure, temperature, humidity and the location itself as features

## Results (pt-BR)
* [Source Code](https://github.com/jeangeorge/pdmn-tp-final/blob/main/tp.ipynb)
* [Final Report](https://www.overleaf.com/read/hxxytbbshvdc) (pt-BR) in the IEEE Conference Template
* [Video](https://www.youtube.com/watch?v=Us0KDIkS45w) showing and explaining our results

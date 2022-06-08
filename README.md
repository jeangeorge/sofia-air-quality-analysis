# Trabalho Final para a disciplina "Processamento de Dados Massivos em Nuvem" - UFMG - 2021/2

## Overview
In this work some analyzes of the database [Sofia Air Quality](https://www.kaggle.com/hmavrodiev/sofia-air-quality-dataset) were performed.

## Goal
- Carry out an analysis of the correlation between the attributes present in the database (pressure, temperature, humidity,
P1 (PM10) and P2 (PM2.5)).
- Try to determine which sensors would possibly be defective, performing a clustering of data by latitude and longitude and an analysis in time windows. For clustering, subdivide the bounding box of the city of Sofia into a predetermined number of areas. For each area, determine if there are sensors continuously reporting temperatures that are very different from their neighbors over time.
- Use a Machine Learning algorithm to predict the concentration of PM10 or PM2.5 particles at a given point in space (either continuously, via regression, or discretely, classifying concentrations into levels), using data such as pressure, temperature, humidity and the location itself as features


## Results
We made a final [report](https://www.overleaf.com/read/hxxytbbshvdc) (pt-BR) following IEEE Conference Template.

We too record a small [video](https://www.youtube.com/watch?v=Us0KDIkS45w) (pt-BR) to show and explain our results.

## Us
Developed by: [Jean George](https://github.com/jeangeorge) e [Luiz Berto](https://github.com/luiz787)

---
title: 'Data Preparation'
date: 2019-02-11T19:27:37+10:00
weight: 5
---

**a. Data collection**

Data of the cases of coronavirus in Hong Kong, the quarantine building list, means of transport, population, as well as testing, are obtained from data.gov.hk, the Hong Kong government's open data source.

**b. Data Cleaning and Wrangling**

The data cases has to be clean to extract only data from January to September. Duplicates will also need to be checked to prevent skewed data analysis. Data Standardization will then ensure the same data types to ensure a fairer comparison and analysis. 

**c. Data Transformation**

As the study analyses the intensity and relationships, the data has to be transformed to the relevant formats before more statistical analysis can be done. Such transformations are converting SpatialPointDataFrame to Point Pattern Processes. Shapefile for the geographic area will need to be converted to owin in order to analysis the points in the study area. 
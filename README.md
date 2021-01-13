# Project Name
Machine Learning Challenge

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
In this homework I was given a NASA Kepler space telescope data set used for finding new planets outside of our solar system. The task was to clean the data and create different machine learning models to find the one with the best accuracy rate for predicting.

## Technologies
* SKLearn (various tools)
* Pandas
* MatPlotLib
* Numpy
* Kruskal

## Code Examples
There are a total of 7 Jupyter files, one for each model and one for the best model (model_3) included in this repository. See each file for code examples.

## Features
This was a tough assignment. One of the problems I experienced was two of the KOI Disposition observations, False Positive and Candidate, were basically synonomous and were causing poor accuracy results. To correct this I combined these two together. Here are the results of the 6 models tested:
* Logistic Regression model 80.09% (model_1 file)
* KNN model 81.12% (model_2 file)
* Random Forest model 89.02% (model_3 file)
* SVM model 76.32% (model_4 file)
* Neural Network model 76.09% (model_5 file)
* Naive Bayes model 87.41% (model_6 file)
* Best Model (best_model file) was the Random Forest model

## Status
Project is: Complete

## Contact
Created by David Stagner (dstagner63@icloud.com)

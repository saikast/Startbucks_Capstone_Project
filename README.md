# Starbucks Capstone Project

This project is a part of the Data Scientist Nanodegree Program by Udacity. The dataset for the project is provided by Starbucks Corporation.

## Project Overview

In this project, we analyze an offer strategy by Starbucks. When Starbucks sends an offer to users of the mobile app, some users might receive the offer, view the offer, and then complete the offer. Others might receive the offer but ignore it. The goal of this project is to predict whether a user would respond to an offer or not, based on demographic data and offer details.

## Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [License](#license)


<a name="introduction"></a>

## Introduction 
This project is part of Udacity's Data Scientist Nanodegree Program in conjunction with Starbucks.

This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one, get one free). Some users might not receive any offer during certain weeks.


<a name="Installation"></a>

## Installation 

The code uses Python, along with Jupyter Notebook. The following libraries are needed:

Pandas
Numpy
Matplotlib
Seaborn
Scikit-learn
Imbalanced-learn


<a name="files"></a>

## File Descriptions 

### Starbucks_capstone_project.ipynb: Jupyter notebook containing the data exploration, preprocessing, model training, and evaluation.

### data/: Directory containing the data for the project. 

It includes the following files:

**portfolio.json**: containing offer ids and meta data about each offer (duration, type, etc.)

**profile.json**: demographic data for each customer

**transcript.json**: records for transactions, offers received, offers viewed, and offers completed

### `Starbucks_capstone_project.html` -  HTML version of the jupyter notebook.

## Results

Our refined model successfully predicts whether a user would respond to an offer or not. 
For more details about the performance of the model, please refer to the Jupyter Notebook.


Link to my article on [Medium](https://medium.com/@saipriyakasturi121/from-data-to-decisions-enhancing-marketing-strategies-through-predictive-modeling-bd8e288d5743).

<a name="license"></a>

## License 
Data provided by Udacity
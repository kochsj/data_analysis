# Seaborn Data Analysis

**Author**: Stephen Koch
**Version**: 1.0.0

## Overview
This file is for analyzing data using linear regression and polynomial regression using seaborn in Jupyter Notebooks. We are using NumPy and Pandas to access and work with data from an [pokemon csv](https://www.kaggle.com/abcsds/pokemon), [housing sales data](https://www.kaggle.com/deltacrot/property-sales), and [world health organization suicide rates](https://www.kaggle.com/szamil/who-suicide-statistics)

## Getting Started

First, make sure that you have python3 installed:
```
$ python3 --version
Python 3.7.5
```
If you do not:
```
$ brew install python
```
You need to have the files locally. Click on the green clone or download button and Download ZIP:

![Click_to_download](../assets/Click_to_download.png)

Navigate to your command line:
```
MacOS: Press command + space to open up the search feature
Search for terminal - This is your command line.
```

In your command line, navigate to this directory:
```
$ cd ~  ##this is your root directory
$ cd Downloads  ##by default: Downloads is a directory inside of your root; and where your file will be downloaded
$ cd data_analysis ##and now you are in this directory
```
This is a collection of Jupyter Nodebooks and CSV files.
Opening the notebooks requires jupyterlab, numpy, pandas, matplotlib, sklearn, and seaborn.
First we need to create a virtual environment to install our package dependencies.
We are using a pipenv virtual environment:
```
$ pipenv install jupyterlab numpy pandas matplotlib sklearn seaborn
```
Your packages will be installed after a short while.
We need to be running in our virtual environment to use our packages:
```
$ pipenv shell
```
From our virtual environment, we can open our jupyter notebooks:
```
$ jupyter lab
```

## Functionality/Architecture
The Jupyter notebooks analyze comma-separated-value files (.csv). In this Jupyter notebook we are using the power of the seaborn package library to read data and render a representative graph. The graphs that we are using are scatterplots and polynomial regressions.

## Change Log
Wed Dec 16 2019 19:28:59<br>Read four csv files and created two Jupyter Notebooks analyzing the data.


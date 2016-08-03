


# Data Science Essentials
## Materials for teaching  

Welcome to the Data Science Essentials. We hope you will find the material provided here useful and compelling. 

## Overview  

This repository contains material for teaching the essential concepts of *data science and machine learning*. The material is built around a series of hands-on lab exercises. The labs are organized into the folders by subject. The material in each folder includes:

- A **README** describing the contents of the folder.
- The **lab documents** themselves, containing step by step directions.  
- Links to a **worked examples** of the labs in the Azure Machine Learning Gallery.  
- Any **code and data files** required for the lab.  
- **Lecture slides**.
- Links to professionally produced **video lectures**.
 
An annotated Table of Contents describing the material in each folder by category can be found below.   

## Getting Started  

You must download the files in this repository to perform the labs and use the other material. You can download the files in this repository in one of two ways. 

- You can download the repository as a **Zip file** by clicking on the **Download ZIP** button in the lower right of the repository main page. Place the **Zip file** in a convenient directory. Click on the **Zip file** icon and select **Extract Here**. You will see the directory structure of the repository extracted. 
- If you are an advanced user, and have **Git Desktop** installed on your computer, you can **Clone** the repository by clicking the **Clone in Desktop** button in the lower right of the repository main page. Your **Clone** will replicate the directory structure of this repository. Information on installing [Git](https://git-scm.com/downloads) and [GitHub](https://help.github.com/articles/set-up-git/) is available online. 

Once you have downloaded the files in this repository continue your setup. Navigate to the **Setup** directory. Open the **Setup-Guide** document and follow the directions. You are then be ready to try some of the lab exercises! 

## Organization  

The labs in this repository are organized into the folders by subject modules. Each folder includes the following materials as appropriate:  

### Lab Exercises

The core of the material in each folder is one or more lab exercises. Each lab provides a hands on experience focused on a specific aspect of data science and machine learning. Each lab document provides step by instructions. 

Some labs are suitable for all students, including business students. Other labs require more advanced techniques, such as R or Python programming. 

### Data and Code

The labs use a variety of tools. All labs use the Azure Machine Learning Studio environment.

Many of the labs use sample datasets provided in Azure ML. Any additional required data can be found in the folders.  

Some labs use R and Python code, which is provided in the folder with the lab. Code can be run by cut and pasting the code and following the directions in the lab documents. 

### Gallery

The final versions of the experiments constructed in each lab are provided in the Azure Machine Learning Gallery. Follow the links provided in the READ me of each folder to view these experiments.  

### Video and Lecture Material

Each category of labs is complemented by professionally produced video lectures. Links to these videos are provided in the README of each folder. The video files themselves are not included in this repository. 

Lecture slides are provided for each module. The PowerPoint files are in the folders along with the lab documents. 

## Contents

This section contains a summary of the contents of each folder. 

- [**Introduction to Data Science** ](https://github.com/snapanalytx/Data-Science-Essentials/tree/master/Introduction-To-Data-Science)contains videos and labs to familiarize students with data science foundational concepts as well as data science technology and tools. The lab focusses on how to get started with Azure Machine Learning as well as how to create and run experiments.
- [**Probability and Statistics for Data Science**] (https://github.com/snapanalytx/Data-Science-Essentials/tree/master/Probability-and-Statistics-for-Data-Science) conatins vidoes that explore random variables and how their probability can be calculated. They also look at distributions of random values for both discrete and continuous variables. Basic statistics that will help explore and understand the values in data are also covered. The lab covers how to work with Summart staistics.
- [**Simulation and Hypothesis Testing**](https://github.com/snapanalytx/Data-Science-Essentials/tree/master/Simulation-and-Hypothesis-Testing) contains videos and labs. The videos cover simulation and confidence intervals as well as an overview of Hypothesis testing. In the lab, you will learn how to create, run and interpret simulations using R or Python. Specifically, the lab will estimate the range of expected profitability for a lemonade stand.
- [**Exploring and Visualizing Data**](https://github.com/snapanalytx/Data-Science-Essentials/tree/master/Exploring-and-Visualizing-Data) contains vides and labs. The videos cover techniques to ingest and explore data in tools such as R, Python and Azure Machine Learning as well as how to visualize data to better understand the patterns and relationships in the data. The lab covers how to use R or Python to visualize and explore data. Two data sets are visualized: Automobiles and Adult Census data.
- [**Data Cleansing and Manipulation Science**](https://github.com/snapanalytx/Data-Science-Essentials/tree/master/Data-Cleansing-and-Manipulation) contains videos and labs to familiarize students with some basic concepts of the data ingestion and flow as well as data cleansing. In the lab, students will learn how to use tools in Azure Machine Learning along with either Python or R to integrate, clean and transform data.
- [**Introduction to Machine Learning**](https://https://github.com/snapanalytx/Data-Science-Essentials/tree/master/Introduction-to-Machine-Learning) contains an introduction to concepts such as *supervised* and *unsupervised learning* and how to use Azure Machine Learning to build  Classification, Regression and Clustering models. Students are also introduced to Azure ML Web Services. The labs teaches how to use Azure Machine Learning to train, evaluate, and publish a classification model, a regression model, and a clustering model.
 

## Labs for Technical Users using R or Python

The following labs teach students advanced techniques using the the R or Python language. Each of these labs offer parallel tracks for either R or Python language users.  

- **Lab I1** in the [Introduction Data Science Technology](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Introduction%20to%20Data%20Science%20Technology)folder walks students thought building a first machine learning model. After the **Setup** process has been completed, this lab is the best starting point for all students
-  **Lab I2** in the [Introduction Data Science Technology](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Introduction%20to%20Data%20Science%20Technology) folder walks students though uploading data files and performing joins in Azure ML. 
-  **Lab T1** in the [Data Transformations for Data Science](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Data%20Transformations%20for%20Data%20Science) folder contains exercises to familiarize students with using R or Python, particularly using the R dplyr package or the Python Pandas package.  
- **Lab T2** in the [Data Transformations for Data Science](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Data%20Transformations%20for%20Data%20Science) folder familiarizes students with the basics of data cleaning and transformation. Topics include treating missing values, duplicates and outliers, as well as scaling numeric data.  
- **Lab Q1** in the [Data Sampling and Quantization](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Data%20Sampling%20and%20Quantization) folder contains exercises in quantizing data using Azure ML, R and Python. 
- **Lab V1** in the [Visualization](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Visualization) folder contains exercises in using both R and Python. The focus is on creating multiple views of a dataset using several common chart types and conditioned plots. The emphasis is on using the R ggplot2 package and Python matplotlib and Pandas plotting.  R and Python code files are included. 
- **M1** in the [Building and Evaluating Models](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Building%20and%20Evaluating%20Models) folder contains exercises for students to perform some simple feature engineering and construct basic machine learning models using Azure ML and R or Python.  
- **M2** in the [Building and Evaluating Models](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Building%20and%20Evaluating%20Models) folder familiarizes students with the process of evaluation machine learning models using Azure ML, R or Python. The emphasis in this lab is on visualization of model errors.
- **Lab R2** in the [Regression](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Regression) folder is an in depth exploration of prediction with regression using Azure ML, R or Python.
- **C3** in the [Classification](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Classification) folder is an in depth exploration of a binary classification problem using Azure ML, R or Python.
- **Lab U2** in the [Clustering](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Clustering) folder is an in depth exploration of unsupervised learning with k-means clustering using Azure ML, R or Python. Students analyze structure in forest fire data, including in-depth evaluation using R or Python graphics. 
- **Lab W1** in the [Publishing Models](https://github.com/AzureDataScienceCurriculum/DataScienceEssentials/tree/master/Publishing%20Models%20as%20Web%20Services) as Web Services folder contains exercises for publishing an Azure Machine Learning Model as a web service. The web service is tested in Excel using a plugin.
- **Lab X1 - Text Minning** provides students with a hands-on overview of mining and preparing text for further analysis. 
- **Lab X2 - Tweet Sentiment Classification** introduces students to text classification. 



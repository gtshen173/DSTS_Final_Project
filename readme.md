# DSTS Final Assignment - U3268781


## Overview

This repository contains the code and resources for **Flight Delay Prediction**. The project is focused on implementing concepts from the **Data Science Technology and Systems** and demonstrates the use of various data processing and machine learning techniques. It also contains the use of AWS Sage Maker.  


## Table of Contents
- [Introduction](#introduction)
- [Folder Structure](#folder_structure)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Model Used](#Model-Used)
- [Expected Output](#expected-output)



## Introduction
The repository contains code written in Python, which is provided in the form of a Jupyter Notebook (`onpremises.ipynb` and `oncloud.ipynb`). The code covers various tasks such as data preprocessing, analysis, and model(on cloud and on premise) implementation. 
It also have tableau file (`Flight Delay Distribution Dashbaord.twb`) where drashboard was created. It also contains folder named (`oncloud.html`) which has result codes of ran on cloud.

## Folder Structure

- `data/` : This folder contains the dataset(s) used for the project. (Make sure to add the data manually if necessary.)
- `html/` : Contains any output results, including trained models, plots, and evaluation metrics done on AWS Sage Make Cloud.
- `notebooks(ipynb)/` : Jupyter notebooks detailing exploratory data analysis, model development, and testing for both onpremise and on AWS cloud .

## Installation
To run the code, you need to set up a Python environment with the necessary dependencies. Follow the instructions below to set it up.

### Prerequisites
- Python 3.8 or above
- Jupyter Notebook
- Tableau Desktop to run Flight Delay Distribution Dashboard.twb file(Optional)
- Git (optional, for cloning the repository)
- AWS Sage Maker instance and user 
- Required Python libraries: pandas, numpy,seaborn,geopandas, matplotlib, scikit-learn, etc.

### Installing libraries
You can install the required libraries by running:


```bash
pip install libraries 
```
    or 
```bash
conda install libraries
```
or 

```bash
pip install pandas numpy seaborn geopandas matplotlib scikit-learn ast
```


## How to Run

You can run the code in your local machine or in AWS Sage Maker

### Run in Local Machine

Clone the repository as follows 
```bash
git clone https://github.com/gtshen173/DSTS_Final_Project.git
```
It has two Parts 
- :Part A Importing, Understanding Data with visulizations and Modelling on Permise 
- :Part B: Predictive Modelling with both on Cloud.

**To run only models in Local Machine**

Open the file onpremises.ipynb file in Jupyter Notebook or Visual Studio Code and execute the cells in sequence to run the code.

Note: make sure you download files from https://ucstaff-my.sharepoint.com/:f:/g/personal/ibrahim_radwan_canberra_edu_au/Er0nVreXmihEmtMz5qC5kVIB81-ugSusExPYdcyQTglfLg?e=bNO312 and put into data/zipfiles as 60 zip files.

Here it will create two CSV files which will be used on cloud.


**To run only models in AWS Sage Maker**

- 1. Start a lab.
- 2. Create a notebook instance and name it "oncloudproject".
- 3. Open Jupyter Lab and upload this notebook into it.
- 4. upload the two combined CVS files (combined_csv_v1.csv and combined_csv_v2.csv), which you created in Part A of this project.
- 5. Open the file oncloud.ipynb file and execute the cells in sequence to run the code.


### Model Used

- On Permise
    Logistic Regression 
    Logistic Regression balanced class
    Random Forest (additional)

- On Cloud
    Linear Leaner  
    XGBoost

## Expected Output 

**Data Analysis:** Insightful visualizations and statistics will be generated to help understand the dataset.

**Classification Models:** The output for classification includes confusion matrix, ROC Curve, Classification Matrices like Accuracy, F1 Score, Percision, and Recall for above models. 

**Tableau Visualizations:** If you using FLight Delay Distribution Dashboard.twb, you'll get interactive dashboard visualizations related to Flight Delay Distribution on various factors.



**Author:** <br>
**Tshering Gyeltshen | U3268781** <br> 
**Master of Data Science in AI and Computational Modelling Student**<br>
**Faculty of Science and Technology**<br>
**University of Canberra**<br>
**Email: U3268781@uni.canberra.edu.au**<br>

####                Thank You
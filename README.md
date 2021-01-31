# Bertelsmann-Arvato-Project

### Table of Contents
1. [Blog Post](https://rahulgupta1.medium.com/customer-segmentation-report-for-arvato-financial-services-e2f03f149f96)
2. [Libraries used](#library)
3. [Project Overview](#overview)
4. [The Process](#process)
5. [File Descriptions](#files)
6. [Licensing, Authors, and Acknowledgements](#license)

Here is the link for the blog post on medium. [report](https://rahulgupta1.medium.com/customer-segmentation-report-for-arvato-financial-services-e2f03f149f96)

## Project Overview<a name="overview"></a>
The objective of the project is to determine the chances that a person from mailout campaign could become a new customer.

The project is divided into several subtasks:
1.	Data Analysis and Preprocessing;
2.	Customer Segmentation Report;
3.	Supervised Learning Predictive Model;
4.	Kaggle Competition;

The training data is protected under the Terms and Conditions and is unavailable for public sharing.

## Libraries used <a name="library"></a>

I have used the following list of libraries in this project.

#### numpy, pandas, seaborn, matplotlib, sklearn, time, os, sys

## The Process <a name="process"></a>

1. Customer Segmentation Report
You'll begin the project by using unsupervised learning methods to analyze attributes of established customers and the general population in order to create customer segments.

2. Supervised Learning Model
You'll use the previous analysis to build a machine learning model that predicts whether or not each individual will respond to the campaign.

3. Kaggle Competition
Once you've chosen a model, you'll use it to make predictions on the campaign data as part of a Kaggle Competition. You'll rank the individuals by how likely they are to convert to being a customer, and see how your modeling skills measure up against your fellow students.

## File Descriptions <a name="files"></a>

* `Arvato Project.ipynb`: Jupyter notebook that contains all code, data visualizations and machine learning model. The metrics used in this projects are AUC-ROC, PCA and 
Grid Search. The algorithms I have explored are XGBoost and AdaBoost.

Data is provided by Bertelsmann Arvato
* `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany. 891,211 persons (rows) x 366 features (columns).
* `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company. 191,652 persons (rows) x 369 features (columns)
* `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign. 42,982 persons (rows) x 367 (columns).
* `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign. 42,833 persons (rows) x 366 (columns).

2 more files for describing attributes:
* `DIAS Attributes - Values 2017.xlsx`: Explains values encoding
* `DIAS Information Levels - Attributes 2017.xlsx`: Explains column names meanings

## Results <a name="results"></a>

The final predictions were made on the Udacity_MAILOUT_052018_TEST.csv. The score of the final performance of my model was 0.7859. 

## Licensing, Authors, Acknowledgements <a name="license"></a>
This web application was developed as part of the [Udacity Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025).

I would like to thank Bertelsmann Arvato Analytics for providing the data used for this project and for all the mentors at Udacity.

Author: Rahul Gupta Copyright 2021

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

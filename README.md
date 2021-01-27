# Bertelsmann-Arvato-Project

### Table of Contents
1. [Project Overview](#overview)
2. [The Process](#process)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#license)


## Project Overview<a name="overview"></a>
“A Customer Segmentation Report for Arvato Financial Solutions” was one of the proposed projects for the Data Scientist Nanodegree Program by the Udacity. The main objective of the project is to determine the descriptive portrait of the potential customer and are chances that a new person from the targeted mailout campaign could become a new customer.
Arvato has provided several dataset files that have demographic information about the general population of Germany, current customers of the company, targeted mailout campaign outcomes, and two files with a description of the demographic features.

The project is divided into several subtasks:
1.	Data Analysis and Preprocessing;
2.	Customer Segmentation Report;
3.	Supervised Learning Predictive Model;
4.	Kaggle Competition;

The training data is protected under the Terms and Conditions and is unavailable for public sharing.

## The Process <a name="process"></a>

1. Customer Segmentation Report
You'll begin the project by using unsupervised learning methods to analyze attributes of established customers and the general population in order to create customer segments.

2. Supervised Learning Model
You'll have access to a third dataset with attributes from targets of a mail order campaign. You'll use the previous analysis to build a machine learning model that predicts whether or not each individual will respond to the campaign.

3. Kaggle Competition
Once you've chosen a model, you'll use it to make predictions on the campaign data as part of a Kaggle Competition. You'll rank the individuals by how likely they are to convert to being a customer, and see how your modeling skills measure up against your fellow students.

## File Descriptions <a name="files"></a>

All the data is provided by Bertelsmann Arvato Analytics and there are given four files for this project:
* `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
* `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
* `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
* `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

Additionally, there were 2 more files for describing attributes:
* `DIAS Attributes - Values 2017.xlsx`: Explains values encoding 
* `DIAS Information Levels - Attributes 2017.xlsx`: Explains column names meanings

Each row in the demographic data files represents and describes a person as well as his or her environment, such as their household, building, and neighborhood. The general structure of the AZDIAS and CUSTOMERS data files is similar. MAILOUT...TEST and MAILOUT…TRAIN are provided for the development and testing of the supervised model.
The training data is protected under the Terms and Conditions and is unavailable for public sharing.


## Results <a name="results"></a>
According to the 2nd part of the project with customers segmentation, the fact of a person being a potential customer is positively affected by the actuality of the last transaction, gender, whether the person from GDR or FRG, with fine social status, the person is dominant minded and dreamily, and fine family type. While financial typology: money saver, number of 6-10 family houses in the PLZ8, and density of inhabitants per square kilometer have a negative impact.

According to the 3rd part of the project with supervised models, the final predictions were made on the Udacity_MAILOUT_052018_TEST.csv, which was pre-processed as the training set. While the private score of the final performance of my model was 0.79, on Kaggle competition it managed to hold 0.79 of accuracy as well according to the AUC-ROC evaluation metric. 

## Licensing, Authors, Acknowledgements <a name="license"></a>
This web application was developed as part of the [Udacity Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025).

Author: Rahul Gupta Copyright 2021

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

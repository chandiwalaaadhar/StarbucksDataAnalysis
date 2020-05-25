
This is a Data Analysis and ML project on Starbucks Datasets.
# My Blog Post Link
[https://medium.com/@chandiwalaaadhar/this-analysis-will-make-you-understand-how-starbucks-is-no-1-in-world-df754c48687e](https://medium.com/@chandiwalaaadhar/this-analysis-will-make-you-understand-how-starbucks-is-no-1-in-world-df754c48687e)

## Installation & Usage
- [X] Make sure you have Jupyter Notebook Installed on your Device

``` 
git clone https://github.com/chandiwalaaadhar/StarbucksDataAnalysis

git jupyter notebook 
```
  
Open Starbucks_Capstone_notebook.ipynb, then run all of the code tabs
For Visualisation and ML model Open Data_visualisation.ipynb
## Project Overview
Customer satisfaction drives business success and data analytics provides insight into what customers think. For example, the phrase "360-degree customer view" refers to aggregating data describing a customer's purchases and customer service interactions.

The Starbucks Udacity Data Scientist Nanodegree Capstone challenge data set is a simulation of customer behavior on the Starbucks rewards mobile application. Periodically, Starbucks sends offers to users that may be an advertisement, discount, or buy one get on free (BOGO). An important characteristic regarding this dataset is that not all users receive the same offer.

This data set contains three files. The first file describes the characteristics of each offer, including its duration and the amount a customer needs to spend to complete it (difficulty). The second file contains customer demographic data including their age, gender, income, and when they created an account on the Starbucks rewards mobile application. The third file describes customer purchases and when they received, viewed, and completed an offer. An offer is only successful when a customer both views an offer and meets or exceeds its difficulty within the offer's duration.
## Dataset Files Included
**portfolio.json** — contains offer ids and metadata about each offer. It contains the following attributes:

**profile.json** — demographic data for each customer.

**transcript.json** — records for transactions and usage of offers.

## Metrics
* Accuracy Score
* F1-Score
## Libraries Used
* Matplotlib
* Seaborn
* Scikit-Learn
* Numpy
* Pandas

## Process Used
#### CRISP-DM process is used to work on this project

## Business Questions Answered with the help of this Project
* Most successful of offers in BOGO, Discount, and Informational. (Generated Maximum Revenue)
* Which User Id’s response to all the offers and which don’t respond to any of the offers?
* Which Starbucks Customer contributes to maximum sales (by Age and Gender)?

## Conclusions
The Maachine Learning model used to predict if the offer would be Success or Fail is RandomForestClassifier, with an accuracy of 65%.

## Future Implementations
Looking to do Feature Engineering for better impelemtations of Machine Learning Algorithm and building a recommender system to recommend offers to users.
## Contributer(s)
[Aadhar Chandiwala](https://github.com/chandiwalaaadhar)
## Acknowledgement(s)
* Dataset from Udacity by Starbucks
## Licensing
Licensed by [MIT License](https://choosealicense.com/licenses/mit/)

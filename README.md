# US-Accidents-Analysis

## Installation
All required packages are in the [requirements.txt](https://github.com/michaelarman/US-Accidents/blob/master/requirements.txt) file

## Project Motivation
I came across this dataset on Kaggle and it had a lot of information. A lot of questions
could be answered from this dataset so I wanted to see what I can discover from it. I also
wanted to try GeoSpatial Analysis and Geoplotting.
For this project, I wanted to discover:
1. Which States have the most accidents? Which Cities have the most accidents?
2. The distribution of when accidents happen throughtout the day
3. Does weather affect the severity of an accident?
4. Can we predict where an accident will occur without training any locational data?

## File Descriptions
There are 3 notebooks available. 
- [US Accidents Analysis](https://github.com/michaelarman/US-Accidents/blob/master/US%20Accidents%20Analysis.ipynb)
is a notebook for initial exploration and visualizations, as well as data preparation and feature engineering.
- [BERT Classifier](https://github.com/michaelarman/US-Accidents/blob/master/BERT%20Classifier.ipynb) classifies the severity of an 
accident by using the text descriptions given in the dataset. This uses BERT deep learning and it achieved 91% accuracy.
- [Classification Model](https://github.com/michaelarman/US-Accidents/blob/master/Classification_Model.ipynb) this is a notebook for
classifying and predicting where the accident occurs. Sadly I did not have enough RAM to actually run the model and validate it but 
I was able to get the feature importance.

## Findings
Findings can be found in this [medium post](https://medium.com/@michaelarman/this-might-make-you-think-twice-about-driving-in-certain-circumstances-in-the-u-s-9fc6d625c346)

## References
The Dataset:
Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. "A Countrywide Traffic Accident Dataset.", 2019.
Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.

# US-Accidents-Analysis

## Installation
All required packages are in the [requirements.txt](https://github.com/michaelarman/US-Accidents/blob/master/requirements.txt) file

## Project Motivation
I came across this dataset on Kaggle and it had a lot of information. A lot of questions
could be answered from this dataset so I wanted to see what I can discover from it. I also
wanted to try GeoSpatial Analysis and Geoplotting.
## From a Business Perspective
From a business perspective it would be very informative to know where most accidents occur and if there is a pattern and when the accidents occur most. A business that would find this informative would be towing companies because they would be able to increase their response rate and minimize time to the accidents if they know where most of them occur per state.

There is a lot to analyze with this dataset. Some questions can be:

1. Which States has the most accidents? This would help us know how to distribute the amount of tow trucks
2. What time do most accidents occur? More workers should be available during those times
3. What affects the severity of the accident? We would be able to minimize the number of severe accidents if we know the factors contributing to them.
4. Can we predict an accident? This could help tow truckers anticipate a job coming.

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
Some of the findings can be found in this [medium post](https://medium.com/@michaelarman/this-might-make-you-think-twice-about-driving-in-certain-circumstances-in-the-u-s-9fc6d625c346)

### Evaluation and Results

- Which state has the most accidents? California - perhaps that suggests more tow truckers are needed in that state
- What time do most accidents occur? Differs per state but accidents happen most before and after work hours (6-8am & 3-6pm)
- What affects the severity of the accident? Duration, and Weather Condition
- Can we predict an accident? This is included in the Classification Model notebook
- Can we predict the severity of an accident? This is included in the BERT notebook

## References
The Dataset:
- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. "A Countrywide Traffic Accident Dataset.", 2019.
- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.

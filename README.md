# Rental Listing Inquiries

## Overview

This project aims to predict `interest_level` of rental listings based on dataset provided by [renthop.com](url), an apartment listing website.

Official contest website: [https://www.kaggle.com/c/two-sigma-connect-rental-listing-inquiries/overview](url)

## Package Installation

The programs are run using Jupyter Notebook (Anaconda 3.7). Instructions to install can be found here: [https://www.anaconda.com/distribution/](url)

Some parts of our code require NTLK and TextBlob package in Python to run, this is however an optional step:

- `conda install -c anaconda nltk`
- `conda install -c conda-forge textblob`

## Code Execution

Open notebook by navigating to project folder (extracted) then run `jupyter notebook` in the command line. The folder should consists of the following files:

- Exploratory Analysis.ipynb
- Missing Values (Preprocessing 1).ipynb
- Handle Missing and Formatting (Preprocessing 2).ipynb
- Outlier Detection (Preprocessing 3).ipynb
- Images and Texts Feature Extraction.ipynb

Simply run all the cell in each file to get the results (`Cell --> Run All`). Code should be executed in the above order to produce desired output pipeline:

- train.json
- trainNaN.json
- trainCleaned.json
- trainCleanedOutliers.json 
- trainTextExtract.json

The final `json` file will contain cleaned data with extracte features ready for classification.

## Project report
The following link contains the final report for the project
https://docs.google.com/document/d/1LmIuy9tu1nXb0zlv1nn4fZHxsllORyHPX4FympsD434/edit?usp=sharing

## Contributors

This repo is part of CMPT 459 (Data Mining) project and is contributed by students:

- Leo Mai
- Jason Nguyen
- Brian Lee

## References

- [Ultimate Guide to deal with Text Data using Python](https://www.analyticsvidhya.com/blog/2018/02/the-different-methods-deal-text-data-predictive-python/)
- [3 Beginner-Friendly Techniques to Extract Features from Image Data using Python](https://www.analyticsvidhya.com/blog/2019/08/3-techniques-extract-features-from-image-data-machine-learning-python/)

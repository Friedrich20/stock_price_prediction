# README

This repo serves as the code implementation of the project assigned in the module Data Acquisition and Processing Systems ELEC0136.

# Description

In this project, we will apply machine learning techniques to perform and extend the two traditional financial methods used in stock prediction, which are known as Technical Analysis and Fundamental Analysis. The closing stock prices of Apple Inc. (AAPL) from April 2017 to May 2020 are used as the only predictor in Technical Analysis while Fundamental Analysis has taken other related information into account such as New York Times articles with regard to the company as well as the market price of Nasdaq Composite reflecting the overall economy. The experiment results show that compared to Technical Analysis, the addition of external information in Fundamental Analysis can remarkably contribute to the increasing accuracy of stock prediction, leading to a drop of Mean Squared Error (MSE) from 87.1 to 0.69. Both of the analysis methods are based on Facebook’s Prophet for time series prediction.

# Results

|        Method        |  Model  | mean squared error (MSE) |
| :------------------: | :-----: | :----------------------: |
|  Technical Analysis  | Prophet |          87.09           |
| Fundamental Analysis | Prophet |           0.69           |

# Having problems?

If you run into problems, please either file a github issue or send an email to uceewta@ucl.ac.uk.

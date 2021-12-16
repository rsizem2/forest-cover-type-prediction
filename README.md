# README

This repository contains my work on classifying forest cover types using various cartographic features. The data comes from the UCI ML repository and can be found at [this link](https://archive.ics.uci.edu/ml/datasets/covertype).

This repository was inspired by the tabular playground series [Kaggle competition](https://www.kaggle.com/c/tabular-playground-series-dec-2021), part of a competition series involving synthetic data generated from a real dataset. Usually the originating dataset is kept a secret however for this particular competition, they revealed the original dataset and did not anonymize the features. 

As I was working on the synthetic dataset I thought it would be interesting to test the same techniques on the original data as well. However this ended up cluttering up notebooks and I noticed the same techniques wouldn't always work on both datasets due to corruptions introduced into the synthetic data. For example, in the original dataset the soil type variable is a single categorical variable one-hot encoded into 40 different binary columns. However, in the synthetic data one observation can have no soil type or multiple soil types, so there is not necessarily a single soil type for each row.


# Goals

My goals with this repository are to test out various feature engineering techniques as well as more modern ML frameworks to see if I can't improve on the original results. To this end, I will use the same training, validation, test splits as the original paper when necessary to see if any approaches are resulting in improvements.
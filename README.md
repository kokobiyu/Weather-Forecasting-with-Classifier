# Weather Forecasting with Classifier

Weather forecasting is an important science. Accurate forecasting can help to save lives and minimize property damage. It's also crucial for agriculture, allowing farmers to track when it's best to plant or helping them protect their crops. And it will only become more vital in the coming years. We are going to make a simple weather forecasting to predict the upcoming weather based on available data.

## Project Overview
The dataset I'm using here is Seattle weather from Kaggle.
The Machine Learning models used are:
1. XGB Classifier
2. K-Nearest Neighbors Classifier
3. AdaBoost Classifier

Metrics that we’ll use for evaluating the models are accuracy and F1-score metric. We choose accuracy as a matrix because it will be used as a reference for algorithm performance if the data set has a very close number of False Negatives and False Positives. However, if the numbers are not close, then I should use the F1 Score as a reference.

## Summary
This article is intended to:
* Beginner Machine Learning model building
* Analyze datasets with simple visualizations
* Train Various Machine Learning Models to choose the most suitable one

We use simple methods to do several things such as cleaning data, exploring data, building models and evaluating models. We ended up achieved highest accuracy on AdaBoostClassifier. This model needs “precipitation”, “temp_max”, “temp_min”, and “wind” as input. In the future we can use this model (with some improvements) to help improve our renewable energy sources so they become more reliable and efficient, for example we can identify optimal layout and geographical location of the solar and wind power plants.


My blogspot: https://medium.com/@abiyyushofficial/weather-forecasting-with-python-machine-learning-beginner-50bf41ddf4e

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

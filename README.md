# Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases

## Objective:
The objective of this project is to provide an illustrative analysis to hypothetical authorities in US to have the opportunity to prioritize environmental policies and implement effective measures to address air pollution and its impact on health. This analysis was done by investigating the causal effects between different pollutants, demographic data, and the number of Melanoma cancer incidents in a specific population.

## Dataset:
A collection of data made from the following datasets extracted from [DATA.gov](https://data.gov/):
* Air Pollution dataset
* Chronic disease indicator dataset
* Demographic dataset

## Methods:
* Data collection & preprocessing [Open Notebook](https://github.com/MiladMt11/Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases/blob/9d3470a39f04b5059e2692afca616679485a5d2f/1.%20Preprocessing.ipynb)
* Web scraping and text mining: [Open Notebook](./2. News and Tweets Analysis.ipynb)
  - using different APIs to match articles and tweets with desired keywords
  - create word clouds and perform sentiment analysis
* Perform exploratory analysis of the data [Open Notebook](./3. Exploratory Analysis.ipynb)
* Predict the rate of cancer occurrences for the two coming years based on historical data:
  - developing an [ARIMA](https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average) model to create a baseline model [Open Notebook](./4. Arima Baseline Model.ipynb)
  - developing an RNN deep learning model as the predictor [Open Notebook](./5. Forecasting with RNN.ipynb)
  - performing explainable AI analysis to understand the different feature effects using [SHAP](https://shap.readthedocs.io/en/latest/)
* Analyze the final results and provide insights [Open Notebook](./6. Result Analysis.ipynb)

# Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases

## Objective:
The objective of this project is to provide an illustrative analysis to hypothetical authorities in US to have the opportunity to prioritize environmental policies and implement effective measures to address air pollution and its impact on health. This analysis was done by investigating the causal effects between different pollutants, demographic data, and the number of Melanoma cancer incidents in a specific population.

## Dataset:
A collection of data made from the following datasets extracted from [DATA.gov](https://data.gov/):
* Air Pollution dataset
* Chronic disease indicator dataset
* Demographic dataset

## Methods:
* Data collection & preprocessing [1. Preprocessing](https://github.com/MiladMt11/Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases/blob/9d3470a39f04b5059e2692afca616679485a5d2f/1.%20Preprocessing.ipynb)
* Web scraping and text mining: [2. News and Tweets Analysis](https://github.com/MiladMt11/Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases/blob/940f072729e2f6579bea846be6714cfd13f61874/2.%20News%20and%20Tweets%20Analysis.ipynb)
  - using different APIs to match articles and tweets with desired keywords
  - create word clouds and perform sentiment analysis
* Perform exploratory analysis of the data [3. Exploratory Analysis](https://github.com/MiladMt11/Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases/blob/940f072729e2f6579bea846be6714cfd13f61874/3.%20Exploratory%20Analysis.ipynb)
* Predict the rate of cancer occurrences for the two coming years based on historical data:
  - developing an [ARIMA](https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average) model to create a baseline model [4. Arima Baseline Model](https://github.com/MiladMt11/Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases/blob/940f072729e2f6579bea846be6714cfd13f61874/4.%20Arima%20Baseline%20Model.ipynb)
  - developing an RNN deep learning model as the predictor [5. Forecasting with RNN](https://github.com/MiladMt11/Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases/blob/940f072729e2f6579bea846be6714cfd13f61874/5.%20Forecasting%20with%20RNN.ipynb)
  - performing explainable AI analysis to understand the different feature effects using [SHAP](https://shap.readthedocs.io/en/latest/)
* Analyze the final results and provide insights [6. Result Analysis.ipynb](https://github.com/MiladMt11/Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases/blob/940f072729e2f6579bea846be6714cfd13f61874/4.%20Arima%20Baseline%20Model.ipynb)

## Installation

Follow these steps to set up the project locally.

### Prerequisites

You will need to have Python installed on your machine. You can download it [here](https://www.python.org/downloads/).

### Install

1. Clone the repository:

    ```bash
    git clone https://github.com/MiladMt11/Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Investigating-The-Impacts-of-Air-Pollution-on-Cancer-Cases
    ```

3. Install the required Python packages using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the notebooks in the order of the numbering in their names.

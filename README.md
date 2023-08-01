# Model🔥

# Predictive Model for GDP Fluctuations

## Overview

This repository contains the code and data for developing a predictive model to forecast the impact of exchange rate and inflation rate on our country's Gross Domestic Product (GDP) fluctuations. The model aims to provide valuable insights into the relationship between these economic indicators and GDP performance, helping stakeholders make informed decisions and anticipate economic trends.

## Table of Contents

- [Problem Statement](#problem-statement)
- [Data](#data)
- [Models Used](#models-used)
- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Problem Statement

The objective of this project is to build a predictive model that can accurately forecast how changes in exchange rate and inflation rate impact our country's GDP fluctuations. By analyzing historical data on exchange rates, inflation rates, and GDP growth, the model seeks to provide actionable insights into the underlying economic relationships.

## Data

The dataset used for training and testing the model can be found in the "data" folder. It includes three CSV files:
- Annual GDP.csv
- Inflation Rates.csv
- Key CBK Indicative Exchange Rates.csv

These datasets contain information on annual GDP, inflation rates, and exchange rates, respectively, spanning several years.

## Models Used

The project utilizes the following predictive models:

1. Linear Regression: A simple model to establish a baseline relationship between exchange rate, inflation rate, and GDP fluctuations, assuming a linear connection.

2. Support Vector Machine Regression (SVR): To capture non-linear relationships between economic indicators and GDP fluctuations. Hyperparameter tuning is performed to optimize the model's performance.

3. Decision Trees and Random Forests: These models can handle both regression and classification tasks, providing insights into complex interactions between the features and the target variable.

## Getting Started

To use the code and reproduce the results:

### Requirements

- Python 3.7 or higher
- Required Python packages: pandas, scikit-learn, matplotlib

### Usage

1. Clone the repository:

```
git clone https://github.com/your-username/predictive-model.git
cd predictive-model
```

2. Install the required packages:

```
pip install -r requirements.txt
```

3. Run the model training and evaluation script:

```
python train_and_evaluate.py
```

4. The results will be displayed, including the model performance metrics (MSE, R-squared) and the best hyperparameters for SVR.

## Results

The model performance and evaluation results can be found in the "results" folder. It includes plots, performance metrics, and model evaluation summaries.


## Contributing

We welcome contributions to enhance the model, improve its accuracy, or address any issues. Please feel free to open a pull request or submit an issue.

## Acknowledgments

We acknowledge the CBK community for providing the datasets used in this project.

For any inquiries or further details, please contact Us
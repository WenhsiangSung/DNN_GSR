## Discovering Soil Moisture Flow Equation from Data via Sparse Regression


Public Datasets and Codes for Data-driven discovery of soil moisture flow governing equation: A sparse regression framework. Water Resources Research. 

## Requirements

- Python 3.6.13
- Matplotlib
- Numpy
- Pandas
- Tensorflow 1.15


## Datasets

See Data folder, details can be found in journal article. This dataset is generated by solving Richardson-Richards equation by Ross method. 
Please see:

Zha, Y., Shi, L., Ye, M., & Yang, J. (2013). A generalized Ross method for two-and three-dimensional variably saturated flow. Advances in Water Resources, 54, 67-77. https://doi.org/10.1016/j.advwatres.2013.01.002

## Codes

Use step1.py (finite methods for clean data and automatic differentiation methods for noisy data) to generate a candidate library, then input into step2 sparse regression.

## Citations

Song, W., Shi, L., Wang, L., Wang, Y., & Hu, X. (2022). Data-driven discovery of soil moisture flow governing equation: A sparse regression framework. Water Resources Research, 58, e2022WR031926. https://doi.org/10.1029/2022WR031926

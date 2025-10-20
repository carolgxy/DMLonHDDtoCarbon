# DML on HDD to Carbon

## Intro
Increasing climatic volatility has intensified the frequency and persistence of cold extremes, driving higher heating demand and carbon emissions from the building sector. However, the socioeconomic and infrastructural mechanisms shaping the relationship between winter thermal stress and emissions remain insufficiently quantified.
In this study, we employ a Double Machine Learning (DML) framework to estimate the causal association between Heating Degree Days (HDD) and CO₂ emissions across six major emitting regions, while controlling for a range of socioeconomic, technological, and geographic confounders. The complete implementation of the DML framework is provided in the notebook HDD_dml_py.ipynb.

## Setup
The code was executed on Google Colab using Python 3.12.11, primarily based on the DoubleML library (version 0.10.1).
For detailed documentation on the DoubleML package, please refer to the official guide: https://docs.doubleml.org/stable/index.html.

## Data
The provided dataset contains all variables required to run the HDD_dml_py.ipynb notebook and reproduce the analysis results.
Comprehensive details on data sources, preprocessing, and variable construction are available in our manuscript.

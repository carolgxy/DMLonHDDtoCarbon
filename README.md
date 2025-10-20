# DML on HDD to Carbon

## Intro
Increasing climatic volatility has intensified the frequency and persistence of cold extremes, driving higher heating demand and carbon emissions from the building sector. However, the socioeconomic and infrastructural mechanisms shaping the relationship between winter thermal stress and emissions remain insufficiently quantified.
In this study, we employ a Double Machine Learning (DML) framework to estimate the causal association between Heating Degree Days (HDD) and CO₂ emissions across six major emitting regions, while controlling for a range of socioeconomic, technological, and geographic confounders. The complete implementation of the DML framework is provided in the notebook HDD_dml_py.ipynb.

## Setup
The code was executed on Google Colab, primarily based on the DoubleML library (version 0.10.1).
For detailed documentation on the DoubleML package, please refer to the official guide: https://docs.doubleml.org/stable/index.html.

## Data
The full dataset for the six regions covered by our study is too large to be uploaded, so we provide the sample dataset of Russia here. It contains all variables required to run the HDD_dml_py.ipynb and reproduce the analysis results for Russia.
Comprehensive details on data sources, preprocessing, and variable construction are available in our manuscript.

## Reproducibility Notice
Machine learning models inherently involve random components (e.g., parameter initialization, sampling, or data splitting).
To ensure the robustness of our results, the code is configured to run five independent iterations of the DML estimation and report the averaged results.
However, please note that minor variations may still occur across runs due to the stochastic nature of the algorithms, even with fixed random seeds.

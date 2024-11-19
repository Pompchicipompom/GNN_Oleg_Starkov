# Missing Values Imputation with Graph Neural Networks in Oil & Gas Datasets

## Overview

Imputation of missing values in data is a critical task in numerous real-world applications. Traditional methods such as mean interpolation, spline interpolation, and regression models are commonly used to address this problem. However, these approaches often fail to capture the complex spatial and temporal dependencies and non-linear relationships present in complex datasets. The emergence of graph neural networks (GNNs) represents a promising solution, as GNNs are capable of capturing complex spatio-temporal dependencies in data.

This repository focuses on leveraging GNNs for imputation tasks in the Oil & Gas industry, particularly for filling missing values in well logs and time-series data. The results of this work aim to improve the training of various machine learning models in the petroleum industry, including but not limited to well classification, time series forecasting, and drilling anomaly detection.

## Objectives

The primary objectives of this project are as follows:
- Explore available implementations of GNNs for missing value imputation.
- Prepare data for use with GNNs, including:
  - Constructing graphs that represent relationships between wells or between drilling parameters.
  - Preprocessing tabular and temporal data.
- Develop a GNN-based model to fill missing values and select appropriate evaluation metrics.
- Compare the performance of the GNN-based approach against classical imputation methods (e.g., forward/backward fill, KNN, non-negative matrix factorization).
- Provide a thorough analysis of the results and draw conclusions on the effectiveness of the GNN model.

## Restrictions

The project aims to implement a GNN model for missing data imputation that outperforms other baseline imputation methods.

## Data Sources

The project utilizes data from the following sources:
- [Taranaki Basin Curated Well Logs (New Zealand)](https://developer.ibm.com/exchanges/data/all/taranaki-basin-curated-well-logs/) – Well logs data.

## Tags

- Data Imputation
- Graph Neural Networks (GNNs)
- Oil & Gas Data
- Machine Learning

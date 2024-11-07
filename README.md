# GNN_Oleg_Starkov
Missing Values Imputation with Graph Neural Networks in Oil&Gas datasets
"Imputation of missing values in data is a critical task in numerous real-world applications. Traditional methods such as mean interpolation, spline interpolation, and regression models are commonly used to address this problem. However, these approaches often fail to capture the complex spatial and temporal dependencies and non-linear relationships present in complex datasets.
The emergence of graph neural networks (GNNs) represents a promising solution, as GNNs are capable of capturing complex spatio-temporal dependencies in data. The purpose of this work is to investigate the capabilities of GNNs to both fill missing values in an existing data sequence and in separate, unrelated sequences.
The results of the work will be useful in training different ML models in the petroleum industry (starting from wells classification and moving to time series forecasting and drilling anomalies detection).
To achieve the research goal, the following steps need to be taken:
•        Explore available implementations of GNNs for missing value imputation
•        Prepare data to work with GNNs. This includes constructing graphs of relationships between wells (or between drilling parameters) and preprocessing tabular or temporal data.
•        Develop a model to fill in missing values using GNNs and select metrics to evaluate the effectiveness of the model.
•        Compare the obtained results with classical methods (forward/backward fill, KNN, non-negative matrix factorization, etc.) of gap filling and draw conclusions.

Restrictions: Implement a model for missing data imputation using GNN, that can outperform other imputation baselines.
Data: Time-series data, well logs data
Data sources: Groningen, Volve, New Zealand – well logs; 
US Produced Waters Geochemicals – time series
Tags: data imputation, GNNs, time series!!"
Date used: taranaki-basin-curated-well-logs (New Zealand)

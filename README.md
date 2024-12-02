# 🌐 Missing Values Imputation with Graph Neural Networks in Oil & Gas Datasets

### 📜 **Overview**

Imputing missing values is a critical step in data preprocessing across numerous real-world applications. Traditional methods—such as mean interpolation, spline interpolation, and regression models—struggle to capture **complex spatial and temporal dependencies** and **non-linear relationships** in datasets. 

**Graph Neural Networks (GNNs)**, however, offer a powerful alternative, as they excel at modeling complex **spatio-temporal relationships**. This repository explores the use of GNNs to tackle missing value imputation tasks specifically in the **Oil & Gas industry**, improving workflows such as:
- **Well classification**
- **Time series forecasting**
- **Drilling anomaly detection**

---

### 🎯 **Objectives**

The main goals of this project are:
1. **Explore and benchmark implementations of GNNs** for missing value imputation.
2. **Prepare data** for use with GNNs:
   - Construct graphs that represent relationships between wells or drilling parameters.
   - Preprocess both tabular and temporal data.
3. **Develop a GNN-based imputation model**, including:
   - Selecting optimal evaluation metrics.
   - Tuning the architecture and hyperparameters.
4. **Compare GNN performance** with classical methods:
   - Forward/backward fill.
   - K-Nearest Neighbors (KNN).
   - Non-negative Matrix Factorization (NMF).
5. **Deliver insights** by analyzing results and effectiveness of the GNN-based imputation approach.

---

### 🛠️ **Project Features**

- 📊 **Dataset Preparation**:
  - Create meaningful relationships between **wells** using spatial, temporal, and parametric data.
  - Implement feature engineering to enrich input data for GNN models.

- 🧠 **Model Development**:
  - Design and train Graph Neural Networks for missing value imputation.
  - Implement multiple GNN architectures, such as **GCN**, **GraphSAGE**, and **GAT**.

- ⚡ **Performance Comparison**:
  - Evaluate GNNs against classical imputation methods to demonstrate their superiority.
  - Utilize **custom metrics** to measure the effectiveness of imputation techniques.

---

### 📚 **Data Sources**

This project utilizes data from the following source:

- **[Taranaki Basin Curated Well Logs (New Zealand)](https://developer.ibm.com/exchanges/data/all/taranaki-basin-curated-well-logs/):**
  - Comprehensive well logs dataset including:
    - Spatial coordinates.
    - Drilling and production parameters.
    - Temporal trends.

---

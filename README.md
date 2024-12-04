# Walmart-Sales-Forecast
This project is to help us understand how time series models work, use Machine Learning to forecast sales, and help business owners make economical decisions.

## Course CISC684 - Intro to Machine Learning

## **Project Overview**

Accurate sales forecasting is crucial for optimizing operations in the retail industry. This project tackles the **Walmart Store Sales Forecasting** problem with a structured, experimental approach:
- **Baseline Models:** LSTM and GRU for time-series data.
- **Advanced Models:** Experimentation with **TimesNet** and **Graph Neural Networks (GNNs)** for enhanced performance.
- **Multimodal Learning:** Combining temporal and static features for a comprehensive forecasting model.

---

## **Key Features**

1. **Data Preparation**:
   - Handle missing values for CPI, unemployment, and markdowns.
   - Normalize data for consistent scaling across features.
   - Extract time-based features like `Year`, `Month`, and `Week`.

2. **Feature Engineering**:
   - Create lag features for `Weekly_Sales` grouped by `Store` and `Dept`.
   - Develop multimodal datasets combining temporal patterns and static features.

3. **Modeling**:
   - **Baseline Models:** LSTM and GRU for benchmarking.
   - **Advanced Techniques:** TimesNet and GNNs for experimenting with novel approaches.
   - **Multimodal Models:** A two-branch architecture integrating temporal and static features.

4. **Evaluation**:
   - Monitor training and validation losses for all experiments.
   - Ablation studies to analyze the impact of model components and hyperparameters.

---

### Work in Progress...

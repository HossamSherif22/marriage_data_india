# marriage_data_india

### README: Marriage Data Analysis Project - India

#### **Project Overview**

This project performs a comprehensive data analysis of marriage trends in India, focusing on key demographic indicators and their socio-economic correlations. Using publicly available datasets, the project aims to uncover patterns and insights related to age at marriage, regional variations, the prevalence of child marriage, and the impact of factors such as education and economic status. The analysis is presented through a series of visualizations and a written report detailing the key findings.

#### **Data Sources**

The primary data for this project is sourced from reliable, publicly available surveys and reports:

* **National Family Health Survey (NFHS)**: A large-scale, multi-round survey that provides extensive data on family planning, health, and key demographic indicators, including detailed information on marriage for women and men. The project utilizes data from NFHS-4 and NFHS-5 to analyze trends over time.
* **Census of India**: Provides historical and current data on marital status, age at marriage, and population distribution by various demographic characteristics.
* **UNICEF and other NGO reports**: Supplementary data and analytical reports from organizations like UNICEF on the state of child marriage in India.

#### **Methodology**

1.  **Data Collection and Cleaning**: Raw data from the NFHS and Census reports are collected, cleaned, and processed to handle missing values and inconsistencies.
2.  **Exploratory Data Analysis (EDA)**: Initial analysis is performed to understand the data's structure, distributions, and basic trends. This includes calculating the mean age at marriage, analyzing the distribution of marital status by age, and identifying outliers.
3.  **Hypothesis Testing**: Statistical tests are conducted to examine specific hypotheses, such as whether there is a significant difference in the age at marriage between urban and rural populations.
4.  **Trend Analysis**: Time-series analysis is performed to track changes in marriage rates and mean age at marriage over the last few decades.
5.  **Correlational Analysis**: The project explores the correlation between marriage data and other socio-economic indicators, including:
    * Educational attainment (literacy rates).
    * Household wealth index.
    * Geographical location (state-wise and urban/rural breakdowns).
6.  **Data Visualization**: Key findings are visualized using a variety of plots (bar charts, line graphs, heatmaps) to make complex data easily understandable.

#### **Key Findings**

* **Increasing Age at Marriage**: The median age at first marriage for women in India has been steadily rising, indicating a positive social shift.
* **Decline in Child Marriage**: The prevalence of marriage before the legal age of 18 has seen a significant decline, although it remains a persistent issue in certain regions.
* **Strong Correlation with Education**: The analysis reveals a strong inverse correlation between educational attainment and the likelihood of early marriage; women with higher education are more likely to marry later.
* **Geographical Disparities**: Significant variations in marriage trends are observed across different states, with some states showing much higher rates of child marriage than the national average.

#### **Tools Used**

* **Programming Language**: Python
* **Libraries**:
    * `Pandas` for data manipulation and analysis.
    * `NumPy` for numerical operations.
    * `Matplotlib` and `Seaborn` for data visualization.
    * `Statsmodels` or `SciPy` for statistical testing.

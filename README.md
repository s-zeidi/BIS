# Business Information Systems Optimization - Purchase Order Handling

## Overview
This project focuses on optimizing the purchase order handling process within a multinational company, leveraging process mining techniques to enhance efficiency and compliance. It utilizes Python's PM4Py library and the Celonis platform to analyze and improve various procurement processes, including 2-way and 3-way matching, and consignment processes.

## Key Features
- **Data Exploration and Preprocessing**: Analyzed variant frequency, activity frequency, and start/end activity patterns to understand the dataset.
- **Process Discovery**: Applied three key process mining algorithms—**Alpha Miner**, **Inductive Miner**, and **Heuristic Miner**—to discover process models from the dataset.
- **Data Segmentation**: Categorized the data into 4 segments (2-way match, 3-way match Invoice after GR, 3-way match Invoice before GR, and Consignment) for focused analysis.
- **Celonis Integration**: Further explored the dataset using Celonis to identify bottlenecks and optimize throughput times across different segments.

## Machine Learning & Techniques Used
- **Python & PM4Py**: Utilized for data preprocessing, outlier detection, and applying process mining algorithms.
- **Celonis Platform**: Used for in-depth analysis, data segmentation, and identifying process bottlenecks, leveraging its advanced analytics and visualization tools.

## Results and Insights
- Identified critical bottlenecks such as delays in invoice processing and approval steps.
- Provided insights into key process segments, offering suggestions for automation, process optimization, and resource management.

## Suggestions for Improvement
- **Automation**: Implement robotic process automation for invoice matching and approval workflows.
- **Process Optimization**: Streamline the purchase order approval and invoice receipt processes.
- **Resource Allocation**: Optimize staffing and working hours for handling high-volume periods and process bottlenecks.


 Use Python and PM4Py to explore and preprocess the log file, and Celonis for advanced process analysis.

## 📦 Libraries Used

- `pandas` – For loading and manipulating tabular datasets.
- `numpy` – For numerical operations and array management.
- `matplotlib.pyplot`, `seaborn` – For creating statistical visualizations and insightful plots.
- `wordcloud` – To generate word clouds that visualize the most frequent terms in textual data.
- `scipy.stats` – Used for statistical analysis, specifically `chi2_contingency` to test for associations between categorical variables.
- `pm4py` – A comprehensive process mining library used for:
  - Converting event logs into process models
  - Evaluating process models based on generalization and simplicity
- `os` – For interacting with the file system (e.g., reading directories or file paths).
- `google.colab` – Used to mount and access Google Drive files when running in Google Colab.



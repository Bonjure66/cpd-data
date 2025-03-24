# cpd-data
A dataset for testing the efficiency of change point detection methods

Environmental Signal Monitoring Dataset

Overview：

This repository contains a benchmark dataset specifically designed for testing changepoint detection methods in environmental signal monitoring. The dataset provides time series data with labeled changepoints to evaluate the effectiveness and efficiency of various detection algorithms.

Dataset Description：

Size: 10,001 data points (including header row)

True Changepoints: 6

Format: Excel (.xlsx)

Changepoint Locations: at indices 1858, 4151, 5259, 6330, 7350, 8964

Background：

Environmental signal monitoring relies on dynamic sensing technology to capture the evolving characteristics of environmental signals through high-precision sensor arrays. This process generates continuous time series data streams that reflect system state transitions. In
this context, shifts in the data stream correspond to transitions between different steady states of the monitored environment.
Changepoint detection is crucial for automatically identifying these state transitions in real-time environmental monitoring.

Data Structure：

The dataset is contained in a single Excel file with two columns:cpd data.xlsx

Data: The environmental signal measurement values

Label: Binary indicator where:

0: Normal data point (9,994 points)
1: Changepoint (6 points)


The changepoints are located at indices 1858, 4151, 5259, 6330, 7350, and 8964, representing transitions between different environmental states.

Purpose：

This benchmark dataset is specifically designed for:

Evaluating the effectiveness of changepoint detection algorithms：

1.Testing the efficiency of detection methods in environmental monitoring contexts

2.Comparing performance across different detection approaches

3.Developing more robust algorithms for real-time environmental state transition detection


Contact：

If you have any questions regarding this dataset, please leave a comment or contact: Dr. Eduardo

Email: vcodntunfc84@outlook.com

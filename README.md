# ICCBR2021-Financial-TS-Similarity
This repository relates to the paper "Measuring Financial Time Series Similarity With a View to Identifying Profitable Stock Market Opportunities" which was published in the proceedings of the International Conference on Case Based Reasoning (ICCBR) 2021

Notebook order is:
1. get_train_df.ipynb - This notebook contains the code to download the raw pricing data from Yahoo! Finance
2. get_windows.ipynb - This code generates the rolling windows. NOTE: This notebook will save ~5GB of data in the directory you run it in. You can reduce the time period or number of stocks considered to use less memory.
3. evaluation.ipynb - The code for the evaluations
4. similar_plots.ipynb - Code for plotting the most/least similar cases based on the proposed metric


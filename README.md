# ICCBR 2021 Paper on Financial Time Series Similarity
This repository relates to the paper "Measuring Financial Time Series Similarity With a View to Identifying Profitable Stock Market Opportunities" which was accepted for presentation at the International Conference on Case Based Reasoning (ICCBR) 2021.

NB: All plots are interactive and do not render on github. Please view them by pasting the URL on [Jupyter nbviewer](https://nbviewer.jupyter.org/). For example, the similar_plots.ipynb notebook can be seen [here](https://nbviewer.jupyter.org/github/rian-dolphin/ICCBR2021-Financial-TS-Similarity/blob/main/similar_plots.ipynb).

Notebook order is:
1. get_train_df.ipynb - This notebook contains the code to download the raw pricing data from Yahoo! Finance
2. get_windows.ipynb - This code generates the rolling windows. NOTE: This notebook will save ~5GB of data in the directory you run it in. You can reduce the time period or number of stocks considered to use less memory.
3. evaluation.ipynb - The code for the evaluations
4. similar_plots.ipynb - Code for plotting the most/least similar cases based on the proposed metric

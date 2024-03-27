This Jupyter Notebook (consumer_traffic.ipynb) is focused on analyzing consumer traffic data to understand cross-sell rates and traffic source patterns.

Data Request

The notebook utilizes a dataset containing consumer traffic information. The dataset includes various features such as traffic source, cross-sell status, order creation date, DNA test activation date, and more.
Feel free to contact me at eeshanarayan27@gmail.com and request for data.

Data Cleaning

The notebook begins with data cleaning steps to ensure the dataset's quality and integrity.
Missing values are handled by dropping rows with missing values in specific columns and converting date columns to datetime format.
Additional cleaning involves converting columns to the appropriate data types and handling errors where necessary.

Cross-Sell Analysis

Cross-sell rates between different customer types and ACOM (Ancestry Composition) subscriptions are calculated.
Overall cross-sell rate and cross-sell rates specific to new and existing registrations are determined.

Exploratory Data Analysis (EDA) Plots

Cross-Sell Rate by Top 5 Traffic Sources (Bar Plot): Visualizes the cross-sell rate for the top 5 traffic sources.
Cross-Sell Rate Distribution by Top 5 Traffic Sources (Box Plot): Shows the distribution of cross-sell rates across the top 5 traffic sources.
Distribution of Cross-Sell Rate (Histogram): Displays the distribution of cross-sell rates across the dataset.
Correlation Matrix (Heatmap): Illustrates the correlation between numerical features in the dataset.
Cross-Sell Rate Distribution by Top 5 Traffic Sources (Violin Plot): Depicts the distribution of cross-sell rates for each of the top 5 traffic sources using a violin plot.

Requirements

To run this notebook, ensure you have the following Python libraries installed:

pandas
matplotlib
seaborn

Usage

Clone the repository or download the consumer_traffic.ipynb file.
Open the notebook in Jupyter Notebook or JupyterLab.
Run each cell sequentially to execute the code and generate the analysis results and plots.

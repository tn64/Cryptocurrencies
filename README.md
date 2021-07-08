
# Cryptocurrencies
<img src="https://github.com/tn64/Cryptocurrencies/blob/main/Resources/pexels-david-mcbee-730547.jpg"></br>
<!-- Photo by David McBee from Pexels -->

## Overview
In this analysis I used unsupervised machine learning to discover what 
cryptocurrencies in the dataset are on the trading market and 
how they could be grouped to create a classification system for a
potential investment portfolio.

## Results
I first cleaned the data to find the 532 tradable cryptocurrencies. 
Next, I scaling the data I reduced the dimensions of the dataset using PCA and then clustered the cryptocurrencies using K-Means.
Finally, I visualized the results with a 3D scatter plot and an hvplot 
scatter plot.

The plots show four different groups of cryptocurrencies, two of which
are clustered closely together (these also contain the most cryptocurrencies).

Results are:

3D Scatter Plot with PCA Data and Clusters
<img scr="https://github.com/tn64/Cryptocurrencies/blob/main/Resources/3D_Scatter.png"></br>

hvplot
<img scr="https://github.com/tn64/Cryptocurrencies/blob/main/Resources/hvplot_scatter.png"></br>



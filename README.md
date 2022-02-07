# Cryptocurrencies

## Analysis Overview
The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.  

The following methods were used for the analysis:
- preprocessing the database
- reducing the data dimension using Principal Component Analysis
- clustering cryptocurrencies using K-Means
- visualizing classification results with 2D and 3D scatter plot.

## Results
Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.


### Clustering Cryptocurrencies using K-Means - Elbow Curve
We don't know what would be the output of the analysis, so unsupervised machine learning was used to identify clusters of the cryptocurrencies.  
An elbow curve was produced using the K-Means method iterating on k values from 1 to 10. 
![Elbow Curve](https://github.com/leblabac/cryptocurrencies/blob/afd5fe7635201145c3f1dc06e33c1c7c53feda89/Resources/elbow_curve.png)

### Visualizing Cryptocurrencies Results  
#### 3D-Scatter plot
![3D=Scatter Plot](https://github.com/leblabac/cryptocurrencies/blob/afd5fe7635201145c3f1dc06e33c1c7c53feda89/Resources/3d_Plot.png)

#### Tradable Cryptocurrencies Table  
![Tradable Cryptocurrencies Table](https://github.com/leblabac/cryptocurrencies/blob/afd5fe7635201145c3f1dc06e33c1c7c53feda89/Resources/trading_table.png)

#### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply  
![2d-Scatter Plot](https://github.com/leblabac/cryptocurrencies/blob/afd5fe7635201145c3f1dc06e33c1c7c53feda89/Resources/scatterplot.png) 

## Summary
We have identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need would need to be further analyzed for investment use by clients.

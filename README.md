# Cryptocurrencies
The purposes of this analysis is to use unsupervised machine learning on cryptocurrency dataset.This analysis processes the data for analysis, clusters the data, reduces dimensions, and reduces the principal components using PCA. 

## Deliverables

Deliverable 1: Preprocessing the Data for PCA

* Data was cleaned and prepared for machine learning models

Deliverable 2: Reducing Data Dimensions Using PCA

* Using Principal Component Analysis (PCA) algorithm, I reduced the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

![PC](/Images/PC.png)

Deliverable 3: Clustering Cryptocurrencies Using K-means

* Using the K-means algorithm, I created an elbow curve using hvPlot to find the best value for K from the pcs_df. Then, I ran the K-means algorithm to predict the K clusters for the cryptocurrency data.

![elbow_curve](/Images/elbow_curve.png)

Deliverable 4: Visualizing Cryptocurrencies Results

* The analysis visualizes the distinct groups that correspond to the three principal components you created in Deliverable 2. Below is a 3D plot created using Plotly Express and hvplot. 

![3D_Scatter](/Images/3D_Scatter.png)

* The analysis also includes a table of currently tradable cryptocurrencies using the hvplot.table() function. A hvplot scatter plot is created using  the data in the table.

![scatter_plot](/Images/scatter_plot.png)


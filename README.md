# Cryptocurrencies

## Purpose

The purpose of the following project deliverables was to create an analysis Accountability Accounting, an investment bank that is interested in offering a new cryptocurrency investment portfolio for its customers. Unsupervised learning was used for this analysis since there was no known output to begin with. To group the cryptocurrencies, a clustering algorithm was put to use and data visualizations have been leveraged to showcase the findings.

## Project Deliverables

The following four project deliverables for this analysis can be found in the [crypto_clustering.ipynb](https://github.com/hollyouellette/Cryptocurrencies/blob/main/crypto_clustering.ipynb) document located in this repository:

   **_Deliverable 1_**: 
   In the deliverable the dataset was preprocessed in order to performance Principal Component Analysis.
   
   **_Deliverable 2_**: 
   A Principath Comoponenet Analysis algorithm was applied to reduce the dimensions of the DataFrame to three principal components. These dimensions were then placed into a new DataFrame.
   
   **_Deliverable 3_**: 
   Using hvPlot, in this deliveable an elbow curve was created to find the best value for K from the previously created DataFrame. Once the K value was identified, a K-means algorithm was run to predict the K clusters for the cryptocurrencies data.
   
  **_Deliverable 4_**: 
  This deliverable contains visualizations of the distinct groups that correspond to the components created in Deliverable 2. The visualizations created were scatter plots with Plotly Express and hvplot. In addition to this, a table with all the currently tradable cryptocurrencies was created using the hvplot.table() function. 


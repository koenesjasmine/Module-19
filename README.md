# Module-19

## Overview
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. They have asked us to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. Since there is no known output for what they are looking for we will be utilizing unsupervised machine learning to gather the data into usable results

## Analysis

- Preprocess the Data for PCA
- Reduce Data Dimensions Using PCA
- Cluster Cryptocurrencies Using K-means
- Visualize Cryptocurrencies Results

## Visualization

After processing the data with the above steps we achieved the following output visualizations.
![image](https://user-images.githubusercontent.com/124399950/222405122-52fb134b-301b-4a23-8706-4c126ef2e96a.png)


We created an Elbow Curve chart that shows the initial point is at 4 clusters.

![image](https://user-images.githubusercontent.com/124399950/222404637-ef430950-44c7-46c4-bda7-139452fb522d.png)


We further visualize the data creating a 3D plot to visualize the 4 Classes of currency.

![image](https://user-images.githubusercontent.com/124399950/222405741-1c3d3d12-bf58-434d-80aa-56bd10afba22.png)
![image](https://user-images.githubusercontent.com/124399950/222405891-086e7ad9-d4b1-48b9-a964-e14173e5680e.png)
![image](https://user-images.githubusercontent.com/124399950/222405855-8da84158-67f6-4d2f-a5c7-f9f861562fe0.png)

Lastly we created a scatter plot that shows the different CoinNames and Algorithms upon hover.

![image](https://user-images.githubusercontent.com/124399950/222405406-61570afc-8a49-4bd4-8c2b-7de977418ced.png)

## Summary
overall unsupervised learning is a great tool when we dont know how we want to classify or group our data but we believe that such a classification may be useful for us to simplify our understanding or to help us make decisions. 
these clusters may help us to diversify our portfolio of crypto currencies by trying to invest in a few from each group where feasible. 

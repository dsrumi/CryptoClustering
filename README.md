**CryptoClustering/Unsupervised Machine Learning


For Module 19 challenge,we used Python and unsupervised learning to predict if crytocurrencies are affected by 24 hour or 7 day price change.

First, we loaded the crypto_market_data.csv into a DataFramem and got the summary statistics and plot the data to see what the data looks like before proceeding.

We prepared the Data using the StandardScaler() module from scikit-learn to normalize the data from the CSV file and created a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

 Then we used the elbow method to find the best value for k and to  plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.

 Next we clustered the cryptocurrencies for the best value for k and created a scattr plot.

 Using the original scaled DataFrame, we performed a PCA and reduce the features to three principal components. we retrieve the explained variance to determine how much information can be attributed to each principal component and then created a new DataFrame with the scaled PCA data and set the "coin_id" index from the original DataFrame as the index for the new dataframe.

 again we used elbow method to find best value for k and plotted a line grapgh and then clusterd the cryptocurrencies husing pCA Dataframe and created a scatter plot.

# CryptoClustering
Module 11 Challenge

The following steps need to be completed in this challenge:
Load the required Panda and skikit-learn libraries and dependecies.
Next the provided CSV file will need to be imported using read_csv, displaying the data to review what is in the CSV file.

The data then needs to be prepared by using the StandardScaler module from scikit-learn                                            
The user then needs to find the best value for k by creating both a k list and inertia list,
creating a loop, predicting the clusters and then using a line plot to visualize the data.

Once the number of clusters(k value) is discovered using the Elbow Curver the User creates 
the model using KMeans process of creating the model, fitting the model and then predicting the model
with the original scaled DataFrame. This included creating a copy of the original dataframe to keep the integrity of the original data. 
Using the copy of the original data frame, the user needed to add a new column and display the data.
Lastly plot the clusters by using a scatter plot and setting the x to price_change_percentage_24th and the y to price_change_percentage_7d

It is now time to optimize the clusters by utlizing the Princial Component Analysis (PCA).
Create the PCA model using the n_compents, then utlizing 'fit_transform on the original scaled data.
The user will need to retreive the variance using the explained_variance_ratio tool and answer that is the total explanied variance for the 3 componenets.

The user will now need to create a new Data frame with the PCA data and display a sample.
The user then needs to find the best value for k by creating both a k list and inertia list,
creating a loop, predicting the clusters and then using a line plot to determine the best k value.

Once the number of clusters(k value) is discovered using the Elbow Curver the User creates 
the model using KMeans process of creating the model, fitting the model and then predicting the model
with the original scaled DataFrame. This included creating a copy of the original dataframe to keep the integrity of the original data. 
Using the copy of the original data frame, the user needed to add a new column and display the data.
Lastly plot the clusters by using a HVplot.scatter and setting the x to PCA1 and the y to PCA2.
At this point the user should also import the hvplot pandas since this was not part of the original required Pandas.

Since the file has unclear instructions, the user should also plot the clusters using a scatter plot.

Lastly, the user will need to write code to determine the weights of each feature on each principal commponent and 
answer which features have the strongest positive or negative influence on each component. 

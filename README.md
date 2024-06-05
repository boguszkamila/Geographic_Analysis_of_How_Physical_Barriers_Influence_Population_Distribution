# Geographic_Analysis_of_How_Physical_Barriers_Influence_Population_Distribution
The study explores how natural and man-made obstacles such as mountains, urban infrastructure impact where people live and settle. The findings aim to highlight patterns and provide insights into the spatial dynamics of human habitation.

## Steps:
1. Exploratory data nalysis
   - missing values (checking MCAR,MAR,MNAR), visualization by missingno
   - removal observations for the missing values of microsatellites whose deficiencies represent no more than 3% of the data with the omission of microsatellites that obtained high correlation values and those that had common deficiencies
   - checking standard deviation before and after deletion
   - missing value imputation by MICE and mean values, checking results by standard deviation
   - removing outliers, computing the interquartile range (IQR) by determining the difference between the 25th percentile (Q1) and the 75th percentile (Q3) of the data
   - removing outliers, visualization longitude and latitude points
   - correlation and data distribution analysis, shapiro-wilk, spearman correlation
     
2. Principal component analysis
3. Clustering  
   - DBSCAN, selecting hyperparameters using silhouette score
   - K-Means and Spectral Clustering, evaluation of the clusters number by using silhouette score
  

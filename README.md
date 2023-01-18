# Identifying Customer Segments of a mail-order sales company

1. First we perform data cleaning on the general population dataset.

2. Next we wrap all the data cleaning steps inside a function to auto-clean datasets in one fell swoop. Data imputation is done wherever necessary afterwards.

3. Using PCA, we reduce dimensionality and retain enough principal components to explain about 85% of the cleaned & imputed general population dataset.

4. We cluster the cleaned & imputed general population dataset using the KMeans algorithm and appropriately select the number of components by finding the elbow of the inertia vs number of components plot.

5. We then use the previous steps on the cleaned & imputed customer dataset to identify which of the previously identified clusters are overrepresented/underrepresented in the customers dataset.

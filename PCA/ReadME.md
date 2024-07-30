This is ReadME for Part 1

### 1.1 Observations

As much variation as feasible is retained while the dataset's number of features is reduced through PCA. When dealing with high-dimensional data, as in the case of the given Pictionary Dataset, this can be especially helpful. As a result, we see that when the number of dimensions in the data produced by PCA is reduced, kNN computations are comparatively quicker since there are less characteristics to take into account when creating the distances.

We see for number of components around 200 to 250, the model performs better and is more accurate than full feature dataset

We find that the model generalises better when PCA is used because it would otherwise tend to overfit as the number of features increased. As can be seen from the figure above, utilising PCA with the right number of features allows us to obtain results that are more accurate when compared to data that has high dimensionality.

### 1.2 Observations

The most significant direction of variance in the data is represented by the first principal component (PC1) of the analysis. The most frequent or dominating patterns in the drawings may be captured by PC1 for the drawer. PC1 can represent for the guesser the most prevalent traits or patterns used to guess the artwork.

Second Principal Component, PC2, reflects the second most important direction of variance and is orthogonal (i.e., uncorrelated) to PC1. PC2 may record changes or patterns unique from those in PC1 in the drawer's casing. PC2 can be seen by the guesser as further features that aid in further refining guesses.

The third most important direction of variance is represented by the third principal component, or PC3. It catches extra data variances that PC1 and PC2 did not take into account.
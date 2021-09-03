# Given enough resources:

run dbscan to get the labels, choose k = number of unique labels - i
- i = 0 if no outliers
- i = 1 if there are outliers (assuming all outliers get the same label (as in sklearn))

# If that is not the case: T_T

1. choose a large k
2. run kmeans
3. check minimun distance between different clusters
5. if it's too small, then choose a smaller k and repeat until the minimum distance between clusters is no insignificant

This too seems very expensive.


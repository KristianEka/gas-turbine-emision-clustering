# gas-turbine-emision-clustering
 Implementing machine learning by comparing the accuracy of the clustering algorithm on turbine gas emissions

## Datasets 💾
- https://archive.ics.uci.edu/ml/datasets/Gas+Turbine+CO+and+NOx+Emission+Data+Set

## Algorithms 🤖
- K-Medoids (PAM)
- CLARA

## Package 📦︎
- readxl
- Amelia
- ggplot2
- GGally
- knitr
- caret (confusion matrix)
- openintro
- dplyr
- cluster (cluster analysis)
- factoextra (cluster visualization)
- clValid (cluster validation)

## Conclusion 💻︎
![image](https://user-images.githubusercontent.com/69257405/213000643-3d62eed8-8a74-4424-8561-ebfa0c407eb6.png)

- PAM Connectivity is lower than CLARA, that means PAM is better than CLARA
- PAM Dunn Index is bigger than CLARA, that means PAM is better than CLARA
- PAM Silhouette is closer to one than CLARA, that means PAM is better than CLARA

However, in terms of speed, CLARA clustering is faster because it is designed to cluster with large amounts of data.

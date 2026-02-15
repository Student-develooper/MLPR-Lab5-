# MLPR-Lab5-

Aim: -
The main aim of this project is to understand and apply distance-based ML algorithms such as K-Nearest Neighbours(KNN) and K-Means clustering. In this assignment, HSV colour features (Hue and Saturation) were extracted from face images and used to perform clustering and classification.

Methodology: -
The following steps were performed in this project:
Converted the images from BGR colour space to HSV colour space.
Extracted Hue and Saturation values as features.
Applied K-Means clustering to group similar face regions.
Used KNN algorithm to classify images based on distance.
Applied cross-validation to evaluate model performance.
Visualised clusters and centroids using scatter plots.

Results & Visualisations: -
K-Means Clustering Output
The clustering results show how faces are grouped based on similarities in Hue and Saturation values.
Template Image Prediction
The template image was classified into one of the clusters using the trained model, demonstrating how distance-based prediction works.

Key Findings: -
Hue and Saturation features are effective for grouping similar facial regions.
Choosing a small value of K in KNN makes the model sensitive to noise (high variance).
Choosing a large value of K makes the model more generalised but may increase bias.
Cross-validation helps in selecting the optimal value of K and improves model reliability.

Conclusion:-
This assignment demonstrates that distance-based algorithms like KNN and K-Means are simple yet powerful techniques for classification and clustering tasks. The performance of these models strongly depends on the choice of distance metric and the value of K. Proper tuning and evaluation help improve the overall model performance.

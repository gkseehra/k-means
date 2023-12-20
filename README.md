# K-Means

## Overview
This project contains three distinct implementations of the K-Means clustering algorithm. Each implementation showcases a different approach to initializing centroids and determining the stopping condition for the algorithm. These variations provide insights into the efficiency and accuracy of the K-Means algorithm under different scenarios.

### Implementations

1. **Lloyd K-Means**: 
   - **Initialization**: Centroids are randomly initialized.
   - **Stopping Criteria**: The algorithm runs until the average change in centroid values between two consecutive iterations is less than a specified threshold.
   - **Centroid Update**: The mean of the data points assigned to a centroid is calculated to determine the new centroid position.

2. **K-Means with SSE Stopping Criteria**: 
   - **Initialization**: Centroids are randomly initialized.
   - **Stopping Criteria**: The algorithm continues until the change in the Sum of Squared Error (SSE) between the centroid and its data points, compared to the previous iteration, falls below a threshold value.
   - **Centroid Update**: Similar to the Lloyd K-Means approach.

3. **K-Means++**: 
   - **Initialization**: Centroids are initialized using a probability distribution calculated for all data points. The probability for each data point is D(x)^2 / Σ(D(x)^2), where D(x) is the Euclidean distance between the data point and the nearest already chosen centroid.
   - **Stopping Criteria**: Same as Lloyd K-Means.
   - **Centroid Update**: Same as Lloyd K-Means.

## Getting Started
To use this repository, clone it to your local machine and open the Jupyter Notebook. Ensure that you have Jupyter Notebook and the necessary Python libraries installed.

## Tools Used
- Python 3.x
- Jupyter Notebook

## Future Scope

1. **Module Conversion**: Transform the Jupyter Notebook (ipynb) into a standalone k-means Python module. This will enable direct import and usage of these K-Means implementations in various Python projects, much like any standard library.
2. **Performance Optimization**: Investigate and implement strategies to enhance algorithm performance, especially for handling larger datasets.
3. **Interactive Visualization Development**: Create interactive visualizations to demonstrate the clustering process, aiding in better understanding and analysis.

## Author
- Gurleen Kaur (gurleenkseehra@gmail.com).

## Contributions
Contributions and suggestions are welcomed to expand the repository's scope.

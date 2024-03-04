## Sampling Techniques in Machine Learning


Sampling techniques are used in machine learning to create representative subsets of data for training and evaluation. This README provides an overview of common sampling techniques and their applications in machine learning.

### Common Sampling Techniques
## 1. Random Sampling
Random sampling involves selecting a random subset of data from a larger dataset. This is useful when the data is uniformly distributed, and there are no specific criteria for selecting samples.

## 2. Systematic Sampling
Systematic sampling involves selecting every nth element from a dataset. This is useful when the data is ordered, and there is a pattern to the sampling.

## 3. Stratified Sampling
Stratified sampling involves dividing the data into strata based on specific criteria and then sampling from each stratum. This is useful when there are different groups in the data that need to be represented in the sample.

## 4. Bootstrapping
Bootstrapping involves creating multiple samples by resampling with replacement from the original dataset. This is useful for estimating the sampling distribution of a statistic or for creating confidence intervals.

## 5. Cluster Sampling
Cluster sampling involves dividing the data into clusters and then sampling from each cluster. This is useful when the data is geographically dispersed or when there are natural groupings in the data.

### Sampling Techniques for Imbalanced Data
In machine learning, it's common to encounter imbalanced datasets where one class is significantly more prevalent than the other(s). In such cases, using sampling techniques can help balance the dataset and improve model performance.

## 1. Random Oversampling
Random oversampling involves randomly duplicating instances from the minority class to balance the dataset.

## 2. SMOTE (Synthetic Minority Over-sampling Technique)
SMOTE involves creating synthetic samples of the minority class by randomly choosing one of its k-nearest neighbors and generating a new instance in the line segment joining them.

## 3. ADASYN (Adaptive Synthetic Sampling Approach for Imbalanced Learning)
ADASYN is similar to SMOTE, but it puts more emphasis on generating samples near the decision boundary.

## 4. SMOTE-ENN (SMOTE and Edited Nearest Neighbors)
SMOTE-ENN first applies SMOTE to generate synthetic samples, then applies Edited Nearest Neighbors to remove noisy samples from the majority class that are misclassified by a k-nearest neighbors classifier.

### Conclusion
These are just a few examples of the sampling techniques that can be used in machine learning projects. The choice of sampling technique depends on the nature of the data and the specific requirements of the problem. Experiment with different techniques to find the best approach for your project.

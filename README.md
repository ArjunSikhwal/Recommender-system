# Recommender-system
Movie recommeder system using anomaly detection algorithm

This repo is specially created for the work done by me as a part of Coursera's Machine Learning Course.

# File name and their function
ex8.m - Octave/MATLAB script for first part of exercise(Creating the algorithm and use it on a sample dataset)

ex8 cofi.m - Octave/MATLAB script for second part of exercise(using the previously created algorithm to recommend movies from the given dataset)

ex8data1.mat - First example Dataset for anomaly detection

ex8data2.mat - Second example Dataset for anomaly detection

ex8 movies.mat - Movie Review Dataset

ex8 movieParams.mat - Parameters provided for debugging
multivariateGaussian.m - Computes the probability density function
for a Gaussian distribution

visualizeFit.m - 2D plot of a Gaussian distribution and a dataset

checkCostFunction.m - Gradient checking for collaborative filtering

computeNumericalGradient.m - Numerically compute gradients

fmincg.m - Function minimization routine (similar to fminunc)

loadMovieList.m - Loads the list of movies into a cell-array

movie ids.txt - List of movies

normalizeRatings.m - Mean normalization for collaborative filtering

estimateGaussian.m - Estimate the parameters of a Gaussian dis-

tribution with a diagonal covariance matrix

selectThreshold.m - Find a threshold for anomaly detection

cofiCostFunc.m - Implement the cost function for collaborative filtering

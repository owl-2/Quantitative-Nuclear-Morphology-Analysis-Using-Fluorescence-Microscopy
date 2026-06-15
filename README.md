# Quantitative Nuclear Morphology Analysis Using Fluorescence Microscopy

## Overview

This project demonstrates an image-analysis workflow for quantifying nuclear morphology from fluorescence microscopy images. Using images from the BBBC039 dataset, nuclei were segmented, morphological features were extracted, and principal component analysis (PCA) was performed to identify major sources of variation.

## Objectives

* Segment cell nuclei from microscopy images.
* Extract quantitative morphological features.
* Explore heterogeneity in nuclear morphology.
* Apply dimensionality reduction using PCA.
* Demonstrate a reproducible computational biology image-analysis workflow.

## Key Results

* 86 nuclei detected after noise removal.
* Area, perimeter, eccentricity, and solidity were extracted for each nucleus.
* PCA revealed that nuclear morphology is primarily explained by:

  * Size-related variation (Area and Perimeter)
  * Shape-related variation (Eccentricity)
* The first two principal components explained 85.3% of total variance.

## Technologies

Python, NumPy, Pandas, Matplotlib, Scikit-image, Scikit-learn

## Future Work

* Analyze all images in the dataset.
* Separate touching nuclei using watershed segmentation.
* Cluster nuclei into morphological subpopulations.
* Compare morphology across experimental conditions.

# PlantRootAnalysis
Spring 2022 SULI Internship Program with Dr. Daniela Ushizima from Berkeley Laboratory. 

# How to start the analysis
1. Download and open `FINAL_ALGORITHMS` folder on Google Colaboratory (two files in folder)
2. Run all code on a Python notebook

# Project Overview 
- Importance: Characterizing root system architecture furthers our understanding of the development of plants, which can lead to increased crop production and environmental protection. 
- Through computer vision, we developed four semantic segmentation algorithms for Spring Wheat plant roots. Segmented binary images are essential to the quantification and phenotyping of roots. 
- Automatic Thresholding Algorithms: Otsu and Li Method
- Machine Learning Algorithms: Random Forest and MLP Classifiers


# Automatic Thresholding Algorithm
The segmentation algorithms performs binary classification consisting of 4 steps: 
- image denoising
- applying automatic threshold
- background cleaning
- implementing morphological operations


# Machine Learning Classifiers
The segmentation algorithms performs binary classification consisting of 4 steps: 
- Background Cleaning
- Feature Selection
- Determine optimal classifier parameters
- Train and Test Models

# Measuring Plant Roots
Recorded properties for scientific purposes within Berkeley Lab through `skimage.measure.regionprops()`
- area
- perimeter
- feret diameter max
- solidity 

# Results Summarized
The automatic thresholding algorithms outperformed the machine learning models. Ostu's method provided the best dice coefficient score above 75%. 

![alt_text](https://github.com/dani-lbnl/lylybell/blob/main/Summary_Algorithms.png)

# Dual-Phase Deep Learning Pipeline for Comprehensive Retinal Image Analysis

#### This repository implements a dual-phase deep learning pipeline for retinal image analysis. The pipeline combines two tools that work in tandem to first detect abnormalities in retinal imagesand flag them, and then predict specific disease conditions based on detailed multi-label classification.

#### Features:
##### - Preprocessing and exploratory analysis of retinal images from a public dataset: https://www.kaggle.com/datasets/andrewmvd/retinal-disease-classification.
##### - Binary classification to distinguish between normal and abnormal images with high accuracy (~90.16%).
##### - Multi-label classification to identify a range of retinal disease conditions.
##### - Comprehensive methodology and experimental details provided in the accompanying paper.

#### Included Files:
##### - **Retinal_Image_Analysis_Part_1.ipynb**: Loads and preprocesses retinal images, performs exploratory data analysis, and builds a CNN for abnormality detection.
##### - **Retinal_Image_Analysis_Part_2.ipynb**: Adapts the CNN for multi-label classification, predicting detailed disease conditions for each flagged image.
##### - **A Dual-Phase Deep Learning Pipeline for Comprehensive Retinal Image Analysis.docx**: Detailed paper covering the methodology, experimental design, hyperparameter tuning, and results.

#### Required Packages:
##### - tensorflow
##### - keras
##### - keras-preprocessing
##### - numpy
##### - pandas
##### - matplotlib 

# BrainSegementationAndDMN
Brain Image Segmentation and Detecting DMN using ICA (a fun side project). 

A DNN model to perform automated skull-stripping of T1w MRI scans and perform Independent component analysis (ICA) on processed resting-state fMRI scans.

Objectives for this project were 

1) Understanding Independent component analysis (ICA) and Dictionary learning (DL) to decompose rs-fMRI scan into different brain networks.
2) Used NFBS Skull-Stripped Repository for the T1w MRI and ground truth + brain mask dataset
 - Performed T1w MRI preprocessing such as intensity normalization, bias field correction, etc. to remove noise from the imaging scans.
 - Using nipype, a python based neuroimaging library 
 - Performed segmentation of unprocessed scans from BrainSightAI’s T1w MRI scans (https://drive.google.com/file/d/1y8N6JpKhyoLDQcscdudwMCgqubjQyfd1/view?usp=sharing) 
 - Experiments with UNET. 

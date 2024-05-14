# Dynamic-Programming-Project
The final project for Dynamic Programming

Student Name: Jiajian Ma

Student ID: 222041049

## Introduction

This project is the implementation of my final project "Improving Synthetic Sample Selections with Method
Inspired by Dynamic Programming"

The high level idea of this work is to propose a synthetic data sample strategy that can consider both of the distribution of original data and the already selected data. To overcome the limitation of "random selection" and "prediction base selection"

## Code

In this repo, we provide the code for the implement of our proposed method and the visualization of the result in "implementation.ipynb". Due to the size of the data (>10GB) we assuming that we have obtained the feature maps of each images. For detail of how we get them, can refer to the "visualization_logging.ipynb", which is not runnable because of lack of data. 

If you are interested in the data augmentation and polyp segmentation part, you can refer to https://github.com/497662892/Ai-Security-Final-Project, it also provide the full code and data we used in this experiment.

## folders

logs: the folder to store the logs of the experiment (testing)
feature_maps: the folder to store the feature maps of the original and synthetic images
data: the folder to store the data of the experiment, which only include the csv file (no images)

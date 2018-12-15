# ECE285_Project

Description
===========

In this project, we use CNN transfer learning to classify retinal damage from OCT scans. What we will do is using a model (VGG-16 and GoogLeNet) which is already capable of extracting features from an image and train its fully connected network in order to classify different types of retinal damage instead of objects. Also we try to improve its performance by using some machine learning algorithms and adjusting parameters. Finally we will reach to an overall graph based analysis and evaluation for this model. This work will use PyTorch as deep learning framework and CUDA for GPU acceleration. 

Getting Started
===============
Load this dataset with pytorch using ImageFolder as the labels are specified by the folders names.


Code organization
=================

demo.ipynb                   --   Run a demo of our code
assets/Dataset.ipynb         --   The dataset we used
code/VGG_16.ipynb            --   Code of VGG-16 model
code/googlenet.ipynb         --   Code of GoogLeNet model

Authors
=======
Tianyu Qin
Shuang Li
Yumeng Ruan
Shihao Luo



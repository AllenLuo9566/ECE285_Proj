# ECE285_Project

Description
===========

In this project, we use CNN models to classify 101 kinds of food. What we will do this using two models (VGG-16 and GoogLeNet) which are already capable of extracting features from an image and train its fully connected network inorder to classify different types of food. Also we try to analyze and improve its performance by adjusting parameters. Finally we will reach to some overall graphs based analysis and evaluation for this model. This work will use PyTorch as deeplearning framework and CUDA for GPU acceleration.

Getting Started
===============
Load this dataset with pytorch using ImageFolder as the labels are specified by the folders names.
If you wang to run the demo, go to https://1drv.ms/u/s!Au68m8RyvYVqiBlCPUTXuaawe5UH to get the 'VGG16_food_101_true_dataset.h5' and put it in the same folder with demo.ipynb. Besides, you need to unzip 'food-101 demo.zip' and put it in the same folder with demo.ipynb.


Code organization
=================

demo.ipynb                   --     Run a demo of our code     
food-101 demo.zip            --     Small dataset containing 8 images for demo
assets/Dataset.ipynb         --     The dataset we used     
code/googlenet.ipynb         --     Code of GoogLeNet model     
code/VGG_16.ipynb            --     Code of VGG-16 model   

Authors
=======
Tianyu Qin    
Shuang Li    
Yumeng Ruan    
Shihao Luo    



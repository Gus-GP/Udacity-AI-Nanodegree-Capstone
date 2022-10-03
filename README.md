# Dog Breed Classifier
This is a repo for the Dog Breed Classifier Project in Udacity Machine Learning Nanodegree.

**Udacity's original repo is [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification)**

## Project Overview

Convolutional Neural Networks (CNN) project for AI  Nanodegree. In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world,  user-supplied images.  Given an image of a dog, your algorithm will  identify an estimate of the canine’s breed.  If supplied an image of a  human, the code will identify the resembling dog breed.

Along with exploring state-of-the-art CNN models for classification  and localization, you will make important design decisions about the  user experience for your app.  Our goal is that by completing this lab,  you understand the challenges involved in piecing together a series of  models designed to perform various tasks in a data processing pipeline.   Each model has its strengths and weaknesses, and engineering a  real-world application often involves solving many problems without a  perfect answer.  Your imperfect solution will nonetheless create a fun  user experience!

## Import Datasets

* Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
* Download the [human_dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

## Python Environment Libraries

Project mainly implemented by using:

* PyTorch
* Python Image Library (PIL)
* Open Computer Vision
* Numpy
* Matplotlib
* Pandas

For detailed package information please see the **requirements.txt** (built for Anaconda Enviroments)

## Human Face Recognition

Haar feature-based cascade classifier (Viola & Jones, 2001).

## CNN Structures

### From Scratch

VGG-11 (Simonyan and Zisserman, 2015)

Accuracy has been achieved up to **13%** with **20 epochs**

### Transfer Learnings

Used **VGG-19** (Simonyan and Zisserman, 2015) for transfer learnings

Accuracy has been achieved up to **81%** with **20 epochs**








# Semantic Segmentation on PASCAL VOC 2012 

## Introduction 
This project implemented image segmentation on the PASCAL VOC 2012 dataset using FCN network.


## General info 
- Framwork: Pytorch 
- Dataset: [PASCAL VOC 2012](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/)

## Repository structure 
- `image_segmentation.ipynb`: notebook performing image segmentation using Pytorch. 
- `images`: contains some segmented images obtained after training the model. 

## Implementation details 
- Constructed fully convolutional network using pretrained ResNet18 as backbone.
- Initialized transposed convolutional layers by bilinear interpolation.
- Trained the model on the VOC Pascal 2012 segmentation dataset.
- Predicted and plotted the result for the model.

## Result 
Here are some segmented image obtained after training the notebook for 50 epochs:  

![result_1](https://github.com/haongnd2280/Semantic-Segmentation/blob/main/images/result_1.jpg)

![result_2](https://github.com/haongnd2280/Semantic-Segmentation/blob/main/images/result_2.jpg)

![result_3](https://github.com/haongnd2280/Semantic-Segmentation/blob/main/images/result_3.jpg)



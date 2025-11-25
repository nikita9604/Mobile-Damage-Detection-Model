# Mobile-Damage-Detection-Model

This model detects three kinds of damage in a mobile phone ('dead pixel', 'scratch', 'screen crack').
We have used YOLO, which is a pre-trained model for object detection, based on which we have trained our model using YOLO (nano, small, medium) out of which 'small' is performing the best. 


# YOLOsmall Evaluation Matrix
![alt text](https://github.com/nikita9604/Mobile-Damage-Detection-Model/blob/main/Model%20Inference.png)


# Folder Structure (YOLO Format)
train: ../train/images
val: ../valid/images
test: ../test/images
# Dataset-Credits
roboflow:
  workspace: abhinavpoc
  project: mobile-damage-diagnosis
  version: 11
  license: CC BY 4.0
  url: https://universe.roboflow.com/abhinavpoc/mobile-damage-diagnosis/dataset/11

#UI Mockup
https://neo-front-19351627.figma.site/

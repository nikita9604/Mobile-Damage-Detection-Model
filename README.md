# Mobile-Damage-Detection-Model

This model detects three kinds of damage in a mobile phone ('dead pixel', 'scratch', 'screen crack').
We have used YOLO, which is a pre-trained model for object detection, based on which we have trained our model using YOLO (nano, small, medium) out of which 'small' is performing the best. 


# YOLOsmall Evaluation Matrix
Class             Images    Instances      Box(  P          R         mAP50      mAP50-95)
all               702       1266                 0.826      0.655     0.713      0.384
dead pixel        156       217                 0.812       0.562     0.613      0.278
scratch           171       399                 0.844       0.82      0.846      0.427
screen crack      336       650                 0.822       0.585     0.68       0.446



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

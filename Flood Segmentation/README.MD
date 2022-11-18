## introduction

Flooding is a natural hazard that causes a lot of deaths every year and the number of flood events is increasing
worldwide because of climate change effects. Detecting and monitoring floods is of paramount importance in order
to reduce their impacts both in terms of affected people and economic losses. Automated image analysis techniques
capable to extract the amount of water from a picture can be used to create novel services aimed to detect floods
from fixed surveillance cameras, drones, crowdsourced in-field observations, as well as to extract meaningful data
from social media streams. In this notebooks we compare the accuracy and the prediction performances of recent Deep
Learning algorithms for the pixel-wise water segmentation task.

## data source 

we used ETCi 2021 Competition on Flood Detection to build those model 

 data can be downloaded from the following link:
 https://www.kaggle.com/datasets/aninda/etci-2021-competition-on-flood-detection
 
 ## data overview
 The provided training data is split across 29 root folders named <region>_<datetime>*, region being the region and datetime being the date and time of the flood event. Each root folder includes 4 sub-folders: vv, vh, flood_label and water_body_label with 2,068 files each. vv and vh correspond to the satellite images listed earlier and images in the flood_label and water_body_label folder provide reference ground truth.

## Model architecture (2D UNet)

We employed 4  cnn models and fine-tuned it for our particular Flood Segmentation task.
& we fined that 2d unet is best suited for this data

![image](https://user-images.githubusercontent.com/31762490/202818422-7d8cd6d4-cd00-425a-b79b-744cb6375fce.png)


## Model summary

![image](https://user-images.githubusercontent.com/31762490/202818451-b6945cd4-9737-48ba-9886-14273ac94efb.png)




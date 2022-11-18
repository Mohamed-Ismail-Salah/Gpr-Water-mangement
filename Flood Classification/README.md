## Overview  
The idea presented in folder's notebooks  is to find the dissimilarity between a pair of satellite images of the same geograhical region. A pair of satellite image consist of an image taken during flood, and an image taken few days before the flood.

An example image pair is given below,


![image](https://user-images.githubusercontent.com/31762490/202319454-4c8289b5-92f2-4997-bdc8-a456d3c5aa0c.png)

If the dissimilarity is high it means, that particular geographical region is flooded. Low value of dissimilarity means, that region is less affected by flood.

This approach to figure out flooded regions can be applied to all other natural disaster as well, since the main idea here is to measure the changes of a particular region before and during the disaster.

The data can be downloaded from the following link:

https://www.kaggle.com/datasets/rahultp97/louisiana-flood-2016




##  Model architecture (VGG16)

We employed 4 KERAS' pretrained models like VGG16 ,resnet ,mobilenet &inceptionv3 CNN and fine-tuned it for our particular flood detection (image classification) task.
& we fined that VGG16 is best suited for this data

![image](https://user-images.githubusercontent.com/31762490/202320653-dd2eca20-243b-4b95-820e-c0bf5d003bfb.png)


## Model summary (VGG16)

![image](https://user-images.githubusercontent.com/31762490/202319963-48aff570-9f3f-4adb-b0f5-bec69a91a3a7.png)

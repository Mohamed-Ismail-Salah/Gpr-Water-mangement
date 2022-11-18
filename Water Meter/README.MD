## introduction

Automatic Meter Reading (AMR) refers to automatically record the consumption of  water for both monitoring and billing. Despite the existence of smart readers,
they are not widespread in many countries, especially in the underdeveloped ones, and the reading
is still performed manually on site by an operator who takes a picture as reading proof.Since
this operation is prone to errors, another operator needs to check the proof image to confirm the
reading. This offline checking is expensive in terms of human effort and time, and has low efficiency. Moreover, due to a large number of images to be evaluated, the inspection is usually done
by sampling
and errors might go unnoticed.
Performing the meter inspection automatically would reduce mistakes introduced by the human
factor and save manpower. Furthermore, the reading could also be executed fully automatically
using cameras installed in the meter box.
Image-based AMR has advantages such as lower cost
and fast installation since it does not require renewal or replacement of existent meters.

## Data 
MR-AMR is a public dataset composed of 140000 images of the digits in full-state and mid-state. It covers different types of water and electricity meters most used in Morocco

Link data below:  
https://data.mendeley.com/datasets/8xjhrrk9rx/1

## overview 
 A CNN architecture was trained in an end-to-end manner where
the initial convolutional layers extract visual features of the whole image and the fully connected
layers predict the probabilities for each digit

## Model architecture

![image](https://user-images.githubusercontent.com/31762490/202796024-53e17496-b370-4a1b-b09d-1ed1a5d7553b.png)

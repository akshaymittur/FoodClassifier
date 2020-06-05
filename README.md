# Food Classifier 
Data science project using deep learning for image classification 

## Overview 
In this project I built a food classifier to identify different dishes from food. This could be useful for someone who doesn't know what they're eating. They could take a picture of a dish and an app could serve them some information. This is the underlying model for building something with those capabilities. 

I was able to get the model to predict the dish with 95% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet50. This created time efficiencies and solid results. 

![Confusion Matrix](https://ibb.co/CHmwjY9)

## Config
I recommend using google colab for this project as it makes the gpu configuration far easier. In google colab make sure that you go to runtime -> change runtime type -> gpu. 

Use the folders and photos located [here](https://drive.google.com/drive/folders/11h_XOMIe_W67PJ7TSix-dPVcLrXO4H7P?usp=sharing), and provide authorization for your account while running the code in colab.

## Data 
I used the following chrome extension to download the data from google images. [FatKun Batch Download Image](https://chrome.google.com/webstore/detail/fatkun-batch-download-ima/nnjjahlikiabnchcpehcpkdeckfgnohf?hl=en)
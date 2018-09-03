# Image Classification with Custom Vision Service
In this lab you will train, evaluate, deploy, and use a custom image classification model using Microsoft Cognitive Services Custom Vision Service. 

The Custom Vision Service is a Microsoft Cognitive Service that lets you build custom image classifiers. It makes it easy and fast to build, deploy, and improve an image classifier. The Custom Vision Service provides a REST API and a web interface to upload your images and train the classifier.

The lab is designed as an instructor guided hands-on exercise. The most efficient way to go through the lab is to follow the instructor. In addition to walking you through the lab's steps, she will explain key concepts and dive into technical details that may not be thoroughly documented in the lab's instructions. 

Don't hesitate to ask questions !

## What will you practice during the lab?
The lab consists of four consecutive steps:
- In the first step you will learn how to provision Custom Vision Service.
- Next you will learn how to train, evaluate and fine tune a custom image classification model.
- In the third step, you will access your model through the REST web service - aka prediction point.
- Finally you will learn how to export your trained model as a docker image so it can be deployed into an arbitrary inference environment



## Scenario

You will train a custom image classification model to automatically classify the type of land shown in aerial images of 224-meter x 224-meter plots. Land use classification models can be used to track urbanization, deforestation, loss of wetlands, and other major environmental trends using periodically collected aerial imagery. The images used in this lab are based on imagery from the U.S. National Land Cover Database. U.S. National Land Cover Database defines six primary classes of land use: *Developed*, *Barren*, *Forested*, *Grassland*, *Shrub*, *Cultivated*. For the sake of simplicity, in this lab you will train and operationalize a classifier to recognize three classes: *Barren*, *Developed*, *Cultivated*.  Example images in each land use class are shown here:

Developed | Cultivated | Barren
--------- | ------ | ----------
![Developed](/Datasets/AerialSmall/train/Developed/ortho_1-1_hn_s_ca025_2016_1_104257.png) | ![Barren](/Datasets/AerialSmall/train/Cultivated/ortho_1-1_hn_s_ca025_2016_1_9900.png) | ![Cultivated](/Datasets/AerialSmall/train/Barren/ortho_1-1_hn_s_ca025_2016_1_7359.png)


## Prerequisites

### Skills
- Basic proficiency in Python and Jupyter
- High level understanding of cloud computing concepts

### Equipment

- An access to Microsoft Azure subscription.
- A workstation with a current version of Anaconda for Python 3 installed. Windows 10 or MacOS recommended. 
- An access to Internet


[Next Step](https://github.com/Microsoft/MTC_AzureAILabs/blob/master/Lab01%20-%20Image%20Classification%20with%20Custom%20Vision%20Service/Step1-SetupEnv/README.md)



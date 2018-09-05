# Image Classification with Custom Vision Service
In this lab you will train, evaluate, deploy, and use a custom image classification model using Microsoft Cognitive Services Custom Vision Service. 

The lab is designed to be instructor guided.  In addition to walking you through the lab's steps, the instructor will explain key concepts and as necessary deep dive into technical details. 

Don't hesitate to ask questions !

## What will you learn during the lab?
The lab consists of 2 parts:
- In the first part you will learn how to train, evaluate, fine tune, and invoke a custom image classification model.
- In the the second part, you will export your model as a docker image so it can be deployed into an arbitrary inference environment

Both parts are implemented as Jupyter notebooks and utilize Custom Vision Service Python SDK. Note, that there are other ways of working with Custom Vision Service, including Go and C# SDKs and Custom Vision Service GUI. In fact all these interfaces are front-ends to Custom Vision Service REST API that is thoroughly documented in the following links:

https://southcentralus.dev.cognitive.microsoft.com/docs/services/d0e77c63c39c4259a298830c15188310/operations/39b14cb5f7f34977a6e6a290

https://southcentralus.dev.cognitive.microsoft.com/docs/services/450e4ba4d72542e889d93fd7b8e960de/operations/5a6264bc40d86a0ef8b2c290




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
- A valid Microsoft account or an Azure Active Directory OrgID ("work or school account")
- An Azure subscription associated with your Microsoft Account or OrgID. If you don’t have an Azure subscription, you can create a trial subscription before you begin.
- An access to Internet


[Next Step](https://github.com/Microsoft/MTC_AzureAILabs/tree/master/Lab01%20-%20Image%20Classification%20with%20Custom%20Vision%20Service/EnvironmentSetup)



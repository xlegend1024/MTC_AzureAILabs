# Train
In this step you will train, evaluate, and fine tune a custom image classification model using Custom Vision Service Web GUI. It is also possible to script the modelling workflow using Custom Vision Service SDK. Refer to the below link for more information:

https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/python-tutorial



## Upload and tag training images
1. Navigate to the project section of Custom Vision Service Web GUI.

https://customvision.ai/projects

2. Click on the project you created in the lab set up step.

![Select the project](images/img4.PNG)

3. To add the first set of images to your project, use the *Add* images button. Navigate to `<MTC_AzureAILabs root/Datasets/AerialSmall/train/Barren` and select and add all images.

![Add images](images/img5.PNG)


2. To set the tag, enter text in the My Tags field and then use the + button. 



3. To upload another set of images, return to step 1. For example, if you want to distinguish between knots and strips, upload and tag images of strips.

## Train and evaluate the classifier
1. To train the classifier, select the Train button.
![Train](images/train02.png)
![Train](images/train03.PNG)

## Test your model
1. From the Custom Vision web page, select your project. Select Quick Test on the right of the top menu bar. This action opens a window labeled Quick Test.
2. In the Quick Test window, click in the Submit Image field and enter the URL of the image you want to use for your test. If you want to use a locally stored image instead, click the Browse local files button and select a local image file.
![Test](images/test1.PNG)
3. Repeat the test for another image
![Test](images/test2.PNG)

## Use SDK to programmatically train and evaluate models






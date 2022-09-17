# Segmentation Detection model for Crack on Concrete Surface
## SDK overview
ASUS AISVision is an Ease-of-use AI Toolkit and SDK for Machine/Computer Vision. It provides three working mode, include “trainer”, “runtime” and “scheduler” for AI training, inference and batch training scenario. By using the SDK, developers can retrain a model with new data input and keep the domain know how in their own field. Its characteristics are:
 - Intuitive, simple, and quick project set-up
 - Four basic model (Object detection, classification, segmentation, and anomaly detection) for vertical application
 - Unique AI training framework
 - Report wizard for sample filtering
 - Multiple training projects scheduling for tuning
 - Friendly Software Development
 
![SDK_interface](https://user-images.githubusercontent.com/48753146/190845253-5f1ae0fd-d719-4c98-9a8d-778ea3dec346.png)

 
## Project Overview.
 To test the capabilities of the SDK, we will train a segmentation model to detect crack on concrete surface. We use 30 images for the training and the annotation has been done directly on the AISVision SDK using the annotation style via pen.
 
## Dataset Annotation
![annotation_step](https://user-images.githubusercontent.com/48753146/190845254-fc28993f-cfee-4249-b813-a7db940a0319.png)

 
 # How to Get a Training Started
 - Open the SDK, define the project name and set the project type: classification, segmentaion, object detection or anomaly detection.
![project_type](https://user-images.githubusercontent.com/48753146/190845250-824fe63a-8468-46c3-bfaa-0502f60457e3.png)
 - Load and annotate the images.
 - Start training and adjust parameters if needed.
 - Verifying the training results as well as the predictions.
 - Retrain with more images, new parameters if needed.
 
## Training and Report
### Training
![train](https://user-images.githubusercontent.com/48753146/190845265-adfb5d64-d5a5-41d6-9383-7389d27d9b06.png)
### Report
![report1](https://user-images.githubusercontent.com/48753146/190845252-7c93273c-8c7e-4efe-a556-111c90ffae29.png)
 
# Predictions
In the first prediction the model was able to perform a good segmentation. However, it missed some crack on the second image. This is the first training. With extra training, more data and adjusted parameters, we can overcome this error. Overall, the model perform quite good for a first training.
![prediction1](https://user-images.githubusercontent.com/48753146/190845255-0494a4c1-1a1e-487c-98ed-b16a89ed556d.png)
![prediction2](https://user-images.githubusercontent.com/48753146/190845257-03bdc6b4-3cc5-4b78-8997-7db810f43d66.png)
 
# Remark:
  - The dataset has been dowloaded here: https://github.com/arthurflor23/surface-crack-detection/tree/master/dataset .

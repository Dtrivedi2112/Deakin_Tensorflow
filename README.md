# Android TensorFlow Machine Learning Example


--------------------------------------------------------------------------------------------------------------------------------------------------


Name: Evaluate the Android tensorflow  Machine Learning app
 
Date Started: 03/08/17
 
Using:
Java
Android Studio
 
Why?
To check the extent of android tensorflow machine learning app and see if it works for a particular class.
 
How?
Fork the github repository.
Link - https://github.com/MindorksOpenSource/AndroidTensorFlowMachineLearningExample
Clone it.
Build it on Android studio.
Run it on mobile. 
Testing by focusing it on various objects based on their shapes, drawings and also check for a specific class.
 
Outcome
 It detects the classes as specified in the inception model but it contains a camera button so one has to take picture to detect the object which is good but live tracking is better which is provided in the original tensorflow app. The reason it is better because in this app when taking pictures from different angles it changes the result every time.

The camera does not optimize automatically so one has to open an image to full screen to it’s best quality so it can be detected other detection process is working fine.
 
Date Completed:  08/08/2017
 
What?
The camera does not detect the objects properly as the image should be it’s best quality so it can detect otherwise it won’t because the camera doesn’t optimize automatically so it will get blur as one moves closer to the image.

It won’t detect an object if it’s in a group.

As it has capture button so one has to take photos from different angles to detect the object because sometimes it doesn’t detect so one has to try it several times.
 
Notes:
Better open an image to full screen to it’s best quality so it can detect properly.

To build the original tensorflow app because when creating the dataset it will be helpful to find all the files related to it rather than finding manually over here which is confusing. 
 
Recommendation:

Build tensorflow on ubuntu.
Might need to edit some changes in the camera for better optimization.
Test for detecting Ant class.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Name: Evaluate the Android tensorflow machine learning app for Ant class. 
Date Started: 05/08/17
 
Using:
Java
Android Studio
 
Why?
To check the extent of identifying one particular class and also observe the confidence score based on that.
 
How?
By making some  class changes in the label file so that it detects only ants and detecting other objects should result in “Not ant”.
Open filename “imagenet_comp_graph_label_strings.txt” and edit all the 1000 classes to “ Not Ant” and don’t edit the class name “Ant” and leave it as it is.
Build it.
Test it on different ant images.
 
Outcome
The results are good but as said in last spike, the image quality should be best to get accurate results.
It can’t detects group of ants.
Need to take photos from different angles to get the exact result.
 
Date Completed:  08/08/2017
 
What?:
This app detects only ants and the confidence score for it is changing if picture is taken from different angle.
Group of objects isn’t recognized by this app.
 
Notes:
Open the image in full screen to get accurate data. 

 
Recommendation:
Maybe train the model by giving some images of ants after optimizing the camera.

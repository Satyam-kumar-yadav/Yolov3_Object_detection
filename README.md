# Yolov3_Object_detection


Objet detection is a task in computer vision that involves identifying the presence, location, and type of one or more objects in a given photograph.

It is a challenging problem that involves building upon methods for object recognition (e.g. where are they), object localization (e.g. what are their extent), and object classification (e.g. what are they).

In recent years, deep learning techniques are achieving state-of-the-art results for object detection, such as on standard benchmark datasets and in computer vision competitions. Notable is the “You Only Look Once,” or YOLO, family of Convolutional Neural Networks that achieve near state-of-the-art results with a single end-to-end model that can perform object detection in real-time.

# Task 1 - Train and Test Data Collection

You can do this task in two ways :-
<br>
**Method 1**<br>
This method is the method I recommend as you can gather thousands of images and auto-generate their labels within minutes! Gathering a dataset from Google's Open Images Dataset and using OIDv4 toolkit to generate labels is easy and time efficient. The dataset contains labeled images for over 600 classes!
[Explore the dataset here](https://storage.googleapis.com/openimages/web/index.html)
![My dataset](https://github.com/Satyam-kumar-yadav/Yolov3_Object_detection/blob/main/dataset.jpg)
<br>
**Method 2**
<br>
Manually Labeling Images with Annotation Tool
If you can't find the proper images or classes within Google's Open Images Dataset then you will have to use an annotation tool to manually draw your labels which can be a tiresome process.<br>
[Download the tool from here](https://tzutalin.github.io/labelImg/)
![Annotation tool](https://github.com/Satyam-kumar-yadav/Yolov3_Object_detection/blob/main/Annotation.jpg)

# Task 2 - Configuring Files for Training
This step involves properly configuring your custom .cfg file, obj.data, obj.names and train.txt file.

# Task 3 - Download pre-trained weights
[darknet53.conv.74](http://pjreddie.com/media/files/darknet53.conv.74)

# Task 4 - Train Your Custom Object Detector
Train Your Custom Object Detector by the command `!./darknet detector train <path to obj.data> <path to custom config> darknet53.conv.74 -dont_show`
<br>
<br>

You can look after some sources :-\
1-[How to Perform Object Detection With YOLOv3 in Keras](https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/)\
2-[Yolo](https://pjreddie.com/darknet/yolo/)\
3-[Train YOLO to detect a custom object](https://youtu.be/_FNfRtXEbr4)

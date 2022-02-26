# Object_Detection

Object detection is basically a Object localization which identifies the location of an object in image and draw a bounding box around their extent. 

* Two important terms of Object Detection is:

  1.Classification of an object.
  
  2.Localization of an object.
 
 
 * Object Detection involves 3 steps:
 
    1.creating the dataset 
      a. classes 
      b. annotation
      
    2.Model Training (Darknet, Yolov3)
    
    3.Model Prediction
    
    
Darknet : It is a open source neural network framework written in C and CUDA. It is faster than most of the models as it is written in C. It is compatible with both CPU and GPU. Advanced implementations of deep neural networks can be done using Darknet. These implementations include You Only Look Once (YOLO) for real-time object detection, ImageNet classification, recurrent neural networks (RNNs), and many others.

YOLO : YOLO stands for You only look once The approach involves a single neural network trained end to end that takes a image as an input and predicts bounding boxes and class labels for each bounding box directly.

* Objective : To detect Sea_sponges from the image.

* Dataset : Created by collecting images of sea sponges from google.

* LabelImg : It is used to annotate the images. (https://pypi.org/project/labelImg/1.4.0/)

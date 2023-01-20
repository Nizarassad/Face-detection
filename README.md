# Face Detection System using OpenCV



## This repository contains a simple face detection system implemented using the OpenCV library. The system is able to detect faces in an image or video stream and draw a bounding box around the detected face.

### Requirements:
    Python 3.x
    OpenCV (version 4.x or higher)
    Numpy
    Usage

### The system can be used in two ways:

#### Detect faces in an image
##### Copy code:

    > python detect_faces.py --image path/to/image
#### Detect faces in a video stream:
##### Copy code:

    > python detect_faces.py --video

#### The system uses a Haar cascade classifier for face detection, which is a machine learning based approach. The classifier is trained on a dataset of positive and negative images, and is able to detect faces with high accuracy. However, it may not work well for all types of faces or in all lighting conditions.

#### Future Work:
   #### - Improving the accuracy of the classifier by fine-tuning it on a specific dataset.
   #### - Implementing more advanced algorithms for face detection such as deep learning based approaches.
   #### - Incorporating face recognition functionality to identify individuals in the detected faces.
   #### - Feel free to fork this repository and submit pull requests. If you have any questions or suggestions, please open an issue.


#### Author

Nizar Assad





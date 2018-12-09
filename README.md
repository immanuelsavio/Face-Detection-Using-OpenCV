# Face Detection Using OpenCV

This simple application has two programs. The first program is in face_sample.py which will take 100 images to make the dataset of the user who will unlock. THe second program is identify_face.py which will train the program with the taken 100 images and then open the webcam to recognize the user. 

### Prerequisites

What things you need to install the software and how to install them<br />
You will be needing Python 2.7 or higher.<br />
The following python packages will be needed:<br />

1.Numpy<br />
2.OpenCV<br />
3.OS<br />

### Logic

This program uses face_sample.py to take the images and store it in the faceimages folder. Then it will make use of the OpenCV library's LBPHFaceRecognizer and CascadeClassifier to learn the images. Then the webcam is used to identify the user if only the person in front of the camera has a confidence level greater than a specified amount(default set 85%). The confidence level is also shown on the screen.

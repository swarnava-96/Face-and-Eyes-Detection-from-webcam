# Live-Face-and-Eyes-Detection

### Goal: The goal of this project is to detect face and eyes from live webcam using OpenCV and Haarcascade classifier.

### Brief Description:
I have used OpenCV and Haarcascade classifier in this project. 


So, what is Haar Cascade? 
It is an Object Detection Algorithm used to identify faces in an image or a real time video. 
The algorithm uses edge or line detection features proposed by Viola and Jones in their 
research paper “Rapid Object Detection using a Boosted Cascade of Simple Features” published in 2001.


The features in Haar Cascade is stored in XML files. I have used "haarcascade_frontalface_default.xml"
for detecting the face and "haarcascade_eye.xml" for detecting the eyes. I have downloaded these files
from Haar Cascade GitHub repository[link](https://github.com/opencv/opencv/tree/master/data/haarcascades).
Then, I have defined a function, changed the color scale to gray for speeding up the task, defined rectangular
boxes for detecting face and eyes. I have used live recordings from my webcam in this project. 

### Demo:
![ezgif com-gif-maker](https://user-images.githubusercontent.com/75041273/136550906-5b575b50-349f-4d43-add2-904d6d9e6962.gif)

### Installation:


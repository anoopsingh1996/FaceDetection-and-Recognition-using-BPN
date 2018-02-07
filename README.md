# FaceDetection-and-Recognition-using-BPN

## Prerequisites
* Python 2.x
* OpenCV 3.x
* Pillow Python Library

## Running the tests

### For Face Detection in image
* Go folder face_detection:- and run
* $ python face_detect.py a1.jpg haarcascade_frontalface_default.xml

![abc](https://user-images.githubusercontent.com/9657488/35817254-e79b3612-0ac2-11e8-9144-54cfbabedb03.png)

### For Face Detection through webcam
* $ python live.py haarcascade_frontalface_default.xml
### For face recognition

* run the dataSetGenerator.py and enter a unique id to create face samples with your face
* run trainer.py for trained dataset
* run detector.py for recognition of face

![bbf](https://user-images.githubusercontent.com/9657488/35817774-5284ddb0-0ac4-11e8-98a0-249db21a92c0.png)

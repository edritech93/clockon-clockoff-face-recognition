# clockon-clockoff-face-recognition
This is a Face Recognition Project - HR Check-in on iOS Device.

Reference:
  - Pre-train Model: Facenet https://github.com/davidsandberg/facenet 
  - Dataset: VGGFace2 https://drive.google.com/file/d/1EXPBSXwTaqrSC0OhUdXNmKSh9qJUQ55-/view?usp=drive_open
  - Architecture: Inception Resnet V1 https://github.com/davidsandberg/facenet/blob/master/src/models/inception_resnet_v1.py
  - Algorithm: 
    + Swift K-means Clustering https://github.com/raywenderlich/swift-algorithm-club/tree/master/K-Means 
    + Swift k-NN https://github.com/baqtiste/KNN-swift 
    + Swift k-NN https://github.com/mmahler2/Swift-DTW-KNN 
  
  
Minimum requirement:
  - iOS 12.0 or later.
  - Xcode 11 or later, Swift 5.


Demo:
- Recognize Screen:

<img src="https://github.com/hosituanit/clockon-clockoff-face-recognition/blob/master/images/recognize.jpg" width="300">


- Unknown Person:

<img src="https://github.com/hosituanit/clockon-clockoff-face-recognition/blob/master/images/unknownPerson.PNG" width="300">


- Predict Image Screen (two people):

<img src="https://github.com/hosituanit/clockon-clockoff-face-recognition/blob/master/images/testTwoPeople.PNG" width="300">

-  Predict Image Screen, Time Taken (1 person):

<img src="https://github.com/hosituanit/clockon-clockoff-face-recognition/blob/master/images/testTimeTaken.jpg" width="300">

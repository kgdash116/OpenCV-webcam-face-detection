# OpenCV-webcam-face-detection<br>

<h1>Summary</h1>


- This repository contains a jupyter notebook that will enable the user to perform a live face detection through the webcam. 
- The model is based on the Haar Classifier.
- The frames obtained from the video feed are passed to a function where the frame is converted to a Grayscale image adn then <br>
  the classifier is applied. The classifier return bounding boxes and number of detections.<br>
- The bounding boxes are then drawn on the live image feed, and the frame is returned.<br>
- The webcam stream can be turned off by pressing "q".

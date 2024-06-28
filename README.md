# Driver-Drowsiness-Detection-System
# Driver Drowsiness Detection System to avoid accidents due to drowsiness

1. Installation of the required module:- OpenCV, keras, TensorFlow, Pygame.
2. Creation of the dialog box
3. The "haar cascade files" folder consists of the xml files that are needed to detect objects from the image. In our case, we are detecting the face and eyes of the person.
4. The model's folder contains our model file "cnnCat2.h5" which was trained on convolutional neural networks.
5. We have an audio clip "alarm.wav" which starts playing when the person is feeling drowsy. 
6. "model.py" file contains the program through which the classification model is built by training on the available dataset. You could see the implementation of convolutional neural network in this file.
7. "drowsiness detection.py" is the main file of our project. To start the detection procedure, we have to run this file.
8. "image.jpg" is the image file of the frame that gets saved once the frame is closed.

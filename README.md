# Project Components Overview

1. **Modules Installation**:
   - Required modules include OpenCV, Keras, TensorFlow, and Pygame.

2. **Dialog Box Creation**:
   - Implementation of a dialog box for user interaction.

3. **Haar Cascade Files**:
   - Contains XML files used for detecting faces and eyes in images.

4. **Model File**:
   - The `cnnCat2.h5` file in the `models` folder is trained on convolutional neural networks.

5. **Audio Clip**:
   - `alarm.wav` plays when the system detects drowsiness.

6. **Model Training** (`model.py`):
   - Builds a classification model using convolutional neural networks trained on a dataset.

7. **Main Detection File** (`drowsiness_detection.py`):
   - Executes the drowsiness detection procedure when run.

8. **Image File**:
   - `image.jpg` captures a frame and saves it when the procedure ends.

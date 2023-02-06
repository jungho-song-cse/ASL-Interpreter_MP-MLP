# ASL-Interpreter_MP-MLP

## American Sign Language - Interpreter.
Build with Media Pipe & Multi Level Perceptron architecture.<br>Can interpret 1~10 numbers.

# Requirements
* mediapipe 0.8.1
* OpenCV 3.4.2 or Later
* Tensorflow 2.3.0 or Later<br>tf-nightly 2.5.0.dev or later (To create a TFLite for model)
* scikit-learn 0.23.2 or Later (To display the confusion matrix) 
* matplotlib 3.3.2 or Later (To display the confusion matrix)

# Files
## asl_num_classifier.py
Program for inference.

## keypoint_classification.ipynb
Model training script for hand sign recognition.

# RUN
python asl_num_classifier.py -> Open webcam<br>
python asl_num_classifier.py --device videoFile.mp4 -> Open videoFile.mp4 (You should add videoFile.mp4 in Folder)
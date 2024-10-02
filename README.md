# projects-2023-24-mxt3771
# ASL Detection Using Action Recognition with LSTM
This project focuses on real-time American Sign Language (ASL) gesture recognition using Long Short-Term Memory (LSTM) deep learning models. By leveraging MediaPipe and OpenCV for real-time feature extraction and a custom-built dataset, the system can detect subtle differences between ASL gestures, providing robust real-time performance even in cluttered environments.

# Project Overview
Features:
Action Recognition with LSTM: Built using 3 LSTM layers and 2 dense layers to capture and classify dynamic ASL gestures.
Real-time Feature Extraction: Utilized MediaPipe and OpenCV to capture key points and spatial dynamics of ASL gestures.
Custom Dataset: Structured a dataset with 30 video frames per gesture for training the model.
High Accuracy: Achieved precise recognition of subtle gesture differences.
Robust Performance: Optimized for real-time usage in diverse environments, including cluttered backgrounds, to improve accessibility for the hearing-impaired community.

# Technologies Used
Deep Learning Framework: TensorFlow/Keras
Model: LSTM (3 layers) + Dense (2 layers)
Feature Extraction: MediaPipe, OpenCV
Programming Languages: Python
Tools: Jupyter Notebooks, NumPy, Pandas
Environment: Tested on local machines (Windows/Linux/Mac)

# Dataset
A custom dataset consisting of 30 video frames per ASL gesture was built for this project. Each gesture's video is converted into sequential key point data using MediaPipe, capturing the motion and positions of hand gestures.

# Model Architecture
The model uses LSTM layers to handle the sequential nature of the ASL gestures, followed by fully connected dense layers for classification. The architecture can be summarized as follows:

Input Layer: Sequence of video frames with gesture key points.
3 LSTM Layers: To process temporal dependencies of the gesture sequence.
2 Dense Layers: For gesture classification.
Output Layer: Softmax for multi-class classification of ASL gestures.

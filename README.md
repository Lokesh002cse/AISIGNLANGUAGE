# AI Sign Language Recognition

## Overview

This project aims to develop an AI system capable of recognizing and interpreting sign language gestures using deep learning techniques. By leveraging computer vision and machine learning algorithms, our goal is to create a robust system that can accurately interpret various sign language gestures in real-time.

## Features

- Real-time Gesture Recognition: Recognizes sign language gestures in real-time.
- Multi-Language Support: Capable of supporting multiple sign languages.
- High Accuracy: Utilizes deep learning models to achieve high accuracy and robustness.
- User-Friendly Interface: Easy-to-use interface for interaction.
- Hardware Compatibility: Compatible with various hardware setups.

### Install Dependencies
To install the required Python packages, navigate to the project directory and run the following command:
```
pip install -r Requirements.txt
```
```Requirements.txt
opencv-python~=4.5.4.60
numpy~=1.26.4
cvzone~=1.6.1
tensorflow
mediapipe
```
## Dataset
To train the model, you'll need a dataset of sign language gestures. You can either use an existing dataset or create your own by recording sign language gestures. Ensure that the dataset is labeled correctly for accurate training.

-  Creating Your Dataset: Organize your dataset in the DATA directory, with separate folders for each letter and gesture.

-  Data Collection Script: Use the data_collection.py script to collect data.

-  Training: You can train the model using Teachable Machine or directly with TensorFlow.

-  After training with TensorFlow, export the model and import it into the testing.py file.


## Usage
Once the system is up and running, it will start recognizing sign language gestures in real-time. You can interact with the system through the user interface or integrate it into other applications.

To test the model, simply run the following command:
~~~
python testing.py
~~~


## Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions are always welcome!


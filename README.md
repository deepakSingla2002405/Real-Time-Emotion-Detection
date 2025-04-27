# Real-Time-Emotion-Detection

Introduction
This project aims to classify the emotion on a person's face into one of seven categories, using deep convolutional neural networks. The model is trained on the FER-2013 dataset which was published on International Conference on Machine Learning (ICML). This dataset consists of 35887 grayscale, 48x48 sized face images with seven emotions - angry, disgusted, fearful, happy, neutral, sad and surprised.

Dependencies
Python 3, OpenCV, Tensorflow
To install the required packages, run pip install -r requirements.txt.
Basic Usage
The repository is currently compatible with tensorflow-2.0 and makes use of the Keras API using the tensorflow.keras library.

First, clone the repository and enter the folder
git clone https://github.com/atulapra/Emotion-detection.git
cd Emotion-detection
Download the FER-2013 dataset inside the src folder.

If you want to train this model, use:

cd src
python emotions.py --mode train
If you want to view the predictions without training again, you can download the pre-trained model from here and then run:
cd src
python emotions.py --mode display

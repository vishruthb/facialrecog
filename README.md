# Facial-Emotion-Recoginiton

## Overview
Using Extended Cohn-Kanade AU-Coded Facial Expression Database to classify basic human facial emotion expressions using ann.

## Installation

The necessary dependencies are in the requirements.txt file so just run this before running the actual code to get them installed. May require some extra effort for OpenCV though.

``
pip3 install -r requirements.txt
``

## Usage

If you want a facial emotion classifier you can just download the Cohn-Kanade dataset and serialize the dataset according to your need and if you can you should also use another dataset with ck for better results.

pickle_dataset.py => Script for processing and Serializing dataset.
  python pickle_dataset.py -h

cnn.py => Convolution Neural Network to train the the classifier.
  python cnn.py -h

cohn-kanade-images.txt => Contains some basic info about the dataset.

## Credits
Vishruth Bharath, DVHS

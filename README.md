# Handwritten-Text-Identification-and-Recognition-from-an-Image

This project implements a deep learning pipeline to automatically identify and recognize handwritten text from images. It uses a Convolutional Recurrent Neural Network (CRNN) combining convolutional layers for feature extraction, bidirectional LSTMs for sequence modeling, and Connectionist Temporal Classification (CTC) loss for training without the need for character-level segmentation.

The system takes grayscale handwritten images, preprocesses them (resize, normalize, encode labels), and trains the CRNN to predict character sequences. It reports both character-level and word-level accuracy. Data augmentation is applied to improve generalization.


### Key Features:
– Supports alphabets, numbers, words, sentences, and special characters

– CRNN with CTC loss for end-to-end recognition

– Edit-distance based evaluation of character-level and word-level accuracy

– Achieved approximately 95.86% character accuracy and 92.40% word accuracy on IAM dataset subset


This repository can serve as a starting point for building OCR systems for handwritten text, document digitization, and real-time handwriting recognition applications.


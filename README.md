🤟 Deep Learning Based Indian Sign Language (ISL) Translation System

This project presents a Deep Learning–based Indian Sign Language (ISL) Translation System designed to bridge the communication gap between the hearing-impaired community and the general public. The system uses computer vision and deep learning techniques to recognize hand gestures in real time and translate them into readable text (and optionally speech output).

Indian Sign Language is widely used across India, yet accessibility tools supporting ISL are limited. This project aims to create an efficient, scalable, and real-time solution that can recognize ISL alphabets, numbers, words, or predefined emergency gestures using a webcam feed.

🔍 Project Overview

The system captures live video input, preprocesses frames, detects hand regions, and feeds the processed images into a trained deep learning model. A Convolutional Neural Network (CNN) is used for feature extraction and classification of gestures. The predicted gesture is then mapped to corresponding text output.

🚀 Key Features

Real-time gesture recognition using webcam

CNN-based deep learning model for accurate classification

Image preprocessing (resizing, normalization, background removal)

Support for ISL alphabets, numbers, and emergency words

User-friendly interface

Scalable architecture for adding more gestures

🧠 Technologies Used

Python

TensorFlow / Keras or PyTorch

OpenCV

NumPy

Matplotlib

⚙️ Working Pipeline

Capture video input from webcam

Extract hand region using image processing

Preprocess image (resize, normalize)

Feed into trained CNN model

Predict gesture class

Convert prediction into text output

📂 Dataset

The dataset contains labeled images of Indian Sign Language alphabets and gestures.

Dataset Structure:
dataset/
│
├── A/
├── B/
├── C/
├── 0/
├── 1/
└── emergency/
You can use:

Custom collected dataset

Kaggle ISL datasets

Self-recorded gesture images

🧠 Model Training

Data Augmentation applied

CNN architecture used for classification

Loss Function: Categorical Cross-Entropy

Optimizer: Adam

Evaluation Metrics: Accuracy

Model is saved as:

model.h5
📊 Results

Training Accuracy: ~98%

Validation Accuracy: ~92%

Real-time performance with minimal latency

🎯 Applications

Assistive communication tool for the hearing and speech impaired

Educational tool for learning ISL

Public service integration (banks, hospitals, government offices)

Smart accessibility systems

📌 Future Enhancements

Sentence formation using NLP

Speech synthesis integration

Mobile application deployment

Transformer-based or LSTM-based sequence modeling

Larger dataset training for higher accuracy

This project demonstrates the practical implementation of deep learning in accessibility technology and promotes inclusive communication through AI-driven solutions.

🤝 Contributing

Contributions are welcome! If you’d like to improve this project:

Fork the repository

Create a new branch

Commit your changes

Submit a Pull Request

📜 License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0).

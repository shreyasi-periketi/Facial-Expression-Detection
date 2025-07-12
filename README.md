# Facial-Expression-Detection

## Project Summary: Facial Expression Detection using CNN
This project aims to develop an automatic facial expression recognition system using a custom Convolutional Neural Network (CNN). Built during a summer internship at Suntek Corp Solutions Pvt. Ltd., Hyderabad, the system is trained on the FER-2013 dataset, which contains over 35,000 grayscale images labeled across 7 universal emotions: Happy, Sad, Angry, Fear, Surprise, Disgust, and Neutral.

The model architecture includes six layers — four convolutional and two dense layers — and leverages techniques such as batch normalization, ReLU activation, dropout, and SoftMax to optimize training and classification. Python, OpenCV, and DeepFace were used for preprocessing and facial detection, while training and testing were conducted in Google Colab using Jupyter Notebook.

Key features include:
- Real-time emotion detection using webcam input via Flask
- Use of ImageDataGenerator for data augmentation and batch training
- Achieved 62.7% validation accuracy, close to the benchmark average for FER-2013

Despite challenges in accurately detecting expressions like fear, the model performed well on happy and surprised classes. Future improvements include better handling of low-light conditions, enhanced data augmentation, and hyperparameter tuning to reduce overfitting.

This project demonstrates the potential of CNNs in human-computer interaction systems and contributes to applications in healthcare, security, customer feedback, and emotion-aware AI.


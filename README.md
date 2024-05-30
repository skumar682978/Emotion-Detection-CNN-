###Emotion Detection Using CNN, ResNet50, and VGG16

**Overview**

This project aims to detect human emotions from facial images using Convolutional Neural Networks (CNNs). The project implements three different models: a custom CNN, ResNet50, and VGG16. Each model is trained and evaluated to compare their performance in emotion detection.

## Dataset

The project uses the FER2013 dataset, which contains grayscale images of faces labeled with one of seven emotions: anger, disgust, fear, happiness, sadness, surprise, and neutral.

## Model Architectures Used

### Custom CNN

A custom Convolutional Neural Network (CNN) built from scratch with the following layers:

- Convolutional layers
- Max-pooling layers
- Fully connected (dense) layers
- Dropout layers for regularization

### ResNet50

ResNet50 is a deep residual network with 50 layers, known for its robustness in image classification tasks. We fine-tune a pre-trained ResNet50 model on the FER2013 dataset.

### VGG16

VGG16 is a convolutional neural network with 16 layers, known for its simplicity and effectiveness in image classification tasks. We fine-tune a pre-trained VGG16 model on the FER2013 dataset.

**Model** **Training**

There are various concept like:

- Transfer leaning
- Model fine tuning
- Data augmentation
- Class weights

These concepts are used in the training process to get the best possible classification result on the FER2013 emotions dataset

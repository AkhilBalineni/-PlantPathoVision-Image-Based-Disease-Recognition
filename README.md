# PlantPathoVision-Image-Based-Disease-Recognition
PlantPathoVision is a deep learning based plant disease recognition tool built using Convolutional Neural Networks. Leveraging the PlantVillage dataset with 20.6K leaf images, the project focuses on detecting bacterial spot disease in pepper leaves using image classification techniques.

The model pipeline includes extensive data augmentation using ImageDataGenerator with transformations like flipping, zooming, rotation, brightness adjustments, and shifting to improve generalization. A custom CNN trained on a T4 GPU achieved 85 percent accuracy in distinguishing between healthy and diseased pepper leaves.

With global crop losses reaching up to 40 percent annually due to plant diseases, this project demonstrates how early detection using image based deep learning models can help prevent large scale food and economic loss. Built as part of the Statistical Machine Learning (CSE 575) course at Arizona State University, this work showcases the power of CNNs in real world agriculture use cases.

# Lung Cancer Classification Using Convolutional Neural Networks

Overview

This project involves the development of a Convolutional Neural Network (CNN) to classify lung tissue images into three categories:

Lung adenocarcinomas

Lung squamous cell carcinomas

Benign lung tissues

The model is designed to assist in automating lung cancer diagnosis, with a primary goal of improving early detection and supporting clinical decision-making.

Dataset

The dataset consists of 15,000 labeled images distributed across three categories:

lung_aca: 5000 images of lung adenocarcinomas.

lung_scc: 5000 images of lung squamous cell carcinomas.

lung_n: 5000 images of benign lung tissues.

These images are stored in the lung_image_sets folder, organized into subfolders for each category.

Methodology

Data Preprocessing:

Images were resized to a uniform shape to match the input requirements of the CNN.

Data augmentation techniques, such as rotation, flipping, and scaling, were applied to enhance model robustness.

Model Architecture:

The CNN architecture includes convolutional layers with ReLU activation, pooling layers, and fully connected layers.

Dropout was employed to prevent overfitting.

Training and Evaluation:

The model was trained using a training-validation split of the dataset.

Cross-entropy loss was used as the loss function, and the Adam optimizer was applied for efficient training.

Performance

The CNN achieved an accuracy of 96% on the test set, demonstrating high effectiveness in distinguishing between the three categories of lung tissue.

Key Features

Automated classification of lung tissue images.

High accuracy, enabling potential application in clinical settings.

Scalable and adaptable for integrating additional datasets or tissue types.

Impact

This project provides a foundation for leveraging deep learning in medical imaging, potentially aiding medical professionals in early cancer detection and improving patient outcomes.

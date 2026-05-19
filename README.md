# Deep_Learning_Project

## Company Name
CODTECH IT SOLUTIONS

---

## Name
Harshal Laxman Yaravalkar

---

## Intern ID
CTIS8789

---

## Domain
Data Science

---

## Duration
4 Weeks

---

## Mentor
Neela Santhosh Kumar

---

# Image Classification using CNN and PyTorch

## Project Description

This project focuses on implementing a deep learning based image classification model using Convolutional Neural Networks (CNNs) and PyTorch. The objective of this task was to build a functional image classification system capable of identifying and categorizing images automatically.

Image classification is one of the most widely used applications of deep learning and computer vision. CNNs are especially effective for image-related tasks because they can automatically learn important visual features such as edges, textures, patterns, and shapes directly from image data.

For this project, the CIFAR-10 dataset provided by PyTorch was used. The dataset contains 60,000 color images divided into 10 different classes including airplanes, automobiles, birds, cats, dogs, frogs, horses, ships, and trucks. Each image has a resolution of 32x32 pixels.

The project was implemented using PyTorch and Torchvision libraries. The first stage of the workflow involved loading and preprocessing the dataset. Image preprocessing was performed using transformations such as converting images into tensors and normalizing pixel values. Normalization helps improve model convergence during training and ensures stable learning.

After preprocessing, the dataset was loaded into batches using PyTorch DataLoaders. Batch loading improves training efficiency and helps the model process large datasets more effectively.

The next step involved building the Convolutional Neural Network architecture. The CNN model consisted of:
- convolutional layers
- activation functions
- pooling layers
- fully connected layers

The convolutional layers were responsible for extracting image features while the pooling layers reduced spatial dimensions and improved computational efficiency. ReLU activation functions were used to introduce non-linearity into the network.

The model was trained using the CrossEntropyLoss loss function and the Adam optimizer. Training was performed for multiple epochs, where the network continuously updated its weights to minimize prediction error. During training, loss values gradually decreased, showing that the model was learning useful image patterns from the dataset.

After training, the model was evaluated on the test dataset to measure classification accuracy. The model achieved reasonable performance considering the simple CNN architecture and limited training epochs.

The project also includes visualization of prediction results. Sample test images along with predicted and actual labels were displayed using Matplotlib. This helps visually evaluate how well the model performs on unseen data.

This project demonstrates important deep learning concepts such as:
- image preprocessing
- convolutional neural networks
- feature extraction
- model training
- prediction visualization
- performance evaluation

The technologies used in this project include:
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib

Overall, this project successfully demonstrates the implementation of a CNN-based image classification system using PyTorch and provides practical understanding of deep learning workflows for computer vision tasks.

---

# Requirements

```bash
pip install torch torchvision matplotlib numpy
```

---

# How to Run

```bash
python cnn_classifier.py
```

The script will:
- download the CIFAR-10 dataset
- preprocess image data
- train the CNN model
- evaluate model accuracy
- display prediction results

---

# Example Output

## Model Training Output
<img width="338" height="190" alt="Screenshot 2026-05-19 164504" src="https://github.com/user-attachments/assets/c5bf2f31-9403-4c62-bbf7-bd3c65d5eba9" />


---

## Prediction Visualization
<img width="1033" height="255" alt="Screenshot 2026-05-19 164547" src="https://github.com/user-attachments/assets/00c2f6b8-0187-4b6e-921f-cffa1a027bdb" />

---

# Features of the Project

- image preprocessing using Torchvision
- custom CNN implementation
- model training and testing
- prediction visualization
- deep learning workflow using PyTorch

---

# Future Improvements

Possible future improvements:
- train for more epochs
- use GPU acceleration
- implement data augmentation
- use deeper CNN architectures
- save and reload trained models

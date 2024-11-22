Image Classification with CNNs on CIFAR-10

This project focuses on developing an image classification model using Convolutional Neural Networks (CNNs) on the CIFAR-10 dataset, aiming to classify images into ten distinct categories.

Dataset

The CIFAR-10 dataset contains 60,000 color images across 10 classes, with 6,000 images per class. The categories are:

• Airplane

• Automobile

• Bird

• Cat

• Deer

• Dog

• Frog

• Horse

• Ship

• Truck

Each image is 32x32 pixels, showcasing variability in pose, lighting, and backgrounds.
Methodology:

1. Model Architecture:
   - Input Layer: 32x32x3
   - Convolutional Layers: 3 layers with ReLU activation
   - Pooling Layers: Max pooling after convolution
   - Dense Layers: Fully connected for classification

2. Training:
   - Epochs: 10
   - Batch Size: 64
   - Optimizer: Adam (lr: 0.001)

3. Data Preprocessing:
   - Normalization and data augmentation for robustness.

4. Results:
   - CNN Accuracy: ~71%
   - Model Comparison:
     - RNN: 37%
     - Decision Tree: 26%

Indicates CNNs excel in high-dimensional image processing.

Challenges

Key challenges included class overlap and significant intra-class variability, especially among visually similar categories like 'Cat' and 'Dog'.

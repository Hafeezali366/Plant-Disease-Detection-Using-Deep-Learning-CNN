# Plant-Disease-Detection-Using-Deep-Learning-CNN
This project implements deep learning techniques to classify tomato plant diseases using the PlantVillage dataset. It compares the performance of two convolutional neural network (CNN) architectures, VGG16 and ResNet50, for precise identification of diseases in tomato leaves. The trained models aim to provide a foundation for real-world agricultural applications, enabling early disease detection and sustainable farming practices.

Dataset
Source: PlantVillage Dataset (obtained from the Mendeley Data repository)
Classes Used: The last 10 classes of the dataset, focusing on tomato plant diseases.
Data Split:
Training: 60%
Validation: 20%
Testing: 20%

Methodology
1. Data Preprocessing:
Resizing images to 224x224 pixels.
Normalizing pixel values.
Applying data augmentation (rotation, zoom, flipping, etc.).
2. Model Selection:
VGG16: Achieved an accuracy of 83%.
ResNet50: Achieved an accuracy of 52%.
3. Training:
Optimizer: Adam
Loss Function: Categorical Cross-Entropy
Learning Rate: 0.0001
Epochs: 10

Results
VGG16: Demonstrated superior performance with better generalization and accuracy.
ResNet50: Showed limitations in this context, with slower convergence and lower accuracy.

Requirements
Python 3.x
TensorFlow 2.x
NumPy
Matplotlib
Jupyter Notebook
Google Colab (optional for training)

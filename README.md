[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.10.12-red.svg)](https://www.python.org/downloads/release/python-31012/)
[![PyTorch Version](https://img.shields.io/badge/PyTorch-1.9.0-green.svg)](https://pytorch.org/get-started/locally/)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/PKhosravi-CityTech/DepthNet/blob/main/DepthNet.ipynb)


# DepthNet

:diamond_shape_with_a_dot_inside: DepthNet: A Versatile Deep Learning Model for MRI Image Analysis with Applications in Cancer Research.

In the development of the DepthNet neural network architecture, we employed a sophisticated approach utilizing depthwise separable convolutions to create an efficient and effective model for image classification tasks. The architecture consists of four depthwise separable convolution blocks, each comprising a depthwise convolution layer followed by a pointwise convolution layer, which significantly reduces the number of parameters compared to traditional convolutional networks. This design choice not only improves computational efficiency but also reduces overfitting due to the decreased model complexity.

Each block includes batch normalization and ReLU activation functions to stabilize learning and introduce non-linearity, followed by max pooling to reduce spatial dimensions and enhance feature extraction. The network's output from the convolutions is processed through fully connected layers, incorporating a dropout rate of 60% before the final classification layer to prevent overfitting further. This model architecture is tailored to operate efficiently on both CPU and GPU environments, ensuring versatile deployment capabilities. The model initializes with a simple binary classification objective but can be adapted to accommodate more classes as needed. This adaptability makes DepthNet suitable for a wide range of image recognition applications, demonstrating its robustness and scalability in practical scenarios.

<img src="https://github.com/PKhosravi-CityTech/DepthNet/blob/main/Images/Depth.png" width="500" />

The DepthNet model is a CNN designed for analyzing high-resolution MRI images (input size 512x512). It features multiple convolutional layers, batch normalization, ReLU activations, and dropout to meticulously extract and analyze image features. Notably, the model classifies images into one of two categories, such as effective or ineffective treatment responses, and measures patient-level accuracy. We utilize early stopping techniques to enhance training efficiency and prevent overfitting, terminating training if there's no improvement in validation accuracy over a set number of epochs.

This script outlines the DepthNet model's implementation using PyTorch, from the architecture's setup to its readiness for both training and evaluation. This ensures the model not only learns effectively but also generalizes well across new, unseen data.

:diamond_shape_with_a_dot_inside: Please access the "DepthpNet.ipynb" file on Google Colab and follow the provided instructions. Additionally, you can find sample images labeled as "Data.zip" in the "Images" folder. Please be aware that these images are provided as examples to demonstrate the required format, and you will need to gather a larger set of images for training the model. 

🛰️ **Citation Request:** If you find the contents and tools in this repository valuable for your work, we kindly request that you cite it in your research or project. Your citation helps acknowledge the effort put into creating and maintaining these AI-driven resources.

📚 **How to Cite:** When referencing this repository, please use the following citation format:

> Khosravi P., *DepthNet*, BioMind AI Lab, Department of Biological Sciences, New York City College of Technology, CUNY, New York City, NY, USA. Released in 2023. [Link to Repository](https://github.com/PKhosravi-CityTech/DepthNet)

Thank you for contributing to the advancement of AI and research. 🤖


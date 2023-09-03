[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.10.12-red.svg)](https://www.python.org/downloads/release/python-31012/)
[![PyTorch Version](https://img.shields.io/badge/PyTorch-1.9.0-green.svg)](https://pytorch.org/get-started/locally/)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/PKhosravi-CityTech/ExCapNet/blob/main/ExCapNet.ipynb)


# ExCapNet

:diamond_shape_with_a_dot_inside: ExCapNet: A Versatile Deep Learning Model for MRI Image Analysis with Applications in Cancer Research.

The ExCapNet model is a convolutional neural network (CNN) designed for precise prostate cancer extracapsular extension (ECE) detection using MRI images. It employs multiple convolutional layers, batch normalization, ReLU activations, and dropout to extract and analyze image features. In this critical task, the model classifies images into one of two categories, indicating the presence or absence of ECE (Y_ECE vs. N_ECE).

It's noteworthy that the MRI images used for training and evaluation are labeled with T2 and T3 pathology results, enriching the model's ability to discern between the different classes accurately. This combination of architectural design and labeled data empowers ExCapNet to provide precise predictions for new, unseen MRI images.

This script encompasses the implementation of the ExCapNet model using PyTorch. Following the definition of the architecture, the model is instantiated and poised for both training and evaluation, contributing to advancements in the critical field of prostate cancer diagnosis.

<img src="https://github.com/PKhosravi-CityTech/ExCapNet/blob/main/Images/ExCapNet.png" width="500" />

The ExCapNet GitHub repository provides a comprehensive resource suitable for both experts and beginners in the realm of deep learning and clinical image analysis. Particularly noteworthy is the inclusion of a meticulously curated Colab file, accompanied by step-by-step instructions. This feature is designed to empower newcomers, enabling them to confidently navigate the model training process. With its user-friendly approach, the Colab file serves as a valuable guide, allowing novices to embark on a successful journey of model training without unnecessary complexities. Whether you are a seasoned practitioner or a novice eager to explore the world of deep learning, the ExCapNet GitHub repository equips you with the necessary tools and guidance to effectively harness the potential of this innovative algorithm.

:diamond_shape_with_a_dot_inside: Please access the "ExCapNet.ipynb" file on Google Colab and follow the provided instructions. Additionally, you can find sample images labeled as "Data.zip" in the "Images" folder. Please be aware that these images are provided as examples to demonstrate the required format, and you will need to gather a larger set of images for training the model. 

🛰️ **Citation Request:** If you find the contents and tools in this repository valuable for your work, we kindly request that you cite it in your research or project. Your citation helps acknowledge the effort put into creating and maintaining these AI-driven resources.

📚 **How to Cite:** When referencing this repository, please use the following citation format:

> *ExCapNet*, BioMind AI Lab, Department of Biological Sciences, New York City College of Technology, CUNY, New York City, NY, USA. Released in 2023. [Link to Repository](https://github.com/PKhosravi-CityTech/ExCapNet)

Thank you for contributing to the advancement of AI and research. 🤖


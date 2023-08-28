[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
[![Python Version](https://img.shields.io/badge/python-3.10.12-red.svg)](https://www.python.org/downloads/release/python-31012/)
[![PyTorch Version](https://img.shields.io/badge/PyTorch-1.9.0-green.svg)](https://pytorch.org/get-started/locally/)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/PKhosravi-CityTech/LightCnnRad/blob/main/LightCnnRad.ipynb)


# ExCapNet

:diamond_shape_with_a_dot_inside: ExCapNet: A Versatile Deep Learning Model for MRI Image Analysis with Applications in Cancer Research.

The ExCapEx model is a deep learning architecture designed for the detection of extracapsular extension in MRI images. This task involves classifying images into one of two categories, indicating the presence or absence of extracapsular extension. The model utilizes a convolutional neural network (CNN) to automatically learn relevant features from the input images. It consists of several convolutional layers followed by batch normalization, ReLU activation, and max-pooling. The learned features are then fed through fully connected layers to make the final prediction.

The architecture of the ExCapEx model is designed to capture intricate patterns and features from the MRI images that are indicative of extracapsular extension. By training on labeled data, the model learns to distinguish between the different classes, enabling it to provide accurate predictions on new, unseen MRI images.

This script contains the implementation of the ExCapEx model using PyTorch. After defining the architecture, the model is instantiated and ready to be trained and evaluated. Adjust the 'num_classes' parameter as needed for your specific classification task.

<img src="https://github.com/PKhosravi-CityTech/ExCapNet/blob/main/Images/ExCapNet.png" width="500" />

The ExCapEx GitHub repository provides a comprehensive resource suitable for both experts and beginners in the realm of deep learning and clinical image analysis. Particularly noteworthy is the inclusion of a meticulously curated Colab file, accompanied by step-by-step instructions. This feature is designed to empower newcomers, enabling them to confidently navigate the model training process. With its user-friendly approach, the Colab file serves as a valuable guide, allowing novices to embark on a successful journey of model training without unnecessary complexities. Whether you are a seasoned practitioner or a novice eager to explore the world of deep learning, the ExCapEx GitHub repository equips you with the necessary tools and guidance to effectively harness the potential of this innovative algorithm.

:diamond_shape_with_a_dot_inside: Please access the "LightCnnRad.ipynb" file on Google Colab and follow the provided instructions. Additionally, you can find sample images labeled as "Data_Brain.zip" in the "Images" folder. Please be aware that these images are provided as examples to demonstrate the required format, and you will need to gather a larger set of images for training the model. 

🛰️ **Citation Request:** If you find the contents and tools in this repository valuable for your work, we kindly request that you cite it in your research or project. Your citation helps acknowledge the effort put into creating and maintaining these AI-driven resources.

📚 **How to Cite:** When referencing this repository, please use the following citation format:

> *ExCapNet*, BioMind AI Lab, Department of Biological Sciences, New York City College of Technology, CUNY, New York City, NY, USA. Released in 2023. [Link to Repository](https://github.com/PKhosravi-CityTech/ExCapNet)

Thank you for contributing to the advancement of AI and research. 🤖

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br /> This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.



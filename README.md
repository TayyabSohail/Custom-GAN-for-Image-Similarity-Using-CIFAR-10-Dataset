# Custom-GAN-for-Image-Similarity-Using-CIFAR-10-Dataset

## Research Paper: 
[Tayyab_question_2_report.pdf](https://github.com/user-attachments/files/17556969/Tayyab_question_2_report.pdf)


# Project Overview
This project involves training a custom Generative Adversarial Network (GAN) using the CIFAR-10 dataset, focusing on the classes of cats and dogs. The generator and discriminator models were built with a unique approach:

Generator: Follows a standard design to generate synthetic images.
Discriminator: Modified to assess the similarity between generated and real images by producing a similarity score. It uses a Siamese Network architecture to effectively measure the similarity between two images.
The goal is for the generator to minimize this similarity score, making the generated images as close as possible to real images, while the discriminator works to maximize the dissimilarity.

# Tools and Technologies Used

Programming Language: Python

# Libraries:

TensorFlow/Keras: For building and training GAN models

NumPy: For data manipulation

OpenCV/PIL: For image processing

Dataset: CIFAR-10, focusing on cats and dogs

# Techniques:

Generative Adversarial Network (GAN)

Image similarity scoring

Siamese Network architecture

Custom discriminator design


# Setup and Installation

## Clone the repository:


git clone https://github.com/your-username/custom-gan-image-similarity.git

cd custom-gan-image-similarity

## Install the required dependencies:

pip install -r requirements.txt

Download the CIFAR-10 dataset (automatically handled within the code).


## How to Run

Train the GAN model:

python train.py

View results: The trained model will output generated images, and similarity scores can be evaluated against the real images.


# Results
The custom GAN is designed to generate images that closely resemble real ones from the CIFAR-10 dataset (cats and dogs) based on image similarity. The discriminator is specifically trained to evaluate this similarity, offering a unique approach to standard GAN training.

![image](https://github.com/user-attachments/assets/cfb68968-c9ac-4406-ad93-ba0b26d1a787)

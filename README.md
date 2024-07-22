# Retrieval-based-Object-Recognition-and-Reconstruction-via-VAE-and-FAISS
 
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-blue)
![FAISS](https://img.shields.io/badge/FAISS-white)
![Generative AI](https://img.shields.io/badge/Generative%20AI-green)
![CLIP](https://img.shields.io/badge/CLIP-Contrastive%20Language%20Image%20Pretraining-orange)
![vae](https://img.shields.io/badge/VAE-Variational%20Auto%20Encoder-white)
![Image Reconstruction](https://img.shields.io/badge/Image%20Reconstruction-purple)
![Robotics Application](https://img.shields.io/badge/Robotics%20Application-black)
![Cosine Similarity](https://img.shields.io/badge/Cosine%20Similarity-grey)
![Noise Injection](https://img.shields.io/badge/Noise%20Injection-yellow)

Project Overview

Among the most impactful technologies, retrieval-based methods and generative models have demonstrated remarkable capabilities in image retrieval, object recognition, and image reconstruction. This project, titled "Retrieval-based Object Recognition and Reconstruction via VAE and FAISS," aims to leverage these technologies to create a robust system capable of recognizing and reconstructing objects based on their latent representations.

The core of this project lies in the integration of Variational Autoencoders (VAEs) with Facebook AI Similarity Search (FAISS). VAEs are powerful generative models that can learn to encode images into a continuous latent space, capturing essential features and structures. By manipulating these latent representations, VAEs can generate new images or reconstruct existing ones with high fidelity. FAISS, on the other hand, is a state-of-the-art library for efficient similarity search and clustering of high-dimensional vectors. It excels in quickly finding the most similar vectors within large datasets, making it ideal for image retrieval tasks.

## Table of Contents
1. [Introduction](#introduction)
2. [Architecture](#architecture)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Results](#results)
6. [Limitation](#introduction)
7. [Future Work](#introduction)
  
# Introduction

This project introduces a novel approach where VAEs are used to encode images into latent vectors, which are then stored and organized using FAISS. When a query image is provided, its latent representation is computed and FAISS retrieves the most similar latent vectors from the dataset. These retrieved latent vectors are subsequently decoded by the VAE to reconstruct the corresponding images. Additionally, by manipulating the latent space with varying sigma values, the project explores the reconstruction of images with different levels of noise and variation, providing insights into the generative capabilities of VAEs.

This project holds significant potential across various applications, including medical imaging, autonomous vehicles, robotics, e-commerce, and more, by addressing practical challenges and contributing to the advancement of AI technologies.

# Architecture

<img src="https://github.com/Dherya27/Object-Recognition-and-Reconstruction-through-CLIP-VAE-Integration/blob/main/results/img/overall_architecrture.png">

# Installation and Usage


# Results

#### Training Plot
<img src="https://github.com/Dherya27/Retrieval-based-Object-Recognition-and-Reconstruction-via-VAE-and-FAISS/blob/main/results/training_loss_plot.png" width="900" height="400">

<img src="https://github.com/Dherya27/Object-Recognition-and-Reconstruction-through-CLIP-VAE-Integration/blob/main/results/reconstruction.gif">

#### Query Image 1
<img src="https://github.com/Dherya27/Object-Recognition-and-Reconstruction-through-CLIP-VAE-Integration/blob/main/results/query/2c304c54a6141d214ff3c6764341833_easy_04.png" width="150" height="150">

#### Retrieval-based Reconstructed Images (k=5) from FAISS VectorDB

<img src="https://github.com/Dherya27/Object-Recognition-and-Reconstruction-through-CLIP-VAE-Integration/blob/main/results/reconstructed_img/retrieval_based_reconstrcution_car1.png">

#### Reconstruction by Manipulating Latent Space with Noise Injection
<img src="https://github.com/Dherya27/Retrieval-based-Object-Recognition-and-Reconstruction-via-VAE-and-FAISS/blob/main/results/noise/car.png">

#### Query Image 2
<img src="https://github.com/Dherya27/Object-Recognition-and-Reconstruction-through-CLIP-VAE-Integration/blob/main/results/query/3f11833d3d9309bc9952c05a06935ddc_easy_02.png" width="150" height="150" >

#### Retrieval-based Reconstructed Images (k=5) from FAISS VectorDB
<img src="https://github.com/Dherya27/Object-Recognition-and-Reconstruction-through-CLIP-VAE-Integration/blob/main/results/reconstructed_img/retrieval_based_reconstruction_chair_1.png">

#### Reconstruction by Manipulating Latent Space with Noise Injection
<img src="https://github.com/Dherya27/Retrieval-based-Object-Recognition-and-Reconstruction-via-VAE-and-FAISS/blob/main/results/noise/chair.png">


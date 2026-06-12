# Cuckoo Eggs Similarity Evaluation (in progress)
This repository contains an implementation for analyzing the similarity of cuckoo eggs to those of their host species using a deep learning-based approach. The project is designed to compute and compare image similarities, leveraging Siamese networks for accurate and interpretable predictions.
## Objective
The primary goal of this project is to evaluate the similarity between cuckoo eggs and host eggs to understand mimicry patterns. The approach involves feature extraction and comparison using a Siamese network and feature extraction by different NN.
## Features
- Deep Learning Framework: Siamese network implementation for pairwise image similarity prediction.
- Customizable Model Training: Allows users to train the model on new datasets of egg images with labeled grades of similarity.
- Image Processing: Preprocessing and augmentation of egg images to enhance model training.
- Evaluation Metrics: Performance evaluation using metrics like loss, accuracy, and precision.
## Input/Output
**Input:** Pairs of images representing cuckoo and host eggs with similarity grades. <br>
**Output:** A trained model for predicting similarity, similarity scores for test images, and visualizations of the results.
## Dataset
Visit [Link](https://drive.google.com/drive/folders/1TKBZJ1dyS87aoSb5hhke-UP_7wpxADMd?usp=drive_link) to the dataset  containing images for Cuckoo Eggs, a table for pairs, and a table of  image names.


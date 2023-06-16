# ML Club Assignment

This repository contains my submission for the ML Club membership assignment. The assignment consists of four questions, and I have provided my answers and explanations for each question. The questions cover various topics related to machine learning, including paper review, model selection, mathematics, and implementation.

## Question 1: Paper Review

For this question, I have reviewed the paper titled "ImageNet Classification with Deep Convolutional Neural Networks" by Krizhevsky et al., published in 2012. The paper, popularly known as AlexNet, is considered one of the most influential papers in the field of computer vision and has had a significant impact on the AI revolution. In my review, I have discussed the significance of the paper, its contributions, and potential areas for improvement beyond what was mentioned in the future works section of the paper.

## Question 2: Model Selection

In this question, I have provided model suggestions for different datasets along with reasoning and references to relevant papers. The datasets and their associated tasks are as follows:

1. Predicting Bacterial Property: A dataset with 20,000 rows and 150 columns, where each column describes a property of bacteria. I have discussed the limitations of using a large neural network for this task and suggested alternative models. I have also provided references to relevant papers.
For a dataset like this, models like **LightGBM**, **MLP** and **XGBoost** can be used. 

2. Predicting the Number of People on the Beach: The task is to predict the crowd size on a beach based on normalized weather features. I have discussed the factors influencing beach attendance and suggested models for accurate prediction. References to relevant papers have been provided.
Models like **Linear Regression**, **Random Forest**, **Gradient Boosting**, **SVM** and **Neural Networks** can be used for datasets like this.

3. Text-Image Search Engine: Using the MS-COCO 2014 dataset, the goal is to create an AI-based search engine that can return text descriptions for given images and vice versa. I have described the expected model, methodology, and loss function for this task. Relevant papers have been cited.
For tasks involving both images and text, models like **ViLBERT**, **CNN_NLP** and **VSE** can be used. 

4. Matrix Multiplication: Given a dataset of random 3x3 matrices and their matrix product, the task is to perform matrix multiplication. I have discussed the techniques for optimizing speed and accuracy in matrix multiplication and the impact of GPU availability. Different scenarios, with and without GPU access, have been considered.
For the task of matrix multiplication, we levarage libraries like **CuBLAS**.
For optimizing speed, **MKL**, **CuBLAS** can be used
When the goal is to optimize accuracy, **MLP** can be applied

## Question 3: Mathematics Description

This question emphasizes the importance of mathematics in machine learning and provides an opportunity to explore Gaussian Processes Regression. Gaussian Processes Regression combines elements of multivariable calculus, linear algebra, probability theory, and statistics. I have discussed the concept of Gaussian Processes, constructing the kernel function, positive-semidefiniteness, Cholesky decomposition, and assumptions for the problem. Additionally, I have provided a blog link for further understanding of Gaussian Processes.

## Question 4: Implementation

For the final question, I have chosen one implementation challenge from a list of interesting models. I have implemented the **Vanilla Autoencoder** using the PyTorch library. The Vanilla Autoencoder is a neural network trained to reproduce its input at the output layer and can be used for tasks such as data compression and denoising. I have mentioned the difficulty level of the implementation and the recommended libraries for each challenge.

Each question's answer contains detailed explanations, reasoning, and references wherever applicable.

Thank you for considering my submission.

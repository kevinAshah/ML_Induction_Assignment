# ML Club Assignment

This repository contains my submission for the ML Club membership assignment. The assignment consists of four questions, and I have provided my answers and explanations for each question. The questions cover various topics related to machine learning, including paper review, model selection, mathematics, and implementation.

## Question 1: Paper Review

For this question, I have reviewed the paper titled "ImageNet Classification with Deep Convolutional Neural Networks" by Krizhevsky et al., published in 2012. The paper, popularly known as AlexNet, is considered one of the most influential papers in the field of computer vision and has had a significant impact on the AI revolution. In my review, I have discussed the significance of the paper, its contributions, and potential areas for improvement beyond what was mentioned in the future works section of the paper.

## Question 2: Model Selection

In this question, I have provided model suggestions for different datasets along with reasoning and references to relevant papers. The datasets and their associated tasks are as follows:

1. Predicting Bacterial Property: A dataset with 20,000 rows and 150 columns, where each column describes a property of bacteria. I have discussed the limitations of using a large neural network for this task and suggested alternative models. I have also provided references to relevant papers.

2. Predicting the Number of People on the Beach: The task is to predict the crowd size on a beach based on normalized weather features. I have discussed the factors influencing beach attendance and suggested models for accurate prediction. References to relevant papers have been provided.

3. Text-Image Search Engine: Using the MS-COCO 2014 dataset, the goal is to create an AI-based search engine that can return text descriptions for given images and vice versa. I have described the expected model, methodology, and loss function for this task. Relevant papers have been cited.

4. Matrix Multiplication: Given a dataset of random 3x3 matrices and their matrix product, the task is to perform matrix multiplication. I have discussed the techniques for optimizing speed and accuracy in matrix multiplication and the impact of GPU availability. Different scenarios, with and without GPU access, have been considered.

## Question 3: Mathematics Description

In this project, I have explored Gaussian Process regression and its application in constructing a surrogate function using the squared exponential kernel (also known as the RBF kernel). Gaussian Processes combine elements of multivariable calculus, linear algebra, and probability theory, making them a powerful tool in machine learning.

To derive the posterior predictive distribution, I define the RBF kernel, ensuring its positive-semidefinite property for a valid Gaussian process. I then perform Cholesky decomposition on the kernel matrix to obtain the lower triangular matrix, which aids in calculating regression weights and predictions. This closed-form solution allows us to smoothly interpolate between data points and extrapolate well into the test data.

In the implementation phase, I utilize Python and numpy to build a Gaussian Process regression model. By employing basic operations, I evaluate its performance on a toy dataset, validating the effectiveness of the derived mathematical framework.

Furthermore, I discuss the concept of extrapolation in Gaussian Processes and its definition of how well the model predicts unseen data points. I distinguish the optimization process in Gaussian Process regression from that of regular neural networks, emphasizing the closed-form solution's role in capturing underlying trends and patterns.

Lastly, I explored the possibility of adapting Gaussian Processes for classification tasks using Gaussian Process Classification (GPC). GPC models estimate the posterior distribution over class labels and can provide probabilistic predictions in addition to continuous outputs.

## Question 4: Implementation

Transformer Implementation using PyTorch
The Transformer is a state-of-the-art model widely used in natural language processing tasks for sequence transduction.

Key Features Implemented
Positional Encoding: The implementation includes positional encoding to provide information about the relative positions of words in the input sequence. This enables the model to capture positional relationships effectively.

Multi-Head Attention: The implementation includes multi-head attention, allowing the model to focus on different word dependencies simultaneously. It applies self-attention multiple times in parallel, capturing different types of relationships.

Self-Attention: The self-attention mechanism is implemented to weigh different words in the input sequence when making predictions. It captures relationships between words by assigning attention weights based on their relevance to other words in the sequence.

Encoder-Decoder Mechanism: The transformer architecture's fundamental encoder-decoder structure is implemented. The encoder processes the input sequence and generates a hidden representation, capturing the input's meaning. The decoder takes the encoder's hidden representation and generates the output sequence.


Each question's answer contains detailed explanations, reasoning, and references wherever applicable.

Thank you for considering my submission.

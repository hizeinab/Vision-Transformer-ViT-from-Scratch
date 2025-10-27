This notebook implements a Vision Transformer (ViT) model from scratch using PyTorch. The ViT architecture is introduced in the machine learning research paper titled "An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale" by Dosovitskiy et al., 2021 (https://arxiv.org/abs/2010.11929). The goal is to understand the core components of a ViT and train it on a small dataset.

The notebook covers the following steps:

-Setup: Installs necessary libraries and builds required functions for a classification task.
-Data Loading: Downloads the dataset from a given URL
-Model Architecture: Defines the key components of the ViT model, including Patch Embedding, Multihead Self-Attention, MLP Block, Transformer Encoder, and the main ViT class.
-Training: Sets up the optimizer and loss function, and trains the ViT model on the downloaded dataset.
-Results: Visualizes the training and testing loss and accuracy curves, as well as making predictions on some images.
Thank you to everyone involved in the Zero to Mastery Learn PyTorch for Deep Learning course, available at https://www.learnpytorch.io/.

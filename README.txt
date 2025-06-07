Description: In this project I have implemented a multilayer perceptron (MLP) character-level language model.

What I learned:

Python:
- torch
  - randn(): initialize a tensor with random numbers from a normal distribution
  - view(): change dimensions of a tensor (ex: [9, 2] --> [6, 3])
  - cross_entropy(): computes loss

AI:
- Context length: number of tokens the model can process at once
- Embeddings: numerical representations of (in this case) letters
- Using mini-batches rather than the whole training set
- Learning rate decay: reducing learning rate towards end of training process
- To avoid overfitting, split data:
  - Training split: used to tune parameters of model
  - Dev/validation split: used to tune hyperparameters
  - Test split: used to evaluate model's performance at the end

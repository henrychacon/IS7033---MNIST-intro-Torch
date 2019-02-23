# MNIST example using a GPU unit

The aim of the attached project is to test the use of GPU to process torch tensors associated with the weights and bias in simple perceptron units in figures ten labels figures of 28x28 pixels. 

Since in this case, the idea is not to train a sophisticated model, but practice with PyTorch tensors, the cross-entropy loss, the one-hot vectors, and linear functions were implemented step by step, using the GPU as the processor unit.

Hence, the trained model has 28*28 input units and 10 outputs. The distribution of the weights of each unit and a map of each one is also presented.

**Theorem**: The translation $[\![e]\!]$ given by

# Multiplication Neural Network
The notebook contains a neural network that learns to multiply two integers using PyTorch.

## Requirements:
1. The file was originally made using Python 3.12.7
2. The only package used is torch

## How to run:
1. First run all the cells
2. The last cell in the last section can be used to predict values by changing x1 and x2, and then running the cell.

## Approach
The model does not learn multiplication itself like a human (AKA 7 x 4 = 7 + 7 + 7 + 7) but instead learns from relations. This means that 2 x 3 could have 6 as output, but also 7 or 5 as example. This is also the reason only 20 random samples are used. This forces the model to figure out some sort of multiplication relationship.

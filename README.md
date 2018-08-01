#  Classification of Fashion-MNIST dataset using CNN models. 

Classification of Fashion products using different neural network based models -- Feedforward, CNN, VGG, etc.


# Data
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.

| Target Class  |   Definition  |
|     :---:     |     :---:     |
|       0       |    T-shirt    |
|       1       | Trouser  |
|       2       | Pullover  |
|       3       | Dress   |
|       4       | Coat  |
|       5       | Sandal  |
|       6       | Shirt  |
|       7       | Sneaker  |
|       8       | Bag |
|       9       | Ankle Boot  |

You can download it here -- https://github.com/zalandoresearch/fashion-mnist

# Models:
1. 2 Layer feedforward Nerual Netwrok
2. CNN (1 Conv layer)
3. CNN (3 Conv layer)
4. CNN (4 Conv layer) + Batch Normalization
5. VGG
6. VGG + Batch Normalization

# Results
Out of all experiments, model with VGG + Batch Normalization performed the best with almost 95% accuracy.

| Model | Accuracy |
| :---: |   :---:   |
| 2 Layer Nerual Netwrok |    88%   |
| CNN (1 Conv layer) | 91%  |
| CNN (3 Conv layer) | 91%  |
| CNN (4 Conv layer) + Batch Normalization | 92%   |
|  VGG     | 93%  |
| VGG + Batch Normalization| 95%  |


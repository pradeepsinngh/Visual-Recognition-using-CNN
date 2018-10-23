# Image Classification using CNN models:
Classification of Fashion products using different neural network based models -- Feedforward, CNN and VGG, etc.


## Data
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. 
You can download it here -- https://github.com/zalandoresearch/fashion-mnist


| Target Class  |   Definition  |
|     :---:     |     :---:     |
|       0       | T-shirt  |
|       1       | Trouser  |
|       2       | Pullover |
|       3       | Dress |
|       4       | Coat  |
|       5       | Sandal |
|       6       | Shirt  |
|       7       | Sneaker |
|       8       | Bag |
|       9       | Ankle Boot |


## Models:
1. 2 Layer feedforward Nerual Netwrok
2. CNN (1 Conv layer)
3. CNN (3 Conv layer)
4. CNN (4 Conv layer) + Batch Normalization
5. VGG
6. VGG + Batch Normalization

## Data Augmentation:
Since, my data set only had 60,000 test cases, which is quite less for a deep learning model (for eg: VGG). So, I have used data (image) augmentation technique to increase the number of images and also to improve the quality of images. 

## Overfitting and Underfitting:
- Dropout
- Data Augmentation

## Results
Out of all experiments, model with VGG + Batch Normalization performed the best with almost 95% accuracy.

| Model | Accuracy |
| :---: |   :---:   |
| 2 Layer Nerual Netwrok |    88%   |
| CNN (1 Conv layer) | 91%  |
| CNN (3 Conv layer) | 91%  |
| CNN (4 Conv layer) + Batch Normalization | 92%   |
|  VGG     | 93%  |
| VGG + Batch Normalization| 94%  |


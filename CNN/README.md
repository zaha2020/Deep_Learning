# Classifying images using Convolutional Neural Networks

## Decription:
In this project, We investigate several configurations of CNNs to classify input images.

## Dataset
For this task, we've used [`Fashion MNSIT`](https://github.com/zalandoresearch/fashion-mnist) which contains 10 classes of data for a classification task.

## Training
We've trained Network with several Configurations to find the best setting for our task. We have checked for these settings:  
- MLP with a different number of hidden layers
- MLP with different Activation functions
- Convolutional Neural Networks
- Convolutional Neural Networks with DropOut
- Convolutional Neural Networks with DropOut and Batch normalization

## Results
Accuracy for different settings mentioned above are in  the below table:

| Model      | Accuracy% |
| ----------- | ----------- |
| CNN + fully connected     | 90,63       |
| CNN + fully connected + Pooling + Batch normalization   | 90,17        |
| CNN + fully connected + Pooling + CNN_Dropout(0.3,0.3,0.5) | 90,56        |
|CNN + fully connected + Pooling + CNN_Dropout(0.2,0.2,0.2)   | 90,89        |
| CNN + fully connected + Pooling + Batchnormalization + CNN_Dropout(0.2,0.2,0.2)   | 91,04        |

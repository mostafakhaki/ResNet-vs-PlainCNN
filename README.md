# ResNet (with skip connections) vs Plain CNN (without skip connections): Training and Performance Comparison on CIFAR-100
This repository contains the code and experiments for three projects that explore the comparison between ResNet50 and a plain CNN (a similar network without skip connections) on image classification tasks. The models are trained from scratch using TensorFlow and Keras. The focus of this repository is to show the impact of residual connections on model performance, particularly on the CIFAR-100 dataset.

## Projects in this Repository
### 1. ResNet-Cifar10: Training ResNet50 from Scratch on CIFAR-10
This project trains ResNet50 on the CIFAR-10 dataset from scratch, demonstrating how the model benefits from residual connections.

### 2. ResNet - Fine Tuning - Cifar100 on ImageNet weights
This project trains a plain CNN (without skip connections) on the CIFAR-10 dataset, providing a baseline to compare with ResNet50.

### 3. Training ResNet50 vs. Plain CNN on CIFAR-100
This project compares the performance of ResNet50 and a plain CNN on the more challenging CIFAR-100 dataset, focusing on training dynamics, convergence speed, and overall accuracy. The comparison includes a plot showing the training differences.

## Objectives:
* ResNet50 Training: Demonstrate the advantages of residual connections by training ResNet50 on CIFAR-10 and CIFAR-100.
* Plain CNN Training: Establish a baseline by training a similar CNN without residual blocks on CIFAR-10 and CIFAR-100.
* Comparison: Visualize the differences in training speed and accuracy between ResNet50 and the plain CNN on CIFAR-100.

## Results:
CIFAR-100: While ResNet50 generally shows better training stability and faster convergence, both models did not achieve high performance on the validation set. The focus of the experiment was on the training process rather than validation accuracy.
![Training ResNet50 vs. Plain CNN on CIFAR-100](https://github.com/mostafakhaki/ResNet-vs-PlainCNN/blob/main/Model%20Accuracy%20-%20ResNet.png?raw=true)

## Notes:
The models' validation set accuracy was not optimized as part of this project. To improve generalization and validation performance, you may consider:
* Regularization techniques like L2 regularization or dropout.
* Data augmentation methods such as random cropping, flipping, and rotation.
  
## Requirements:
* Python 3.x
* TensorFlow 2.x
* Keras
* CIFAR-100 Dataset

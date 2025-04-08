# 🧠 #CIFAR100 #CNN #Experiments

This project focuses on #imageclassification using a custom #ConvolutionalNeuralNetwork (#CNN) trained on a reduced subset of the [CIFAR-100 dataset](https://www.cs.toronto.edu/~kriz/cifar.html). The aim is to analyze the impact of architectural and training variations on classification performance, all within the limitations of a free #GoogleColab environment.

## 📌 #ProjectGoals

- Build a CNN from scratch using #TensorFlow and #Keras
- Use a subset of CIFAR-100 (#8to12 classes with reduced samples per class)
- Evaluate and improve classification accuracy through systematic experimentation

## ⚙️ #KeyFeatures

- 🔹 #DataPreprocessing and subset extraction from CIFAR-100
- 🔹 Custom CNN architecture with convolutional, max-pooling, and dense layers
- 🔹 #Experiments with CNN depth, #activationfunctions, #optimizers, batch sizes, and more
- 🔹 Evaluation of #modelperformance on the CIFAR-100 test set

## 🔬 #Experiments

- Test the effect of increasing/decreasing CNN layers
- Experiment with #activationfunctions like #ReLU, #Sigmoid, and #Softmax
- Try different #optimizers and learning rates
- Evaluate the effect of batch sizes and epochs on training and accuracy

## 🗂️ #Files

- `cnn_cifar100.ipynb`: Main #Colab notebook with code and experiments

## 🔧 #TechStack

- #TensorFlow / #Keras
- #Python (#Jupyter / #Colab)
- #CIFAR100Dataset (subset)
- #ImageNetDataset (subset)

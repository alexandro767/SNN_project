# Spiking Neural Networks for Computer Vision

## Introduction

Spiking neural networks (SNNs) are a type of artificial neural network that uses spiking neurons to process information. Spiking neurons are more biologically realistic than traditional artificial neurons, and they can be used to implement a wide variety of complex computations.

SNNs have shown great promise for a variety of computer vision tasks, including image classification, object detection, and scene understanding. This is because SNNs are able to process information in a more efficient and event-driven manner than traditional artificial neural networks.

## Project Goals

The goal of this project is to develop a set of SNN models for computer vision tasks. These models will be implemented in PyTorch and SNNTorch and will be trained on a variety of datasets.

## Challenges

Spiking Neural Networks operate with discontinuous outputs, so we smooth Heaviside functions by using sigmoid functions.

## Datasets

The following datasets are used to train and evaluate the SNN models:

- CIFAR-10
- MNIST

## Models

The following SNN models are implemented:

- [SNNVGG](https://github.com/alexandro767/SNN_project/blob/main/SNN_VGG_2.ipynb)
- [SNNMLP](path/to/SNNMLP.py)

## Evaluation

The SNN models will be evaluated on the following metrics:

- Accuracy

## Results

The table below shows the accuracy for each model on the CIFAR-10 and MNIST datasets.

| Model   | Dataset | Accuracy |
|---------|--------------------|----------------|
| [SNNMLP](path/to/SNNMLP.py) | MNIST            | 90%            |
| [SNNVGG(1)](https://github.com/alexandro767/SNN_project/blob/main/SNN_VGG_like.ipynb) | CIFAR-10            | 60.42%            |
| [SNNVGG(2)](https://github.com/alexandro767/SNN_project/blob/main/SNN_VGG_2.ipynb) | CIFAR-10            | 57.26%            |

---

Replace `path/to/SNNVGG.py` and `path/to/SNNMLP.py` with the actual paths to your model files. Adjust the accuracy values as per your evaluation results.

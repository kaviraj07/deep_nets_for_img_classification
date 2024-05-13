# Deeper Networks for Image Classification

- Code by Kaviraj Gosaye QMUL
- Student ID: 220575371

## Description :scroll:
This repository is an analysis of Convolutional Neural Networks (CNNs) on two popular datasets to measure performance of deep networks for image classification tasks. All four models are trained on MNIST and further analysis for CIFAR10 is done using only ResNet50 and MobileNetV2.

## Models :rocket:
- InceptionV3
- VGG16
- ResNet50
- MobileNetV2

## Datasets :books:
- MNIST
- CIFAR10

## Tech and Version :hammer_and_wrench:
- Python 3.12.1
- PyTorch 2.2.0
- Matplotlib 3.8.2
- Torchinfo 1.8.0


## Results :chart_with_upwards_trend:

### MNIST

| Model       | Size (MB)   | Trainable parameters | Train Loss (4 s.f.) | Test Loss (4 s.f.) | Train Accuracy (4 s.f.) | Test Accuracy (4 s.f.) | Precision | Recall |
|-------------|----------|----------------------|---------------------|--------------------|-------------------------|------------------------|-----------|--------|
| **VGG-16**  | 549.95| 134,308,810          | 0.01964             | 0.03202            | 99.47                   | 98.93                  | 0.99      | 0.99   |
| **Inception V3** | 92.32 | 21,805,226           | 0.02872             | 0.02745            | 99.20                   | 98.53                  | 0.99      | 0.99   |
| **ResNet50** | 105.99| 23,519,690            | 0.01447             | 0.03467            | 99.58                   | 98.61                  | 0.99      | 0.99   |
| **MobileNetV2** | 9.11 | 1,814,346             | 0.04369             | 0.09918            | 98.61                   | 94.06                  | 0.94      | 0.94   |


### CIFAR10
| Model       | Size (MB)    | Trainable parameters | Train Loss (4 s.f.) | Test Loss (4 s.f.) | Train Accuracy (4 s.f.) | Test Accuracy (4 s.f.) | Precision | Recall |
|-------------|----------|----------------------|---------------------|--------------------|-------------------------|------------------------|-----------|--------|
| **ResNet50** | 108.61| 23,520,842            | 0.02102             | 1.184              | 99.27                   | 73.58                  | 0.74      | 0.74   |
| **MobileNetV2** | 73.96 | 1,814,922             | 0.04439             | 1.318              | 98.42                   | 72.30                  | 0.72      | 0.72   |

# hnn-classification

## About
The repository of my undergraduate thesis titled "Comparative Study between Hierarchical Neural Network and Single Convolutional Neural Network for Image Classification with Hierarchical Data". This repository contains source code for both HNN and single CNN implementations.

## Goal
This research was performed in order to:
1. To compare accuracy, F1-score, execution time, and memory usage between HNN and single CNN models on CIFAR-100 dataset subset

## Research flow
This research was performed according to these steps:
1. Literature study
2. Dataset selection
3. Data preparation
4. Data preprocessing
5. Modeling
6. Evaluation

## Results
The results of our research can be seen in these tables:

**Accuracy and F1-score :**
|                             | **Accuracy** | **F1-score** |
|-----------------------------|-------|--------|
| **Single CNN** | 52.25% | 0.5185  |
| **HNN**         | 52.08% | 0.5173  |

**Execution time and memory usage :**
|                             | **Execution time (per-image)** | **Memory usage (in MiB)** |
|-----------------------------|-------|--------|
| **Single CNN** | 0.10520 s | 1027.5664  |
| **HNN**         | 0.23508 s | 4994.7265  |

Based on these results, we can conclude that the differences of classification performance between single CNN and HNN models are not very significant, with the results slightly favor that of single CNN model. For both models, the Top-1 Accuracy score tops out at around 52%. 

## Limitations and Suggestions
We suspect that the relatively small size of images and also that the amount of images for each classes is relatively few might contribute to the low classification performance. For further developments, it is suggested to increase the number of images by combining this dataset with other relevant datasets. 

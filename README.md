# 🐶 Dog Breed Image Classification

## Overview
A **multi-class image classification project** that predicts a dog’s breed from an image using **transfer learning** with a pre-trained **ResNet34** model and the `fastai` library.

The project focuses on **fine-grained visual classification**, where some classes share very similar visual features.

---

## Problem
- **Task**: Image classification
- **Classes**:
  - Beagle  
  - Doberman  
  - Golden Retriever  
  - Labrador Retriever  
  - Shih-Tzu
- **Challenge**: High visual similarity between certain breeds and large intra-class variation

---

## Dataset
- **Source**: Stanford Dogs Dataset
- **Total size**: 750 images (150 per breed)
- **Split**:
  - Train set: 600 images
  - Validation set: 150 images
- Balanced and manually organized dataset

---

## Model
- **Framework**: fastai (PyTorch)
- **Architecture**: ResNet34 (pre-trained)
- **Approach**: Transfer Learning using `vision_learner` and `fine_tune`

---

## Results
- **Validation Accuracy**: **96.66%**
- Strong performance across all classes
- Most confusion occurred between visually similar retriever breeds

---

## Key Learnings
- Transfer learning enables high accuracy even with limited data
- Dataset quality and class similarity significantly affect model performance
- Fine-grained classification requires careful feature understanding

---

## Tech Stack
Python · fastai · PyTorch · Jupyter Notebook · CNNs

---

**Author**: Tair Saida  
Deep Learning Project – 2025

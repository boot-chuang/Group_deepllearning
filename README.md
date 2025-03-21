# Emotion Recognition Through Multimodal Feature Fusion with Transformer Networks

[![GitHub stars](https://img.shields.io/github/stars/yangchuang/Emotion-Recognition-Through-Multimodal-Feature-Fusion.svg?style=social&label=Stars)](https://github.com/yangchuang/Emotion-Recognition-Through-Multimodal-Feature-Fusion)
[![GitHub forks](https://img.shields.io/github/forks/yangchuang/Emotion-Recognition-Through-Multimodal-Feature-Fusion.svg?style=social&label=Fork)](https://github.com/yangchuang/Emotion-Recognition-Through-Multimodal-Feature-Fusion/fork)

This repository contains the implementation of a multi-modal emotion recognition system that combines audio features (Action Units - AU and Mel-Frequency Cepstral Coefficients - MFCCs) for improved emotion classification using Transformer networks.
![Model Architecture](model.png)

## Introduction

The ability to recognize emotions from speech signals has emerged as a pivotal technology in affective computing, with applications ranging from mental health diagnostics to intelligent voice assistants. This project addresses the challenges of temporal dependency, modality alignment, and data sparsity through an innovative architectural design and optimization strategies.

## System Overview

The proposed system processes AU and MFCC features through dedicated transformer streams, fuses them through attention-guided gates, and outputs emotion probabilities across 8 classes (neutral, happy, sad, angry, etc.).

## Key Features

- **Transformer Architecture**: Utilizes the Transformer model to capture temporal patterns in audio features.
- **Multi-Modal Fusion**: Combines AU and MFCC features for improved emotion classification.
- **FocalLoss**: Employs FocalLoss to handle class imbalances and improve model generalization.
- **Real-Time Inference**: Optimizes the system for real-time performance through model quantization.

## Performance Visualization

The system's performance is demonstrated through various visualizations, including training and validation loss and accuracy comparisons, and test accuracy comparison.

## Dataset

The system was trained and evaluated on a dataset containing audio recordings labeled with eight distinct emotions. The dataset includes both AU and MFCC features, providing a comprehensive resource for training and evaluating speech-based emotion recognition systems.

## Conclusion

The developed system represents a significant advancement in speech-based emotion recognition, offering a robust and accurate solution for multi-modal emotion analysis. Future work will focus on enhancing system performance through sophisticated fusion mechanisms, exploring additional modalities, and improving robustness to noisy or incomplete data.

## Limitations and Future Work

- Limited to audio features; future work could integrate visual or physiological signals.
- Relies on pre-extracted features; end-to-end training might capture more relevant patterns.
- Performance could be further enhanced with more sophisticated fusion mechanisms.

## References

- Cummins, N., et al. (2021). AI-based mental health monitoring from speech. NPJ Digital Medicine.
- Poria, S., et al. (2017). Context-dependent sentiment analysis in user-generated videos. ACL.
- Zhang, Y., et al. (2022). Facial-vocal emotion fusion via deep metric learning. IEEE TMM.
- Chen, M., et al. (2020). Multimodal emotion recognition with transformer-based self-supervised feature learning. IEEE TAC.
- Tsai, Y.H.H., et al. (2019). Multimodal transformer for unaligned multimodal language sequences. ACL.



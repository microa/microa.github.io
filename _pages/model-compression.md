---
permalink: /model-compression/
title: "Model Compression"
excerpt: "Model compression research and publications"
author_profile: false
---

# Model Compression

This page showcases my research in model compression, focusing on efficient neural network architectures and optimization techniques. My work spans from decentralized signal classification to advanced pruning methods and efficient vision transformers.

## Research Overview

Model compression is crucial for deploying deep learning models on resource-constrained devices. My research focuses on three key areas:

1. **Decentralized Classification**: Using early exit mechanisms for efficient distributed inference
2. **Structural Pruning**: Advanced pruning techniques for optimal brain connections
3. **Efficient Vision Transformers**: Token dropping and optimization for vision models

## Publications

### 1. DCentNet: Decentralized multistage biomedical signal classification using early exits

**Authors**: Xiaolin Li, **Binhua Huang**, Barry Cardiff, Deepu John  
**Journal**: Biomedical Signal Processing and Control, Volume 104, 2025  
**DOI**: [10.1016/j.bspc.2024.107468](https://doi.org/10.1016/j.bspc.2024.107468)

**Abstract**: This work presents DCentNet, a novel approach for decentralized biomedical signal classification using early exit mechanisms. The method enables efficient distributed inference across multiple devices while maintaining high accuracy.

**Key Contributions**:
- Decentralized multistage classification framework
- Early exit mechanisms for computational efficiency
- Real-time biomedical signal processing
- Embedded system deployment

**Code Repository**: [DCentNet GitHub Repository](https://github.com/microa/DSCEE)

### 2. Optimal Brain Connection: Towards Efficient Structural Pruning

**Authors**: S. Chen, W. Ma, **Binhua Huang**, Q. Wang, G. Wang, W. Sun, L. Huang, D. John  
**Journal**: arXiv preprint, 2025  
**arXiv**: [2508.05521](https://arxiv.org/abs/2508.05521)

**Abstract**: This paper introduces a novel structural pruning method that identifies optimal brain connections in neural networks. The approach achieves significant model compression while preserving performance.

**Key Contributions**:
- Advanced structural pruning techniques
- Optimal connection identification
- Performance-preserving compression
- Comprehensive evaluation on multiple datasets

### 3. TinyDrop: Tiny Model Guided Token Dropping for Vision Transformers

**Authors**: Guoxin Wang, Qingyuan Wang, **Binhua Huang**, Shaowu Chen, Deepu John  
**Journal**: arXiv preprint, 2025  
**arXiv**: [2509.03379](https://arxiv.org/abs/2509.03379)

**Abstract**: TinyDrop presents a training-free token dropping framework for Vision Transformers, guided by lightweight vision models. The method reduces computational costs while maintaining accuracy.

**Key Contributions**:
- Training-free token dropping framework
- Lightweight guidance model integration
- Significant FLOPs reduction (up to 80%)
- Plug-and-play compatibility with diverse ViT architectures

## Implementation Details

### DCentNet Implementation

The DCentNet repository contains comprehensive implementation including:

#### Experimental Code
- **Inference and Sender (BLE)**: Deep sleep mode, inference mode, connected mode, and broadcast mode implementations
- **Receiver (BLE)**: Connected and broadcast mode receivers
- **Embedded System Deployment**: Arduino IDE integration with trained models

#### Training Code
- **Edge Impulse Integration**: Simple training notebook with API key support
- **Customizable Networks**: Flexible architecture for different use cases
- **Multiple Model Variants**: 2-5 layer CNN architectures

#### Deployment Guide
1. Launch Arduino IDE (Version 2.3.3)
2. Add trained model library
3. Install ArduinoBLE library (Version 1.3.7)
4. Include inference file in your code

### Model Variants Available
- EEPS-2LayerCNN.zip
- EEPS-3LayerCNN.zip
- EEPS-4LayerCNN.zip
- EEPS-5LayerCNN.zip
- 2Layerswith96%Acc.zip

## Research Impact

These works contribute to the field of model compression through:

1. **Practical Deployment**: DCentNet provides real-world embedded system solutions
2. **Theoretical Advances**: Optimal Brain Connection offers novel pruning methodologies
3. **Efficiency Gains**: TinyDrop demonstrates significant computational savings

## Future Directions

- Integration of early exit mechanisms with advanced pruning techniques
- Cross-domain application of token dropping methods
- Real-time optimization for edge computing scenarios

---

*This page summarizes my contributions to model compression research, spanning from practical embedded implementations to theoretical advances in neural network optimization.*

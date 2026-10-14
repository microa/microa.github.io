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
**Journal**: Biomedical Signal Processing and Control, Volume 104, Article 107468, 2025  
**DOI**: [10.1016/j.bspc.2024.107468](https://doi.org/10.1016/j.bspc.2024.107468)

**Summary**: This work presents DCentNet, a novel approach for decentralized biomedical signal classification using early exit mechanisms. The method enables efficient distributed inference across multiple devices while maintaining high accuracy.

**Key Contributions**:
- Decentralized multistage classification framework
- Early exit mechanisms for computational efficiency
- Real-time biomedical signal processing
- Embedded system deployment

**Code Repository**: [DCentNet GitHub Repository](https://github.com/microa/DCentNet)

### 2. Optimal Brain Connection: Towards Efficient Structural Pruning

**Authors**: Shaowu Chen, Wei Ma, **Binhua Huang**, Qingyuan Wang, Guoxin Wang, Weize Sun, Lei Huang, Deepu John  
**Journal**: IEEE Transactions on Multimedia, 2026  
**DOI**: [10.1109/TMM.2026.3732964](https://doi.org/10.1109/TMM.2026.3732964)  
**arXiv**: [2508.05521](https://arxiv.org/abs/2508.05521)  
**Code**: [Optimal Brain Connection GitHub Repository](https://github.com/ShaowuChen/Optimal_Brain_Connection)

**Summary**: Optimal Brain Connection evaluates structural parameter importance while accounting for interactions within components and dependencies across layers. Its Jacobian Criterion guides pruning, while an autoencoder-based Equivalent Pruning mechanism preserves the contributions of original connections during fine-tuning.

**Key Contributions**:
- Jacobian Criterion for interaction-aware structural importance estimation
- Equivalent Pruning with autoencoders to reduce performance loss during fine-tuning
- Evaluation across CNNs, Vision Transformers, and multimodal models

### 3. TinyDrop: Tiny Model Guided Token Dropping for Vision Transformers

**Authors**: Guoxin Wang, Qingyuan Wang, **Binhua Huang**, Shaowu Chen, Deepu John  
**Conference**: IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2026  
**DOI**: [10.1109/ICASSP55912.2026.11464424](https://doi.org/10.1109/ICASSP55912.2026.11464424)  
**arXiv**: [2509.03379](https://arxiv.org/abs/2509.03379)

**Summary**: TinyDrop presents a training-free token dropping framework for Vision Transformers, guided by lightweight vision models. The method reduces computational costs while maintaining accuracy.

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
The original experiments used Arduino IDE **2.3.3** and ArduinoBLE **1.3.7**. See the [repository deployment guide](https://github.com/microa/DCentNet#deploy-in-embedded-system) for the setup and trained-model downloads.

1. Launch Arduino IDE.
2. Add the trained model ZIP via **Sketch → Include Library → Add .ZIP Library**.
3. Install ArduinoBLE through the Library Manager.
4. Include the inference file from the repository.

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

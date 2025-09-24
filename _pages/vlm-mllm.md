---
permalink: /vlm-mllm/
title: "VLM, MLLM, World Models"
excerpt: "Vision-Language Models, Multimodal Large Language Models, and World Models research"
author_profile: false
---

# VLM, MLLM, World Models

This page showcases my research in Vision-Language Models (VLM), Multimodal Large Language Models (MLLM), and World Models. My work focuses on integrating large-scale vision-language models with efficient video understanding and temporal reasoning.

## Research Overview

Vision-Language Models and Multimodal Large Language Models represent the frontier of AI research, combining visual and linguistic understanding. My research in this area focuses on:

1. **CLIP Integration**: Leveraging large-scale vision-language models for video understanding
2. **Efficient Fusion**: Combining frozen vision-language models with temporal information
3. **Zero-Shot Capabilities**: Training-free approaches for video recognition tasks

## Publications

### MoCLIP-Lite: Efficient Video Recognition by Fusing CLIP with Motion Vectors

**Authors**: **Binhua Huang**, Nan Wang, Arjun Parakash, Soumyabrata Dev  
**Journal**: arXiv preprint, 2025  
**arXiv**: [2509.17084](https://arxiv.org/abs/2509.17084)  
**Code**: [GitHub Repository](https://github.com/microa/MoCLIP-Lite)

**Abstract**: Video action recognition is a fundamental task in computer vision, but state-of-the-art models are often computationally expensive and rely on extensive video pre-training. In parallel, large-scale vision-language models like Contrastive Language-Image Pre-training (CLIP) offer powerful zero-shot capabilities on static images, while motion vectors (MV) provide highly efficient temporal information directly from compressed video streams. To synergize the strengths of these paradigms, we propose MoCLIP-Lite, a simple yet powerful two-stream late fusion framework for efficient video recognition.

**Key Contributions**:
- **CLIP Integration**: Effective fusion of frozen CLIP image encoder with temporal information
- **Two-Stream Architecture**: Late fusion framework combining vision-language and motion features
- **Zero-Shot Capabilities**: Leveraging CLIP's powerful zero-shot capabilities for video understanding
- **Efficient Design**: Frozen backbone approach ensuring extreme efficiency
- **Performance**: 89.2% Top-1 accuracy on UCF101 dataset

**Technical Details**:
- **Frozen CLIP Encoder**: Utilizes pre-trained CLIP image encoder without fine-tuning
- **Motion Vector Integration**: Incorporates compressed-domain motion information
- **Lightweight Fusion**: Only tiny Multi-Layer Perceptron (MLP) head is trained
- **Late Fusion Strategy**: Combines features from both modalities at the final stage
- **Significant Improvements**: Outperforms zero-shot (65.0%) and MV-only (66.5%) baselines

**Vision-Language Model Aspects**:
- **Large-Scale Model Utilization**: Effective use of pre-trained CLIP models
- **Multimodal Understanding**: Integration of visual and temporal information
- **Zero-Shot Transfer**: Leveraging CLIP's zero-shot capabilities for video tasks
- **Frozen Backbone Efficiency**: Maintaining efficiency while utilizing large models

## Research Impact

This work contributes to the VLM/MLLM field through:

1. **Efficient Integration**: Novel approach to combining large vision-language models with video understanding
2. **Zero-Shot Capabilities**: Demonstrates effective zero-shot transfer from image to video domains
3. **Computational Efficiency**: Maintains efficiency while utilizing large-scale models
4. **Practical Deployment**: Provides practical solutions for video understanding tasks

## Technical Innovations

### CLIP-Video Fusion
- **Frozen Encoder Utilization**: Effective use of pre-trained CLIP without fine-tuning
- **Temporal Integration**: Combining static image understanding with motion information
- **Late Fusion Strategy**: Optimal combination of visual and temporal features

### Zero-Shot Video Understanding
- **Domain Transfer**: From image understanding to video recognition
- **Training-Free Approach**: No additional training required for video tasks
- **Performance Preservation**: Maintaining accuracy while reducing computational costs

### Efficient Architecture
- **Frozen Backbone Design**: Minimal training requirements
- **Motion Vector Integration**: Leveraging compressed-domain information
- **Scalable Framework**: Applicable to various video understanding tasks

## Future Directions

- **Advanced VLM Integration**: Exploring newer vision-language models for video understanding
- **Multimodal Fusion**: Advanced fusion strategies for vision-language-video tasks
- **World Model Applications**: Extending to world model and temporal reasoning tasks
- **Cross-Modal Learning**: Enhanced cross-modal understanding capabilities

## Related Research Areas

### Vision-Language Models
- Large-scale pre-trained models for visual understanding
- Zero-shot capabilities for various vision tasks
- Multimodal representation learning

### Multimodal Large Language Models
- Integration of visual and linguistic understanding
- Cross-modal reasoning capabilities
- Efficient deployment strategies

### World Models
- Temporal reasoning and prediction
- Video understanding and analysis
- Sequential decision making

---

*This page summarizes my contributions to Vision-Language Models, Multimodal Large Language Models, and World Models research, focusing on efficient integration of large-scale models with video understanding tasks.*

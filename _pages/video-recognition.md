---
permalink: /video-recognition/
title: "Video Recognition"
excerpt: "Video recognition research and publications"
author_profile: false
---

# Video Recognition

This page showcases my research in video recognition, focusing on efficient video understanding through motion vectors, CLIP integration, and advanced cropping techniques. My work addresses the computational challenges in video analysis while maintaining high accuracy.

## Research Overview

Video recognition is a fundamental task in computer vision, but state-of-the-art models are often computationally expensive. My research focuses on three key approaches:

1. **Motion Vector Integration**: Leveraging compressed-domain motion information for efficient video understanding
2. **CLIP-Video Fusion**: Combining large-scale vision-language models with temporal information
3. **Zero-Shot Detection**: Training-free methods for video object detection and action recognition

## Publications

### 1. MoCLIP-Lite: Efficient Video Recognition by Fusing CLIP with Motion Vectors

**Authors**: **Binhua Huang**, Nan Wang, Arjun Parakash, Soumyabrata Dev  
**Journal**: arXiv preprint, 2025  
**arXiv**: [2509.17084](https://arxiv.org/abs/2509.17084)  
**Code**: [GitHub Repository](https://github.com/microa/MoCLIP-Lite)

**Abstract**: Video action recognition is a fundamental task in computer vision, but state-of-the-art models are often computationally expensive and rely on extensive video pre-training. In parallel, large-scale vision-language models like Contrastive Language-Image Pre-training (CLIP) offer powerful zero-shot capabilities on static images, while motion vectors (MV) provide highly efficient temporal information directly from compressed video streams. To synergize the strengths of these paradigms, we propose MoCLIP-Lite, a simple yet powerful two-stream late fusion framework for efficient video recognition.

**Key Contributions**:
- Two-stream late fusion framework combining CLIP with motion vectors
- Frozen backbone approach ensuring extreme efficiency
- 89.2% Top-1 accuracy on UCF101 dataset
- Significant performance improvement over zero-shot (65.0%) and MV-only (66.5%) baselines

**Technical Details**:
- Combines features from frozen CLIP image encoder
- Lightweight supervised network trained on raw motion vectors
- Only tiny Multi-Layer Perceptron (MLP) head is trained during fusion
- Provides highly efficient baseline for video understanding

### 2. MVP: Motion Vector Propagation for Zero-Shot Video Object Detection

**Authors**: **Binhua Huang**, Ni Wang, Wendong Yao, Soumyabrata Dev  
**Journal**: arXiv preprint, 2025  
**arXiv**: [2509.18388](https://arxiv.org/abs/2509.18388)  
**Code**: [GitHub Repository](https://github.com/microa/MVP)

**Abstract**: Running a large open-vocabulary (Open-vocab) detector on every video frame is accurate but expensive. We introduce a training-free pipeline that invokes OWLv2 only on fixed-interval keyframes and propagates detections to intermediate frames using compressed-domain motion vectors (MV). A simple 3x3 grid aggregation of motion vectors provides translation and uniform-scale updates, augmented with an area-growth check and an optional single-class switch.

**Key Contributions**:
- Training-free pipeline for zero-shot video object detection
- Motion vector propagation from keyframes to intermediate frames
- 3x3 grid aggregation for translation and scale updates
- mAP@0.5=0.609 and mAP@[0.5:0.95]=0.316 on ILSVRC2015-VID
- Outperforms tracker-based propagation methods

**Technical Details**:
- Invokes OWLv2 only on fixed-interval keyframes
- Uses compressed-domain motion vectors for propagation
- Area-growth check and single-class switch mechanisms
- No labels, no fine-tuning required
- Compatible with all open-vocabulary methods

### 3. MoCrop: Training Free Motion Guided Cropping for Efficient Video Action Recognition

**Authors**: **Binhua Huang**, Wendong Yao, Shaowu Chen, Guoxin Wang, Qingyuan Wang, Soumyabrata Dev  
**Journal**: arXiv preprint, 2025  
**arXiv**: [2509.18473](https://arxiv.org/abs/2509.18473)  
**Code**: [GitHub Repository](https://github.com/microa/MoCrop)

**Abstract**: This paper presents MoCrop, a motion-aware adaptive cropping module for compressed-domain efficient video action recognition. MoCrop leverages motion vectors in H.264 videos to locate motion-dense regions and applies a single clip-level crop to all I-frames during inference. The module is training-free, adds no parameters, and can be plugged into different backbone networks.

**Key Contributions**:
- Training-free motion guided cropping for video action recognition
- Motion vector utilization for motion-dense region localization
- Single clip-level crop application to all I-frames
- No parameter addition, plug-and-play design
- Significant efficiency improvements in video processing

**Technical Details**:
- Leverages H.264 motion vectors for motion analysis
- Motion-dense region localization
- Single crop application across all I-frames
- Compatible with various backbone networks
- No training required, zero parameter overhead

## Research Impact

These works contribute to efficient video understanding through:

1. **Computational Efficiency**: Significant reduction in computational costs while maintaining accuracy
2. **Training-Free Methods**: Zero-shot and training-free approaches for practical deployment
3. **Motion Vector Utilization**: Effective use of compressed-domain information
4. **Real-World Applications**: Practical solutions for video analysis tasks

## Technical Innovations

### Motion Vector Integration
- Direct utilization of compressed video streams
- Efficient temporal information extraction
- Reduced computational overhead

### CLIP-Video Fusion
- Large-scale vision-language model integration
- Zero-shot capabilities for video understanding
- Frozen backbone efficiency

### Zero-Shot Detection
- Training-free object detection pipelines
- Motion vector propagation mechanisms
- Open-vocabulary compatibility

## Future Directions

- Integration of motion vector methods with advanced vision transformers
- Cross-domain application of cropping techniques
- Real-time optimization for streaming video analysis
- Multi-modal fusion approaches

---

*This page summarizes my contributions to video recognition research, focusing on efficient methods that leverage compressed-domain information and large-scale vision-language models.*

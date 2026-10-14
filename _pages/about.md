---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

{% include ai-introductions.html %}

# 🔥 News {#news}
- *2026.10*: &nbsp;📝 MoCLIP has been accepted at The Visual Computer! Paper coming soon · [[code]](https://github.com/microa/MoCLIP)
- *2026.09*: &nbsp;📝 Optimal Brain Connection, has been accepted at IEEE Transactions on Multimedia and is now available on: [[paper]](https://doi.org/10.1109/TMM.2026.3732964) 
- *2026.07*: &nbsp;📝 EarthCamQA, has been accepted at iEMSs and is now available on: [[paper]](https://soumyabratadev.wordpress.com/wp-content/uploads/2026/07/huang2026earthcamqa.pdf) [[code]](https://github.com/microa/realtime-urban-visual-qa)
- *2026.03*: &nbsp;📝 MoCrop, has been accepted at IEEE IJCNN. [[paper]](https://arxiv.org/abs/2509.18473) [[code]](https://github.com/microa/MoCrop)
- *2026.02*: &nbsp;📝 MoCLIP-Lite, has been accepted at IEEE CISP and is now available on IEEE Xplore: [[paper]](https://doi.org/10.1109/CISP-BMEI68103.2025.11259157) [[code]](https://github.com/microa/MoCLIP-Lite)
- *2026.01*: &nbsp;📝 TinyDrop has been accepted at IEEE ICASSP! [[paper]](https://doi.org/10.1109/ICASSP55912.2026.11464424)
- *2025.10*: &nbsp;🤝 Contributed MV-Only (high-speed mode) to mv-extractor. [[upstream]](https://github.com/LukasBommes/mv-extractor) [[my fork]](https://github.com/microa/hs-mv-extractor) [[PyPI]](https://pypi.org/project/motion-vector-extractor/)
- *2025.09*: &nbsp;📝 Preprinted MVP on arXiv: [[paper]](https://arxiv.org/abs/2509.18388) [[code]](https://github.com/microa/MVP)


# 📝 Latest Publications {#publications} 

**2026**
- **Training-Efficient Video Action Recognition Through Vision-Language Semantic Priors and Compressed-Domain Motion Fusion**  
  **B. Huang**, Z. Cui, W. Yao, Y. Li, and S. Dev  
  The Visual Computer (accepted) · Paper coming soon · [[code]](https://github.com/microa/MoCLIP)  

- **Optimal brain connection: Towards efficient structural pruning**  
  S. Chen, W. Ma, **B. Huang**, Q. Wang, G. Wang, W. Sun, L. Huang, D. John  
  IEEE Transactions on Multimedia [[paper]](https://doi.org/10.1109/TMM.2026.3732964) [[arXiv]](https://arxiv.org/abs/2508.05521) [[code]](https://github.com/ShaowuChen/Optimal_Brain_Connection)   

- **EarthCamQA: An Agentic LLM–VLM Framework for Real-Time Visual Question Answering in Urban Environments**  
  **B. Huang**, W. Yao, Y. Li, D. A. Cabrera, S. Dev  
  iEMSs 2026 [[paper]](https://soumyabratadev.wordpress.com/wp-content/uploads/2026/07/huang2026earthcamqa.pdf) [[code]](https://github.com/microa/realtime-urban-visual-qa)

- **MoCrop: Training Free Motion Guided Cropping for Efficient Video Action Recognition**  
  **B. Huang**, W. Yao, S. Chen, G. Wang, Q. Wang, S. Dev  
  IEEE IJCNN 2026 [[paper]](https://arxiv.org/abs/2509.18473) [[code]](https://github.com/microa/MoCrop)

- **TinyDrop: Tiny Model Guided Token Dropping for Vision Transformers**  
  G. Wang, Q. Wang, **B. Huang**, S. Chen, D. John  
  IEEE ICASSP 2026 [[paper]](https://doi.org/10.1109/ICASSP55912.2026.11464424) [[arXiv]](https://arxiv.org/abs/2509.03379)

**2025**
- **MoCLIP-Lite: Efficient Video Recognition by Fusing CLIP with Motion Vectors**  
  **B. Huang**, N. Wang, A. Pakrashi, S. Dev  
  IEEE CISP 2025 [[paper]](https://doi.org/10.1109/CISP-BMEI68103.2025.11259157) [[code]](https://github.com/microa/MoCLIP-Lite)

- **MVP: Motion Vector Propagation for Zero-Shot Video Object Detection**  
  **B. Huang**, N. Wang, W. Yao, S. Dev  
  arXiv preprint [[paper]](https://arxiv.org/abs/2509.18388) [[code]](https://github.com/microa/MVP)

- **DCentNet: Decentralized multistage biomedical signal classification using early exits**  
  X. Li, **B. Huang**, B. Cardiff, D. John  
  Biomedical Signal Processing and Control [[paper]](https://doi.org/10.1016/j.bspc.2024.107468) [[code]](https://github.com/microa/DCentNet)

**2024**
- **Dynamic liquid volume estimation using optical tactile sensors and spiking neural network**  
  **B. Huang**, S. Fang, M. Yin et al.  
  Springer - Intelligent Service Robotics [[paper]](https://doi.org/10.1007/s11370-023-00488-0)

More papers on <a href='https://scholar.google.com/citations?user=WsVak2gAAAAJ'><img src="https://img.shields.io/badge/Google%20Scholar-grey?style=flat&logo=Google%20Scholar&labelColor=f6f6f6"></a> <a href='https://scholar.google.com/citations?user=WsVak2gAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

# 🧩 Open-Source Projects & Contributions
- **mv-extractor** — Contributor (2025)  
  A fast H.264/MPEG-4 motion-vector extractor with optional RGB decode skipping.  
  • Key: Implemented **Motion-Vectors-Only** / frame-decode skipping mode; docs & tests; acknowledged upstream.  
  • Links: [Upstream](https://github.com/LukasBommes/mv-extractor) · [My fork](https://github.com/microa/hs-mv-extractor) · [PyPI](https://pypi.org/project/motion-vector-extractor/)  
  <a href="https://github.com/LukasBommes/mv-extractor"><img alt="GitHub stars" src="https://img.shields.io/github/stars/LukasBommes/mv-extractor?style=social"></a>
  <a href="https://pypi.org/project/motion-vector-extractor/"><img alt="PyPI" src="https://img.shields.io/pypi/v/motion-vector-extractor"></a>


- **GelPixel** — Tactile Sensing (RCAR 2023)  
  A single-pixel tactile sensor research release, including the dataset, multi-target regression code, Fourier parameters, and sensor-structure comparison notebook.  
  • Links: [Repository](https://github.com/microa/GelPixel) · [Paper](https://ieeexplore.ieee.org/abstract/document/10249300) · [Dataset](https://github.com/microa/GelPixel/blob/main/Data/OUT_FILE_CMB20.csv)  
  <a href="https://github.com/microa/GelPixel"><img alt="GelPixel GitHub stars" src="https://img.shields.io/github/stars/microa/GelPixel?style=social"></a>

- **CNC_5axis** — Motion Control  
  A Python interface for five-axis CNC control over serial communication, supporting distance-based movement, timed movement, direction selection, and speed adjustment.  
  • Links: [Repository](https://github.com/microa/CNC_5axis)  
  <a href="https://github.com/microa/CNC_5axis"><img alt="CNC_5axis GitHub stars" src="https://img.shields.io/github/stars/microa/CNC_5axis?style=social"></a>

- **Cloud IoT System** — Embedded IoT  
  An IoT prototype connecting 8051/STM32 devices through ESP8266 WiFi to TCP cloud services for temperature monitoring, data logging, and remote control; includes firmware and hardware diagrams.  
  • Links: [Repository](https://github.com/microa/Cloud_IoT_System) · [Hardware diagrams](https://github.com/microa/Cloud_IoT_System/tree/main/Diagram)  
  <a href="https://github.com/microa/Cloud_IoT_System"><img alt="Cloud IoT System GitHub stars" src="https://img.shields.io/github/stars/microa/Cloud_IoT_System?style=social"></a>

# 👨‍💻 Service
- Session Chair: IJCNN2026
- Program Committee: AAAI2027, AAAI2026, SWC2026
- Session Assistant: RCAR2023
- Reviewer: IEEE T-PAMI, IEEE T-IP, IEEE T-MM, IEEE T-ASE, IEEE T-IM, AAAI, ACM MM, IEEE ICRA, IEEE ICASSP, IEEE IJCNN, BMVC



# 👨‍💻 Research Focuses
<pre>
 • Video Understanding         (<a href="/video-recognition/">Outputs</a>)       2025 - present
 • Model Compression           (<a href="/model-compression/">Outputs</a>)       2023 - 2025
 • Embodied Intelligence       (<a href="/robotics/">Outputs</a>)       2021 - 2023

</pre>

# 🏃‍♂️ Personal life
- 🏃‍♂️ Completed two marathons (42.195 km)  
<br><br>  

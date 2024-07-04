---
title: "Vessel segmentation with spatio-temporal attention network"
excerpt: "An efficient real-time vessel segmentation algorithm is developed to delineate vessels from bi-modal ultrasound images for diagnosis and management of peripheral vascular disease (PVD) <br/><img src='/images/vesnet_figure.png'>"
collection: portfolio
---

Accurate, real-time segmentation of vessel structures in ultrasound image sequences can aid in the measurement of lumen diameters and assessment of vascular diseases. This, however, remains a challenging task, particularly for extremely small vessels that are difficult to visualize.
We propose to leverage the rich spatiotemporal context available in ultrasound to improve segmentation of small-scale lower-extremity arterial vasculature. We describe efficient deep learning methods that incorporate temporal, spatial, and feature-aware contextual embeddings at multiple resolution scales while jointly utilizing information from B-mode and Color Doppler signals. Evaluating on femoral and tibial artery scans performed on healthy subjects by an expert ultrasonographer, and comparing to consensus expert ground-truth annotations of inner lumen boundaries, we demonstrate real-time segmentation using the contextaware models and show that they significantly outperform comparable baseline approaches.

Publications: [MICCAI-ASMUS21-paper](https://link.springer.com/chapter/10.1007/978-3-030-87583-1_1)
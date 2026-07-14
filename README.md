# FED_FORMER

This repository contains the complete implementation of **FED_FORMER**, a federated hyperspectral image classification framework developed for the **XiongAn hyperspectral dataset**.

The primary implementation is provided in:

## Main Notebook
**last-june-23-3dcnn-attention-scl.ipynb**

This notebook contains the complete end-to-end implementation of the proposed FED_FORMER framework, including:

• XiongAn dataset preprocessing
• False-color image generation
• Ground truth visualization
• Spectral Unmixing
• Adaptive Synthetic Sample Generation (ASSG)
• 3D CNN feature extraction
• Channel Attention
• Spatial Attention
• Transformer Encoder
• Supervised Contrastive Learning
• Classification network
• Training and validation
• Performance evaluation (OA, AA, Kappa)
• Classification maps and visualization

## Novel Contributions

★ Adaptive Synthetic Sample Generation (ASSG) for balancing minority classes while preserving spectral characteristics.

★ Hybrid 3D CNN + Transformer architecture combining local spectral–spatial feature extraction with global contextual modeling.

★ Channel Attention and Spatial Attention modules for enhanced feature representation.

★ Supervised Contrastive Learning to improve discriminative feature embeddings.

★ Personalized Federated Learning framework for privacy-preserving hyperspectral image classification.

## Proposed FED_FORMER Pipeline

1. XiongAn hyperspectral dataset loading
2. Spectral–spatial patch extraction
3. Spectral Unmixing
4. Adaptive Synthetic Sample Generation (ASSG)
5. Hybrid 3D CNN feature extraction
6. Channel Attention
7. Spatial Attention
8. Transformer Encoder
9. Supervised Contrastive Learning
10. Classification Head
11. Federated model training and evaluation

This repository serves as the official implementation of the proposed **FED_FORMER** framework, highlighting the integration of **Adaptive Synthetic Sample Generation**, **Hybrid CNN–Transformer learning**, **Attention mechanisms**, and **Federated Learning** for hyperspectral image classification on the **XiongAn benchmark dataset**.

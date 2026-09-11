# C<sup>2</sup>SFA: Confidence- and Curvature-Guided Spline Feature Augmentation

This repository contains the official PyTorch implementation of the paper:
**"C<sup>2</sup>SFA: Confidence- and Curvature-Guided Spline Feature Augmentation for Single-Source Domain Generalization in Medical Image Segmentation"** .

## 📝 Abstract
Medical image segmentation models often degrade on unseen domains because of differences in imaging modalities, acquisition protocols, and sequences. This work proposes **C<sup>2</sup>SFA**, a framework that jointly expands source variations in image and feature spaces:
* **Confidence-guided spline augmentation (CSA):** Generates global and anatomical region-level views and fuses them using gradient saliency and prediction confidence.
* **Curvature-guided high-order feature adversarial learning (CHFA):** Applies up to third-order Hermite perturbations and derives a complementary curvature-related direction for nonlinear, multidirectional feature exploration.

## 🚀 Environment Setup
```bash
# Example setup commands
conda create -n c2sfa python=3.10
conda activate c2sfa
pip install torch torchvision
pip install -r requirements.txt

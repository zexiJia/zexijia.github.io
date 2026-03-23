---
title:          "GROW: Watermark Generation with Progressive Guidance for Diffusion Models"
date:           2026-06-04 00:01:00 +0800
selected:       false

pub:            "IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)"
pub_date:       "2026"
pub_last:       ' <span class="badge badge-pill badge-publication badge-info">To appear</span>'

abstract: >-
  Digital watermarking is a cornerstone for copyright protection. With the rapid advancement
  of generative models like diffusion models, in-generation and training-free watermarking
  techniques have garnered significant attention for their endogeneity and convenience.
  These methods typically embed a watermark into the initial noise, where watermark
  extraction relies on Denoising Diffusion Implicit Models (DDIM) inversion. However,
  the computationally intensive extraction process severely hinders their path toward
  practical deployment. To overcome this critical bottleneck, we propose GROW, a novel
  training-free paradigm that reframes watermarking from a one-shot “embedding” to a
  progressive “growth”. Specifically, at each denoising step, we compute a loss in the
  frequency domain between the predicted clean latent representations and target watermark
  signals. The gradient of this loss is then used to progressively guide the generation,
  ensuring the watermark is naturally woven into the final image representations. Notably,
  GROW requires no inversion process for extraction, enabling highly efficient watermark
  verification. Comprehensive experiments on multiple datasets show that GROW not only
  achieves superior imperceptibility and robustness but also offers a detection speed
  nearly 100× faster than inversion-based techniques. The code will be made publicly
  available.

cover:          /assets/images/covers/crow.png

authors:
  - "Pengcheng Luo"
  - "Zexi Jia"
  - "Yijia Zhong"
  - "Jinchao Zhang"
  - "Jie Zhou"

links:
  arXiv: https://arxiv.org/search/?query=GROW+Watermark+Progressive+Guidance+Diffusion&searchtype=all&source=header
---

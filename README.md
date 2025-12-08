# Awesome Pixel Diffusion Papers

A curated list of notable papers on pixel-space diffusion models for image and video generation. Papers are sorted by publication year in descending order, focusing on end-to-end pixel diffusion approaches that operate directly in raw pixel space, avoiding latent encodings where possible.

## 2025

- **PixelDiT: Pixel Diffusion Transformers for Image Generation**  
  [arXiv:2511.20645](https://arxiv.org/abs/2511.20645)  
  A fully transformer-based model with dual-level design (patch-level and pixel-level DiTs) for end-to-end pixel-space diffusion, achieving strong FID scores on high-resolution images.

- **Back to Basics: Let Denoising Generative Models Denoise**  
  [arXiv:2511.13720](https://arxiv.org/abs/2511.13720)  
  Proposes "Just image Transformers" (JiT) that directly predict clean images in pixel space, leveraging the manifold assumption for efficient high-dimensional generation without noise prediction.

- **DeCo: Frequency-Decoupled Pixel Diffusion for End-to-End Image Generation**  
  [arXiv:2511.19365](https://arxiv.org/abs/2511.19365)  
  Introduces frequency decoupling to enable stable end-to-end pixel diffusion, addressing VAE limitations for high-fidelity synthesis.

- **DiP: Taming Diffusion Models in Pixel Space**  
  [arXiv:2511.18822](https://arxiv.org/abs/2511.18822)  
  Decouples global structure (via DiT on large patches) and local details (via lightweight head) for efficient pixel-space generation, balancing quality and compute.

- **PixNerd: Pixel Neural Field Diffusion**  
  [arXiv:2507.23268](https://arxiv.org/abs/2507.23268)  
  Combines pixel-space diffusion with neural fields for continuous image representation and generation.

- **Advancing End-to-End Pixel Space Generative Modeling via Self-Supervised Pre-training**  
  [arXiv:2510.12586](https://arxiv.org/abs/2510.12586)  
  A two-stage framework with self-supervised distillation to bridge performance gaps in pixel-space diffusion and consistency models.

- **PixelFlow: Pixel-Space Generative Models with Flow**  
  [arXiv:2504.07963](https://arxiv.org/abs/2504.07963)  
  An end-to-end flow-based framework for direct pixel-space image generation, eliminating VAEs and upsamplers for simplicity and performance.

## 2024

- **Simpler Diffusion (SiD2): 1.5 FID on ImageNet512 with Pixel-Space Diffusion**  
  [arXiv:2410.19324](https://arxiv.org/abs/2410.19324)  
  A scalable recipe for pixel-space diffusion using sigmoid loss-weighting and guidance intervals, achieving SOTA on ImageNet at 512x512 resolution.

- **Novel View Synthesis with Pixel-Space Diffusion Models**  
  [arXiv:2411.07765](https://arxiv.org/abs/2411.07765)  
  Adapts diffusion architectures for end-to-end novel view synthesis directly in pixel space, outperforming prior methods.

- **Edify Image: High-Quality Image Generation with Pixel Space Laplacian Diffusion Models**  
  [arXiv:2411.07126](https://arxiv.org/abs/2411.07126)  
  Cascaded models using Laplacian diffusion for photorealistic, pixel-accurate generation.

- **Pixel-Space Post-Training of Latent Diffusion Models**  
  [arXiv:2409.17565](https://arxiv.org/abs/2409.17565)  
  Adds pixel-space objectives to improve fine-tuning and preference alignment in latent models.

- **Scalable High-Resolution Pixel-Space Image Synthesis with Hourglass Diffusion Transformers**  
  [arXiv:2401.11605](https://arxiv.org/abs/2401.11605)  
  Linear scaling with pixel count via hourglass transformers for high-res training.

- **Snap Video: Scaled Spatiotemporal Transformers for Text-to-Video Synthesis**  
  [arXiv:2402.14797](https://arxiv.org/abs/2402.14797)  
  Extends pixel diffusion to video with scaled spatiotemporal transformers for text-conditioned synthesis.

## 2023 and Earlier

- **Simple Diffusion: End-to-End Diffusion for High Resolution Images**  
  [arXiv:2301.11093](https://arxiv.org/abs/2301.11093)  
  Simplifies high-res diffusion training in pixel space without complex modifiers, achieving SOTA FID on ImageNet.

- **Hierarchical Text-Conditional Image Generation with CLIP Latents** (GLIDE)  
  [arXiv:2204.06125](https://arxiv.org/abs/2204.06125)  
  Two-stage hierarchical model using CLIP latents for text-to-image, influential for later pixel-space extensions.

This list includes the provided papers and expands with recent works from arXiv searches up to December 2025. For updates, check arXiv under "pixel diffusion" or "pixel-space diffusion models." Contributions welcome!

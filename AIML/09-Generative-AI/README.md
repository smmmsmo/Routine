# Generative AI

## Foundations

- Generative versus discriminative modeling
- Explicit and implicit density modeling concepts
- Latent variables, sampling, likelihood, reconstruction, and perceptual quality
- Evaluation challenges: fidelity, diversity, usefulness, bias, and memorization

## Model Families

### Autoencoders

- Encoders, decoders, bottlenecks, reconstruction objectives
- Denoising, sparse, and contractive concepts

### Variational Autoencoders

- Probabilistic encoders and decoders
- Reparameterization trick
- Reconstruction term, KL regularization, and ELBO intuition
- Latent-space interpolation and conditional VAEs

### Generative Adversarial Networks

- Generator and discriminator objectives
- Adversarial training dynamics
- Mode collapse, instability, conditional GANs, and Wasserstein concepts

### Diffusion Models

- Forward noising and learned reverse denoising
- Noise schedules, score intuition, samplers, and conditioning
- Classifier-free guidance and latent diffusion
- Text-to-image systems and controllable generation concepts

### Autoregressive and Multimodal Models

- Token-by-token generation
- Image, audio, and video tokenization concepts
- Contrastive image-text learning
- Captioning, speech models, and multimodal transformers

## Required Builds

1. Denoising autoencoder
2. Variational autoencoder with latent-space visualizations
3. Small GAN experiment with training diagnostics
4. Diffusion notebook or guided-generation workflow
5. Multimodal retrieval or captioning application

## Responsible Evaluation

- Check training-data and licensing constraints.
- Test for memorization and privacy concerns.
- Document model limitations and synthetic-data provenance.
- Evaluate across diverse prompts and populations.
- Use appropriate human review for sensitive applications.

## Mastery Checklist

- [ ] I can compare autoregressive, VAE, GAN, and diffusion approaches.
- [ ] I understand latent variables and the VAE objective intuitively.
- [ ] I can explain adversarial training and mode collapse.
- [ ] I understand the forward and reverse diffusion processes.
- [ ] I can evaluate fidelity and diversity rather than cherry-picking samples.
- [ ] I document responsible-use constraints.

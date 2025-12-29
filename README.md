Title: Attentive-CVAE: Text-to-Face Synthesis
Introduction: This repository contains the official implementation of an Attentive Conditional Variational Autoencoder (CVAE). The model is designed to generate and reconstruct human faces based on specific attributes (e.g., Smiling, Eyeglasses, Hair Color) by integrating a Feature Attention Mechanism and CLIP (Contrastive Language-Image Pre-training) embeddings.

Key Features:

Architecture: CVAE with an integrated Attention layer for better feature selection.

Guidance: Text-based attribute control via 40 CelebA labels.

Evaluation: Latent space visualization using t-SNE.

Platform: Optimized for Google Colab and PyTorch.

Dataset: The model is trained on the CelebA dataset, utilizing 40 binary attributes to condition the generation process.

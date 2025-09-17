# Exploring-the-Effectiveness-of-Lightweight-Vision-Language-Models-for-Deepfake-Image-Detection-
This repository contains the code and experimental framework for deepfake image detection using lightweight Vision-Language Models (VLMs). The models explored include BLIP-2 Mini and MiniGPT, fine-tuned with Low-Rank Adaptation (LoRA) for parameter efficiency. The system was evaluated on three benchmark datasets: FaceForensics++ (FF++), Celeb-DF (v2), and WildDeepfake, achieving competitive accuracy with reduced computational overhead.

Key contributions:

Reproducible preprocessing, training, and evaluation pipeline.

LoRA-based fine-tuning reducing trainable parameters by >90%.

Comparative analysis of lightweight VLMs vs. state-of-the-art baselines.

Integration of efficiency metrics (model size, inference time, GPU memory) alongside accuracy.

Qualitative interpretability via attention maps and caption inspection.

This work demonstrates that efficient and interpretable lightweight VLMs can be deployed for deepfake detection in constrained environments such as mobile apps and real-time moderation systems.

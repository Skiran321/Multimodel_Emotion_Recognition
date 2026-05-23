# Multimodal Emotion Recognition System

## Overview

This project implements a deep learning based Multimodal Emotion Recognition System using both speech and text modalities from the TESS (Toronto Emotional Speech Set) dataset.

The system was designed to analyze emotional patterns from:
- acoustic speech representations
- lexical text representations
- fused multimodal embeddings

Three independent pipelines were implemented and evaluated:
- Speech Emotion Recognition Pipeline
- Text Emotion Recognition Pipeline
- Multimodal Fusion Pipeline

The project also includes:
- classification analysis
- confusion matrix evaluation
- t-SNE embedding visualization
- multimodal representation learning analysis
- model comparison experiments

---

# Dataset

Dataset:
- TESS (Toronto Emotional Speech Set)

Emotion Classes:
- angry
- disgust
- fear
- happy
- neutral
- ps
- sad

Speech samples were processed from `.wav` files, while transcript words were extracted directly from filename annotations.

---

# Project Structure

```bash
# Project Structure

project/
├── models/
│ ├── speech_pipeline/
│ │ ├── speech_emotion_model.ipynb
│ │ ├── speech_emotion_model.keras
│ │ 
│ │
│ ├── text_pipeline/
│ │ ├── text_emotion_model.ipynb
│ │ ├── text_emotion_model.keras
│ │ 
│ │
│ └── fusion_pipeline/
│ ├── multimodal_fusion_model.ipynb
│ ├── fusion_emotion_model.keras
│ 
│
├── Results/
│ ├── plots/
│ ├── tsne_comparison_clusters/
│ └── accuracy_comparison_table/
│
├── README.md
└── requirements.txt

# How to Run the Project


If you want to run the complete multimodal emotion recognition pipeline from the beginning, follow the steps below.

---

### 1. Download the Dataset

Download the TESS (Toronto Emotional Speech Set) dataset and extract the dataset folder.

---

### 2. Configure Dataset Directory

Place the extracted dataset inside the project root directory.

Example structure:

```bash
project/
├── dataset/
├── models/
├── Results/
├── README.md
└── requirements.txt

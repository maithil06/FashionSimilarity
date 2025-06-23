# 👗 FashionSimilarity

An AI-powered fashion similarity engine that helps users find visually similar outfits using state-of-the-art deep learning models. Built to enhance product discovery in fashion e-commerce, styling apps, and trend forecasting platforms.

## 🔍 Overview

This project demonstrates how visual similarity in fashion can be computed using modern vision transformers and deep feature embeddings. Users can upload an image, and the model finds the closest matching styles from a reference collection using image embeddings.

### 🎥 [Demo Video](link-to-demo-if-you-have-one)

## 📂 Project Structure

 ```bash 
📁 FashionSimilarity/
├── features_clip.npy # Embeddings using CLIP
├── features_vit.npy # Embeddings using Vision Transformer
├── features_convnext.npy # Embeddings using ConvNeXt
├── features_efficientnet.npy # Embeddings using EfficientNet
├── zara_features_clip.npy # Zara dataset embeddings (CLIP)
├── zara_features_vit.npy # Zara dataset embeddings (ViT)
├── zara_features_convnext.npy # Zara dataset embeddings (ConvNeXt)
├── zara_features_efficientnet.npy # Zara dataset embeddings (EfficientNet)
├── main-fashion-similarity.ipynb # Inference & similarity search demo
└── training-for-fashion-dataset.ipynb # Feature extraction & embedding generation
```

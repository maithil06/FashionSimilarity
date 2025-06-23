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

## 🛠️ Technologies Used

- **CLIP** by OpenAI  
- **ViT** (Vision Transformer)  
- **EfficientNet**, **ConvNeXt**  
- **FAISS** for fast nearest neighbor search  
- **NumPy**, **Matplotlib**, **Streamlit/Gradio** (optional frontend)  

## ⚙️ How It Works

1. Extract image embeddings from a dataset using CLIP, ViT, EfficientNet, or ConvNeXt.
2. Store these features as `.npy` files.
3. Upload a new query image.
4. Use FAISS to find top K nearest images based on cosine similarity.
5. Display similar outfits.

## 🚀 Use Cases

- Fashion product recommendation engines
- Visual search in e-commerce
- Virtual personal stylists
- Outfit inspiration & trend discovery

## 📦 Getting Started

### Clone the Repo
```bash
git clone https://github.com/maithil06/FashionSimilarity.git
cd FashionSimilarity
```

## Run Notebook
```bash
jupyter notebook main-fashion-similarity.ipynb
```
## 🤝 Contributing
Pull requests are welcome! If you'd like to suggest features or improvements, feel free to open an issue.

## 📄 License
This project is open-source and available under the MIT License.


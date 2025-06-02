# AI Image Caption Recommendation System

This project uses CLIP (Contrastive Language–Image Pre-training) to recommend the most relevant captions for an image based on a predefined caption library.

## 🚀 How It Works

1. Load an image and generate image embeddings using CLIP.
2. Load a set of candidate captions and generate text embeddings.
3. Compare the image and text embeddings using cosine similarity.
4. Return the most similar captions as recommendations.

## 🧰 Requirements

- Python 3.8+
- torch
- transformers
- scikit-learn
- pillow

Install dependencies:

```bash
pip install -r requirements.txt

# Stable Diffusion Text-to-Image Pipeline

A complete Generative AI pipeline for text-to-image generation using Stable Diffusion, including data preprocessing, image generation, evaluation, MLOps experiment tracking, API deployment, and a Streamlit web application.

## Features

- Image preprocessing and cleaning
- Caption preprocessing and normalization
- Flickr30k dataset preparation
- Custom PyTorch Dataset and DataLoader
- CLIP tokenization
- Stable Diffusion v1.5 image generation
- Cross-attention based text conditioning
- Image generation from custom prompts
- CLIP similarity evaluation
- BLEU score evaluation
- METEOR score evaluation
- FID score calculation
- Inception Score calculation
- FastAPI REST API
- Streamlit interactive application
- TensorBoard experiment tracking
- CSV experiment logging
- Model checkpoint saving
- Stable Diffusion fine-tuning pipeline

---

## Tech Stack

- Python
- PyTorch
- Diffusers
- Hugging Face Transformers
- Stable Diffusion v1.5
- CLIP
- TorchVision
- PIL
- NumPy
- Pandas
- Matplotlib
- FastAPI
- Streamlit
- TensorBoard
- NLTK
- Scikit-learn

---

## Project Pipeline

```
Flickr30k Dataset
        │
        ▼
Image Cleaning
Caption Cleaning
        │
        ▼
Preprocessing
        │
        ▼
PyTorch Dataset
        │
        ▼
Stable Diffusion
        │
        ▼
Generated Images
        │
        ├────────► CLIP Similarity
        ├────────► BLEU
        ├────────► METEOR
        ├────────► FID
        └────────► Inception Score
        │
        ▼
FastAPI + Streamlit
        │
        ▼
TensorBoard + CSV Logging
```

---

## Dataset

- Flickr30k

Images are cleaned, resized, normalized, and paired with processed captions before training and evaluation.

---

## Evaluation Metrics

- CLIP Similarity
- BLEU Score
- METEOR Score
- Fréchet Inception Distance (FID)
- Inception Score (IS)

---

## MLOps Features

- TensorBoard logging
- CSV experiment tracking
- Generated image saving
- Model checkpoint saving
- Prompt history
- Experiment metadata

---

## Web Applications

### Streamlit

Interactive interface for generating images from text prompts.

### FastAPI

REST API for image generation and evaluation.

---

## License

This project is intended for educational and research purposes.

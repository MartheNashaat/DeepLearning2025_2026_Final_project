# DeepLearning2025_2026_Final_project
Pixel Art Generation with Diffusion Models

Class-conditional DDPM for generating 16×16 pixel art sprites across 5 categories,
extended with Classifier-Free Guidance (CFG). Includes ablations on sampling steps,
model size, and conditioning, plus a class-conditional GAN as comparison. 

**Course:** DLAI 2025/2026 
**Topic:** Image/Video Generation

## Dataset

[Pixel Art Dataset](https://www.kaggle.com/datasets/ebrahimelgazar/pixel-art) —
89,400 sprites, 5 classes (imbalanced: 6k–35k per class).

## Repository

- `PixelArtGeneration_DiffusionModel.ipynb` — main DDPM pipeline
- `PixelArtGeneration_GAN.ipynb` — class-conditional DCGAN baseline
- `Report.pdf` — full project report

## Authors

Marthe Elgawly — 2170201 
elgawly.2170201@studenti.uniroma1.it

Beyza Nur Elaslan — 2180876
elaslan.2180876@studenti.uniroma1.it

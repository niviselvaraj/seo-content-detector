# SEO Content Quality & Duplicate Detector

## 📘 Project Overview
This project automates SEO content analysis by evaluating webpage quality and detecting duplicate or thin content across URLs. It extracts text directly from webpages, computes readability and engagement metrics, identifies duplicate content using semantic similarity, and classifies pages into quality tiers (Low, Medium, High) using machine learning. The pipeline supports both offline dataset analysis and live URL inspection via a unified Jupyter Notebook.

---

## ⚙️ Setup Instructions
```bash
git clone https://github.com/yourusername/seo-content-detector
cd seo-content-detector
pip install -r requirements.txt
jupyter notebook notebooks/seo_pipeline.ipynb
```

🚀 Quick Start

Load your dataset (e.g., extracted_features.csv) in the notebook.

Run each cell to:

Extract features (word count, sentence count, readability)

Generate embeddings using sentence-transformers

Compute pairwise cosine similarity

Flag thin and duplicate content

Train a content quality classifier

Use the function:

analyze_url("https://example.com/sample-article")


to analyze any webpage and return quality metrics and duplicate matches.

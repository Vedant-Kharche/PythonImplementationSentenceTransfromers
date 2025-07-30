# Sentence Embeddings and Similarity Heatmap

This project uses the `sentence-transformers` library to explore and visualize semantic similarity between sentences using pre-trained transformer models.

## 🔍 What It Does

- Encodes a list of creative sentences into high-dimensional sentence embeddings.
- Computes pairwise **cosine similarity** between embeddings.
- Visualizes the similarity matrix using **Seaborn heatmaps**.
- Compares results from two transformer models:
  - `bert-base-nli-mean-tokens`
  - `all-mpnet-base-v2`

## 🧠 Concepts Used

- **Sentence Embeddings**: Vector representations of sentences.
- **Cosine Similarity**: Metric to compare semantic similarity between vectors.
- **Transformer Models**: Pretrained language models fine-tuned for sentence-level tasks.

## 📦 Dependencies

Install the required libraries with:

```bash
pip install sentence-transformers seaborn matplotlib numpy


# 📌 GloVe Embeddings — Mini Project Summary
In this mini-project, I explored GloVe (Global Vectors for Word Representation) using the glove.6B.200d pre-trained embeddings. My objective was to analyze how semantic relationships between words are preserved when visualized using dimensionality reduction techniques.

## 🔍 What I Did:
Loaded 200-dimensional GloVe vectors and extracted embeddings for a carefully chosen set of overlapping words (e.g., apple, mango, computer).

Applied PCA followed by t-SNE to reduce dimensions to 2D for visualization.

Plotted word vectors using different perplexity values (25, 30, 40, 45, 50) to observe how clustering behavior changes.

## ✨ Key Observations:
At perplexity 25 and 30, the visualizations grouped semantically related words together meaningfully.
Notably, the word apple appeared between mango and computer, effectively capturing its dual nature as both a fruit and a tech brand.

At perplexity 40, the word apple shifted far from mango, indicating a loss in that semantic balance.
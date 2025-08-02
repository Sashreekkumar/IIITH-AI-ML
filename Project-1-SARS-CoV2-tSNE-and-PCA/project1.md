# COVID-19 Variant Classification - Mini Project Summary

In this mini-project, I explored the classification of SARS-CoV-2 variants across Indian states using two powerful dimensionality reduction techniques: Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE). My objective was to uncover hidden patterns and clusters of variants by visualizing high-dimensional genetic and epidemiological data.


---

## What I Did:

* I processed two datasets: `India_685.csv` (epidemiological data) and `sequences.fasta` (genetic sequences).
* I extracted features from both datasets, converting genetic sequences into a numerical format.
* I applied **PCA** for initial dimensionality reduction, then **t-SNE** to create 2D/3D visualizations of variant clusters.
* I mapped these identified variant clusters back to specific Indian states to observe their geographical distribution.

---

## Key Observations:

* **Effective Clustering:** Both PCA and t-SNE successfully reduced complex data, revealing clear groupings of SARS-CoV-2 variants.
* **Geographical Patterns:** The visualizations highlighted distinct geographical patterns in how different variant clusters were distributed across Indian states.
* **Variant Relationships:** t-SNE was particularly useful in showing non-linear relationships, grouping variants that might not seem obvious through simpler methods.
* **Insights into Spread:** This analysis provided valuable insights into the potential emergence and spread of various COVID-19 variants within India.
# ColPali Retrieval Optimization Demo

This repository demonstrates how to optimize **ColPali-based PDF retrieval** using **Qdrant**, with a focus on improving retrieval speed while maintaining quality. The project includes two Jupyter notebooks with experiments and results.

---

## Repository Structure

```plaintext
- ColPali as a reranker I.ipynb
  Covers the initial setup and data preparation:
  - Combining ViDoRe, UFO, and DocVQA datasets into a single collection.
  - Uploading vectors to a Qdrant collection.

- ColPali as a reranker II.ipynb
  Focuses on retrieval experiments:
  - Using pooled vectors for first-stage retrieval and ColPali for reranking.
  - Comparing retrieval quality and speed between pooled and original vectors.
  - Exploring optimizations such as cutting <pad> tokens and binary quantization.
```

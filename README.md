# Text Summarization System (CNN/Daily Mail)

This project implements a text summarization system capable of producing concise summaries from lengthy articles, blogs, or news content. It supports both **extractive summarization** (using `spaCy`) and **abstractive summarization** (using pre-trained models like `BART` from HuggingFace Transformers).

---

## 📌 Objectives

- Preprocess raw news article data.
- Implement extractive summarization using word frequency and sentence scoring.
- Implement abstractive summarization using a pre-trained BART model.
- Fine-tune models (optional) to improve summary quality.
- Evaluate summaries with ROUGE metrics.
- Allow manual testing on real-world input texts.

---

## 📂 Dataset

- **CNN/Daily Mail Dataset**
- Loaded via HuggingFace Datasets:

---

## 🛠️ Project Structure

text-summarization/
- ├── extractive.py # Extractive summarization using spaCy
- ├── abstractive.py # Abstractive summarization using HuggingFace transformers
- ├── evaluate.py # ROUGE evaluation for generated summaries
- ├── dataset.py # Dataset loading and cleaning
- ├── app.py # Manual summarization interface
- ├── requirements.txt # Python dependencies
- └── README.md # Project description


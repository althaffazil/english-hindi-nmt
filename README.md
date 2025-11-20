# **English–Hindi Neural Machine Translation (NMT) using PyTorch, LSTM & Attention**

This project implements an English → Hindi Neural Machine Translation system using a sequence-to-sequence LSTM architecture with Luong Attention. It demonstrates the complete pipeline from text preprocessing to model training and translation.

---

## 🧠 Model Overview

The project includes:

* Encoder LSTM
* Luong Attention mechanism
* Decoder LSTM with attention integration
* Seq2Seq training pipeline
* SentencePiece BPE subword tokenization
* Custom DataLoaders with padding and batching
* Validation and loss tracking

---

## ▶️ Running the Notebook

1. Open the `.ipynb` file in **Google Colab**.
2. Enable GPU:
   **Runtime → Change runtime type → GPU**
3. Run all cells from top to bottom.
4. The notebook handles:

   * Tokenization
   * Model construction
   * Training and validation
   * Translation examples

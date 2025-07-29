## 📘 Project 1: Indonesian-to-English Machine Translation using Keras Hub

### Overview

This project implements a simple Transformer-based **Indonesian-to-English** machine translation system using components from [Keras Hub](https://keras.io/hub/). It covers the full pipeline from tokenization and vocabulary generation to model training, evaluation, and greedy decoding.

### Features

* Custom tokenizer training using WordPiece
* Sequence-to-sequence Transformer architecture with encoder-decoder design
* Special token handling (`[START]`, `[END]`, `[PAD]`)
* Causal masking and padding masking support
* Greedy decoding for inference

### Requirements

> ⚠️ **Note**: You do not need to manually install the `requirements.txt` dependencies if you're using the notebook in Google Colab.
> All necessary libraries are installed within the code cells.
> The `requirements.txt` file simply lists the libraries used for reference or local setup.

If you wish to set it up locally:

```bash
pip install -r requirements.txt
```

---

## 📘 Project 2: Abstractive Summarization with BART

### Overview

This notebook demonstrates **abstractive text summarization** using a pre-trained [BART](https://huggingface.co/facebook/bart-large-cnn) model from Hugging Face Transformers. It leverages transfer learning to summarize long text into concise summaries.

### Features

* Uses `facebook/bart-large-cnn` via 🤗 Transformers
* Tokenizes and truncates long input documents
* Applies maximum length and beam search during generation
* Performs inference using GPU (if available)

### Requirements

> ⚠️ **Note**: You don’t need to run `requirements.txt` when using this notebook in Colab.
> The required packages are already installed via code cells. The `requirements.txt` file is provided just for clarity and optional local use.

To install dependencies manually (e.g., in a local environment):

```bash
pip install -r requirements.txt
```


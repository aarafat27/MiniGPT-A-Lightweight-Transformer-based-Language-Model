# MiniGPT: A Lightweight Transformer-based Language Model

MiniGPT is a simplified implementation of a GPT-style language model built using PyTorch and Hugging Face's Transformers library. It provides a hands-on approach to understanding transformer blocks, self-attention mechanisms, and causal language modeling.

## Features

- Implements a GPT-like architecture with Transformer blocks.
- Includes custom self-attention and feed-forward layers.
- Trains on the Wikitext-2 dataset for text generation.
- Supports tokenization with Hugging Face's GPT-2 tokenizer.
- Demonstrates text generation with nucleus (top-p) sampling.

---

## Requirements

- Python 3.8 or later
- PyTorch 1.10 or later
- Hugging Face Transformers library
- Datasets library for loading datasets

Install dependencies:

```bash
pip install torch transformers datasets

## Nano-GPT
This project is a from scratch implementation of a small GPT style language model built to deeply understand transformer architecture, scaling behavior, and training dynamics.

The model is trained on a single technical book using GPT-2 byte level BPE tokenization (50,257 vocabulary size).

This is a learning focused implementation designed to explore architecture mechanics rather than build a production-scale system.

# Project Goal

The objective of this project is to:

Understand decoder only transformer architecture

Study embedding and unembedding layers

Analyze multi head attention behavior

Observe scaling limits with small datasets

Examine overfitting and memorization patterns

# Architecture Overview

The model follows a decoder only transformer architecture similar to early GPT models such as GPT and GPT-2.

Configuration

Vocabulary Size: 50,257 (GPT-2 tokenizer)

Embedding Dimension (d_model): 128

Transformer Layers: 3

Attention Heads per Layer: 4

Feedforward Hidden Size: 512

Context Window: 256 tokens

Dropout: 0.1

Weight Tying: Enabled (input embeddings tied with output projection)

# What This Project Explores

Relationship between vocabulary size and parameter count

Scaling mismatch between dataset size and model capacity

Attention head specialization

Memorization vs generalization behavior

Training and validation loss divergence

# Future Improvements

Custom tokenizer with reduced vocabulary

Scaling experiments with different embedding dimensions

Improved regularization

Attention visualization tools

Logit lens analysis

Better accuracy and generalization tuning

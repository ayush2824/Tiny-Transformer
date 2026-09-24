# Tiny Transformer

A small character-level Transformer language model built from scratch in PyTorch.

## What it does

The model is trained on Shakespeare text and learns to generate
Shakespeare-style text character by character.

## Features

- Character-level tokenization
- Token and positional embeddings
- Self-attention
- Multi-head attention
- Feed-forward network
- Layer normalization
- Residual connections
- Training and validation loss
- Autoregressive text generation

## Files

- `tiny_transformer.ipynb` — Model implementation and training
- `input.txt` — Shakespeare training dataset

## Purpose

This project was built to understand how Transformer-based language
models work by implementing and training a small model from scratch.

## Learning Resources

This project was built while learning from:

- Andrej Karpathy — Let's build GPT from scratch
- freeCodeCamp — Large Language Model from Scratch
- Zachary Huang — Transformer/Attention/Pytoch/Deep Learning
- "Attention Is All You Need" — Vaswani et al.

The implementation is my own learning project, inspired by the concepts and implementations covered in these resources.

## Experiments

During training, I experimented with:

- Training/validation split
- Different training durations
- Dropout and regularization
- GPU training and autoregressive generation
- Monitoring train vs validation loss
- Observing how generated text evolved during training

The model initially produced repetitive/random characters, but with training
it gradually learned Shakespeare-like vocabulary, dialogue structure,
punctuation, and character patterns.

## Training Results -> (experiment.txt)

Example:

Iterations 2500:
Train Loss: 1.7530
Validation Loss: 1.9441

Iterations 3000:
Train Loss: 1.6077
Validation Loss: 1.8218

The generated text became increasingly structured as training progressed.

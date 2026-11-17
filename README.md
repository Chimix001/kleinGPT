# KleinGPT

A tiny character-level GPT trained on TinyStories, designed to run on a CPU or a single consumer GPU in minutes. Inspired by Andrej Karpathy's nanoGPT.

## Features
- ~424K parameters (2 transformer layers, 4 attention heads, 128-dimensional embeddings).
- Character-level tokenizer with a ~90-token vocabulary.
- Trains on 5,000 TinyStories in under a minute on CPU.
- Automatic CUDA detection for GPU acceleration.
- Checkpoint saving and loading.
- Simple training logs and visualizations using `print()` and Matplotlib.

## Acknowledgements

KleinGPT is inspired by [nanoGPT](https://github.com/karpathy/nanoGPT) by Andrej Karpathy. It builds on his GPT architecture, training approach, and philosophy of keeping language models minimal and easy to understand.

For a more complete and production-oriented implementation, check out nanoGPT and his *Let's build GPT* video.

## Note

KleinGPT is a learning project, not a production-ready language model. Its goal is simple: make GPT architecture easier to understand, experiment with, and train on modest hardware.

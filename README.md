# nanoGPT

This repository contains implementations of two language models:

1. **Bigram Language Model** (bigram.py) – A simple neural network-based bigram model.
2. **Transformer-based GPT Model** (gpt.py) – A more advanced language model using self-attention.

## Features
- Implements a basic bigram language model with embeddings.
- Implements a Transformer-based language model inspired by GPT.
- Uses PyTorch for model training and inference.
- Includes text generation capabilities.

## Installation
Ensure you have Python installed along with the required dependencies:

```sh
pip install torch numpy
```

## Usage
### Running the Bigram Model
```sh
python bigram.py
```
This will train a simple bigram model and generate text.

### Running the GPT Model
```sh
python gpt.py
```
This will train and generate text using a Transformer-based model.

## File Structure
- `bigram.py`: Implements the Bigram Language Model.
- `gpt.py`: Implements a Transformer-based GPT-style model.
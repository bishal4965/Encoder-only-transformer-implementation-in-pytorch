# Encoder-Only Transformer for Sequence Classification

This project implements a simplified version of a Transformer encoder model from scratch using PyTorch. It mimics the architecture of BERT, including token and positional embeddings, multi-head self-attention, feedforward layers, residual connections, and layer normalization. The model is trained on a toy dataset for sequence classification.

## Features

* Encoder-only Transformer architecture
* Multi-head scaled dot-product attention
* Position and token embeddings
* Feedforward network with GELU activation
* Residual connections and layer normalization
* Classification head for sequence classification tasks

## Training

The model is trained using PyTorch on a sample dataset with a standard training and validation loop. Loss is computed using cross-entropy, and accuracy is tracked during validation.

Example training log:

```
Epoch 1/5 - Train Loss: 1.3779 | Val Loss: 1.4415 | Val Acc: 0.3400
Epoch 2/5 - Train Loss: 1.5946 | Val Loss: 1.4800 | Val Acc: 0.3550
...
```

## Requirements

* Python 3.8+
* PyTorch
* Transformers (for tokenizer)
* scikit-learn (for evaluation metrics)


## Usage

1. Clone the repo:
  ```bash
    git clone https://github.com/bishal4965/Encoder-only-transformer-implementation-in-pytorch.git
  ```
2. Run all cells

## Notes

* This project is educational and focuses on clarity and conceptual understanding.
* For real-world applications, consider using Hugging Face’s pre-trained models for performance and stability.

## License

MIT License


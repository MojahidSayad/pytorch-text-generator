# pytorch-text-generator

A simple PyTorch character-level text generator example built from scratch.

The project uses a small bigram language model to learn sequence prediction from `input.txt` and generate new text. This repository is intended for learning and experimentation with PyTorch and language modeling.

## Features

- Character-level tokenization with a custom vocabulary.
- Simple `BigramLanguageModel` using an embedding layer.
- Data batching for training and validation.
- Text generation from a trained model.

## Repository structure

- `main.py` - Example training script and text generation logic.
- `input.txt` - Training text data used to build the vocabulary.
- `more.txt` - Additional text file included in the repository.
- `requirements.txt` - Dependencies required to run the project.
- `Templates/index.html` - HTML template included as part of the project.
- `.gitignore` - Excludes local environment files and sensitive data.

## Requirements

- Python 3.11 or newer
- PyTorch

Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Create and activate a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the training and generation script:

```bash
python main.py
```

## How it works

- `main.py` reads `input.txt` and builds a character vocabulary.
- The text is encoded as integer tokens and split into training and validation sets.
- A simple `BigramLanguageModel` predicts the next character from the current input.
- The training loop updates model weights using `AdamW` and cross-entropy loss.
- After training, the model generates new character sequences.

## Notes

- This is a learning project, not a production-ready text generator.
- The model is intentionally small and designed for demonstration.
- Update `input.txt` with your own text to experiment with different outputs.

## Repository description

A beginner-friendly PyTorch text generation example using a character-level bigram model.

## Author

[Mojahid Sayad](https://github.com/MojahidSayad)

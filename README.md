# pytorch-text-generator

This repository contains a simple PyTorch-based text generation example built from a character-level language model.

## Project structure

- `main.py` - trains and generates text using a PyTorch bigram language model.
- `input.txt` - text dataset used to build the character vocabulary and train the model.
- `requirements.txt` - Python dependencies required to run the project.
- `Templates/index.html` - auxiliary HTML template included in the project.

## Setup

1. Create and activate a Python virtual environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the script:

```bash
python main.py
```

## Notes

- The model in `main.py` is a toy example and is intended for learning how character-based generation works in PyTorch.
- `input.txt` is treated as the training text.
- `.gitignore` excludes the local virtual environment and `.env` file.

## Author

[Mojahid Sayad](https://github.com/MojahidSayad)

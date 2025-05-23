# Simple RAG

## What is this?

This is a simple implementation of a Retrieval-Augmented Generation (RAG).

## Requirements

* NVIDIA GPU
* CUDA
* uv: https://docs.astral.sh/uv/getting-started/installation/

## Installation

```bash
uv sync --frozen
```

Optional: Install nbstripout to automatically remove output cells from Jupyter notebooks before committing them to Git.

```bash
uv run nbstripout --install
```

## Usage

1. Open `rag.ipynb` in Jupyter Notebook.
2. In the first cell, set the path for `documents_dir` to your documents directory.
3. "Run All"
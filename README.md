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

1. `uv run jupyter lab`
2. Open the displayed URL in your browser to access Jupyter Lab.
3. Open `rag.ipynb` in Jupyter Lab.
4. In the first cell, set the path for `documents_dir` to your documents directory.
5. "Run All Cells"

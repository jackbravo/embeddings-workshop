# How to teach new things to your AI

A hands-on workshop exploring how to work with text embeddings for search and retrieval, using modern Python tools and libraries.

Companion to the talk "[How to teach new things to your AI](https://docs.google.com/presentation/d/1so8_4HOEu9WsowwXYrVafhxLB4A3pM36uaWsg34PQCQ/edit?usp=sharing)".

## Overview

This workshop teaches the fundamentals of working with text embeddings through a practical Jupyter notebook that guides participants through:

- Text extraction from PDFs
- Semantic text chunking
- Creating and working with embeddings
- Vector similarity search
- Reranking search results
- Building a simple RAG (Retrieval Augmented Generation) system

## Prerequisites

- Python 3.12
- Basic familiarity with Python and Jupyter notebooks
- Understanding of basic NLP concepts
- A text editor (VS Code recommended)

## Setup

1. Install Python 3.12 using a version manager like:
   - [uv](https://docs.astral.sh/uv/) (recommended)
   - [mise](https://mise.jdx.dev/getting-started.html)

2. Clone this repository and navigate to the project directory:
```bash
git clone [repository-url]
cd [repository-name]
```

3. Create and activate a virtual environment:
```bash
uv venv
source .venv/bin/activate  # On Unix/macOS
# or
.venv\Scripts\activate  # On Windows
```

4. Install dependencies:
```bash
uv pip install -r requirements.txt
```

## Getting Started

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `embeddings.ipynb` and follow along with the tutorial.

## What You'll Learn

- How to extract and process text from PDF documents
- Techniques for semantic text chunking
- Creating and working with text embeddings
- Implementing vector similarity search using DuckDB
- Using rerankers to improve search results
- Building a simple question-answering system

## Additional Resources

- [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) - Compare embedding models
- [Sentence Transformers Documentation](https://www.sbert.net/)
- [DuckDB Documentation](https://duckdb.org/)
- [PyMuPDF Documentation](https://pymupdf.readthedocs.io/)

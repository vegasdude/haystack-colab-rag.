[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vegasdude/haystack-colab-rag/blob/master/colab_notebook.ipynb)

# Haystack Colab RAG

This repository contains a **Google Colab notebook** that implements a Retrieval-Augmented Generation (RAG) pipeline using **Haystack** and **OpenAI**. It allows you to query PDFs, TXT, and DOCX files stored in Google Drive via an interactive GUI.

## Features
- Automatic loading of PDFs, TXT, DOCX files
- Embedding cache for faster processing
- Summarization of large documents
- Multi-turn conversation memory
- Interactive GUI in Colab
- Optional model switching (`gpt-3.5-turbo` or `gpt-4o-mini`)
- Auto-updates document store when new files are added

## How to Use
1. Open the `colab_notebook.ipynb` in Google Colab.
2. Mount your Google Drive.
3. Enter your OpenAI API key when prompted (do **not** hardcode it).
4. Place your documents in a folder (default: `/MyDrive/my_docs/`).
5. Use the GUI to type questions and receive answers.
6. Add new documents anytime — they will be automatically loaded.

## Folder Structure

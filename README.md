# Text Generation with GPT-2

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/) [![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Transformers-orange.svg)](https://huggingface.co/docs/transformers/index) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview
This project demonstrates text generation using the GPT-2 model from Hugging Face. It involves fine-tuning a pre-trained GPT-2 on a small custom dataset of AI-inspired poetic text, then using the fine-tuned model to generate new text based on prompts. The implementation is in a Jupyter Notebook, covering data preparation, model training, and inference, making it suitable for exploring language model fine-tuning and generative AI.

GPT-2 is a transformer-based model known for its ability to generate human-like text. This project shows how to adapt it for a specific style (poetic AI themes) using minimal data and resources.

## Problem Statement
Fine-tune a pre-trained GPT-2 model on a custom dataset of AI-themed poetic text to generate coherent and stylistically similar continuations from given prompts. The implementation should utilize the Hugging Face Transformers library to load the model and tokenizer, prepare the dataset, perform fine-tuning with specified training arguments, and demonstrate text generation capabilities, highlighting the process of adapting large language models for domain-specific creative tasks without building from scratch.

## Features
- **Custom Dataset Creation**: Generates a repeated poetic dataset for fine-tuning.
- **Model Fine-Tuning**: Uses Hugging Face Trainer for efficient training on GPT-2.
- **Text Generation**: Employs a pipeline for generating text from prompts post-fine-tuning.
- **Simple and Educational**: Disables wandb for clean runs; easy to extend with larger datasets.
- **Dependencies**: Relies on transformers and datasets libraries.

## Requirements
- Python 3.x
- Jupyter Notebook (or JupyterLab) for running the `.ipynb` file
- Required packages (installed via pip in the notebook):
  - transformers
  - datasets

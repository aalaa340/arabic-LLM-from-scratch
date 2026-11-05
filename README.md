 # arabic-LLM-from-scratch
Implementing a character-level language model from scratch using PyTorch, following Andrej Karpathy's LLM tutorial, with an Arabic text dataset.

Status: In Progress 

## Overview
This project explores the fundamental concepts behind Large Language Models (LLMs) by implementing a language model from scratch using Python and PyTorch.

It follows the educational tutorial by Andrej Karpathy, Let's build GPT from scratch, with an adaptation that uses an Arabic text dataset instead of the original Tiny Shakespeare dataset.

The main objective is to understand the internal mechanisms of language modeling, including tokenization, embeddings, model architecture, training, and text generation.

## Objectives

Understand how language models learn statistical patterns from text.

Implement a character-level language model using PyTorch.

Experiment with Arabic text as the training dataset.

Understand the training and text-generation processes.

Develop a stronger practical understanding of the foundations of LLMs.

## Technologies

Python

PyTorch

NumPy

google colab

## Dataset

An Arabic text dataset containing approximately 1.1 million characters.

The dataset contains Arabic text covering different topics, including science, technology, education, nature, and everyday life.

## Current Progress

### Part 1: Baseline Language Model

- [x] Reading and exploring the dataset
- [x] Character-level tokenization
- [x] Train/validation split
- [x] Batch generation
- [x] Building the Bigram Language Model
- [x] Loss estimation and text generation
- [x] Training the Bigram Language Model

### Part 2: Understanding Self-Attention

- [ ] Averaging past context
- [ ] Weighted aggregation
- [ ] Matrix-based aggregation
- [ ] Softmax in self-attention
- [ ] Positional encoding
- [ ] Queries, keys, and values
- [ ] Scaled self-attention

### Part 3: Building the Transformer

- [ ] Implementing self-attention
- [ ] Multi-head self-attention
- [ ] Feed-forward neural network
- [ ] Residual connections
- [ ] Layer normalization
- [ ] Dropout
- [ ] Combining Transformer blocks

### Part 4: GPT Architecture and Training

- [ ] Understanding encoder vs. decoder Transformers
- [ ] Building the GPT architecture
- [ ] Implementing the language model head
- [ ] Initializing model parameters
- [ ] Training the GPT model
- [ ] Evaluating training and validation loss
- [ ] Generating text using the trained model

### Part 5: Arabic Language Model Experiments

- [ ] Preparing the Arabic dataset
- [ ] Training the model on Arabic text
- [ ] Generating Arabic text
- [ ] Evaluating generated Arabic text
- [ ] Analyzing model limitations
- [ ] Experimenting with different model configurations
Progress will be updated as development continues.

## Project Structure

arabic-llm-from-scratch/
│
├── README.md
├── arabic_dataset.txt
├── bigram_model.ipynb

## Learning Resources

Andrej Karpathy – Let's build GPT from scratch.

## Future Improvements

Experiment with different model configurations.

Analyze the quality of generated Arabic text.

Explore improvements to the language modeling architecture.

Investigate the challenges of character-level language modeling in Arabic.

## Author

Aalaa Khogali

Electrical and Electronics Engineering Student

Interested in Machine Learning, Deep Learning, NLP, and AI Safety.

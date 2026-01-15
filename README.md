# ML-yearning-LLM-summarizer
Fine-tuning an open-source LLM to summarize chapters from Machine Learning Yearning using LoRA

# LLM Fine-Tuning for Educational Textbook Summarization

This project implements an end-to-end pipeline to summarize chapters from the book *Machine Learning Yearning* using open-source transformer models and parameter-efficient fine-tuning techniques.

## 📌 Project Overview
- Extracts text from a textbook PDF
- Splits long chapters into token-safe chunks
- Generates chapter-level summaries using transformer models
- Prepares instruction-style data for fine-tuning
- Fine-tunes an open-source LLM using LoRA

## 🧠 Models & Techniques
- Summarization: BART / DistilBART
- Fine-tuning: Falcon (LoRA)
- Instruction tuning for chapter summarization

## 🛠️ Tech Stack
- Python
- Hugging Face Transformers & Datasets
- PyTorch
- PEFT (LoRA)
- PyPDF2


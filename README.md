# Emotion-Aware Dialogue Summarization
A dissertation project for the MSc in Data Science focused on summarizing emotionally rich conversations using modern NLP techniques.

## 💡 The Project
This project tackles the challenge of summarizing empathetic dialogues by fine-tuning a specialized BART model and comparing its performance against modern Large Language Models (LLMs), including an advanced RAG implementation. A key part of this research involved identifying and correcting a major structural flaw in the popular EmpatheticDialogues dataset.

## Key Finding
The primary finding is that a specialized, fine-tuned model significantly outperforms general-purpose LLMs on this nuanced summarization task, proving the value of task-specific training.

## ⚙️ How to Run
The project is organized into a series of Jupyter Notebooks that should be run in order.

01_Data_Cleaning_and_EDA.ipynb: Analyzes the source data and creates the cleaned, reliable train/validation/test splits.

02_BART_Fine_Tuning.ipynb: Fine-tunes the BART models (with and without emotion labels).

03_LLM_Experiments.ipynb: Runs the Zero-Shot and RAG experiments using Ollama.

04_Evaluation.ipynb: Calculates the final ROUGE and BERTScore metrics and generates the result visualizations.


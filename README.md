# Fine-tuning Phi-2 for Text Summarization (XSum)

## Overview
This repository fine-tunes a decoder-only LLM (Phi-2) for abstractive summarization using XSum.
Training uses parameter-efficient fine-tuning (LoRA) with 4-bit quantization to fit in Colab T4.

## Dataset
- EdinburghNLP/xsum (HuggingFace Datasets)

## Model
- microsoft/phi-2
- PEFT: LoRA (4-bit)

## Repository Structure
- notebooks/
- reports/
- requirements.txt

## Notebooks
1. notebooks/01_prepare_xsum.ipynb
2. notebooks/02_finetune_phi2_lora.ipynb
3. notebooks/03_evaluate_rouge.ipynb

## Results (fill after running)
| Model | Epochs | ROUGE-1 | ROUGE-2 | ROUGE-L |
|------|--------|---------|---------|---------|
| phi-2 (LoRA 4-bit) |  |  |  |  |

## Identification
- ANOM NUR MAULID - 1103223193 - TK4601
- DARRELL CHESTA ADABI - 1103223128 - TK4601

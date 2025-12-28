# Zen Koan NLP Analysis

**동아시아 선 공안(禪公案)의 언어 구조에 대한 정량적 분석**

A Quantitative NLP Analysis of East Asian Zen Koans: Redefining as a Designed System of Logic Refusal

## Overview

This project applies computational linguistics methods to analyze the linguistic structure of Zen Buddhist koans, comparing them with Buddhist sutras, Confucian classics, and Tang-Song prose.

**Core Research Question:** Are koans truly "illogical," or do they possess a deliberately designed linguistic structure that blocks logical reasoning?

## Project Structure

```
zen-koan-nlp-analysis/
├── data/
│   ├── raw/           # Original text files
│   ├── processed/     # Preprocessed data
│   └── chunks/        # Chunked data for analysis
├── src/
│   ├── preprocessing/ # Text cleaning & tokenization
│   ├── analysis/      # NLP feature extraction
│   ├── statistics/    # Statistical analysis
│   └── visualization/ # Plotting scripts
├── notebooks/         # Jupyter notebooks
├── results/
│   ├── figures/       # Generated plots
│   ├── tables/        # Result tables
│   └── statistics/    # Statistical outputs
├── paper/             # Paper drafts
└── docs/              # Documentation
```

## Dataset

| Category | Texts | Est. Words |
|----------|-------|------------|
| Koans | 2 (98 cases) | ~70,000 |
| Buddhist Sutras | 8 | ~60,000 |
| Confucian Classics | 5 | ~50,000 |
| Tang-Song Prose | 25 | ~50,000 |

## Installation

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

## Methodology

Three-level analysis design:
1. **Level 1 (Original Units):** Preserves genre characteristics
2. **Level 2 (Chunked):** Controls for length effects
3. **Level 3 (Statistical):** Linear Mixed Models with covariates

## License

MIT License

## Citation

```
Kim, H. (2026). A Quantitative NLP Analysis of Zen Koans. 
```

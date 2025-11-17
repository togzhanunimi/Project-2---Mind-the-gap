# Mind the Gap (P2): Measuring and Mitigating Gender Bias in DistilBERT

📌 Project Overview

This project analyzes and mitigates gender stereotype bias in the lightweight transformer model DistilBERT using the StereoSet benchmark.
The workflow follows the official “Mind the Gap” methodology:

Bias Evaluation (baseline)

Counterfactual Data Augmentation (CDA)

Fine-Tuning

Re-evaluation and comparison

All experiments are efficient, transparent, and reproducible.

🎯 Objectives

Evaluate gender bias using Pseudo Log-Likelihood (PLL) on StereoSet

Generate CDA data via gender-swapped profession templates

Fine-tune the model on:

- CDA-only data

- Balanced CDA + original sentences

Compare baseline vs mitigated models using SS (Stereotype Score) & LM (Language Modeling Score)
 

## Repository Contents
- `Stereotype_Analysis_Report.pdf` – final project report (7 pages).
- `Project_2__Stereotype_Analysis_CLEAN.ipynb` – Jupyter/Colab notebook with code and experiments.
- `README.md` – this file.

## How to Run
You can open the notebook in **Google Colab** or run locally:
```bash
pip install transformers datasets torch accelerate matplotlib pandas tqdm

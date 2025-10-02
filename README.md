# Mind the Gap (P2): Measuring and Mitigating Gender Bias in DistilBERT

This repository contains the code and report for my final project in **Text Mining and Sentiment Analysis**.

## 📌 Project Overview
The aim of this project is to:
1. Evaluate gender bias in a lightweight transformer model (DistilBERT) using the StereoSet benchmark.
2. Apply **Counterfactual Data Augmentation (CDA)** by generating gender-swapped profession-related sentences.
3. Fine-tune the model with CDA data.
4. Re-evaluate the model and compare baseline vs mitigated results.

## 📊 Results
- **Baseline SS%**: 41.5  
- **Mitigated SS%**: 0.0  
- **Baseline LM%**: 95.5  
- **Mitigated LM%**: 100.0  

The results show that CDA reduced stereotype preference but over-corrected, while fluency was preserved.

## 📂 Repository Contents
- `Project_2_Text_Mining_and_Sentimental_Analysis.pdf` – final project report (7 pages).
- `Project_2.ipynb` – Jupyter/Colab notebook with code and experiments.
- `README.md` – this file.

## 🚀 How to Run
You can open the notebook in **Google Colab** or run locally:
```bash
pip install transformers datasets torch accelerate matplotlib pandas tqdm

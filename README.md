# Evolutionary Analysis of Kisspeptin Proteins via MSA and PAM250

This repository contains the complete workflow developed for the bioinformatics project entitled **"Evolutionary Analysis of Kisspeptin Proteins via Multiple Sequence Alignment and PAM250 Matrix"**, presented at the **II Encontro Regional de Engenharia de Bioprocessos e Biotecnologia**, under the thematic axis of **Golden Biotechnology (Bioinformatics)**.

---

## Project Overview

Kisspeptins (Kiss1 and Kiss2) are peptide hormones involved in the regulation of puberty and reproductive functions across vertebrates. Due to their evolutionary divergence, analyzing their sequence similarity across species offers insights into functional conservation and diversification.

This project applied **multiple sequence alignment (MSA)** and **evolutionary clustering** techniques to analyze Kiss1 and Kiss2 protein sequences from human, mouse, opossum, frog, and zebrafish.

---

## Objectives

- Perform MSA of kisspeptin protein sequences using the **MUSCLE** algorithm.
- Evaluate sequence similarity using the **PAM250 substitution matrix**.
- Calculate pairwise identity percentages between sequences.
- Visualize similarity through **heatmaps** and **dendrograms**.
- Identify conservation patterns and evolutionary clusters among Kiss1 and Kiss2 isoforms.

---

## Dataset

Protein sequences were obtained from a public dataset on Kaggle:

> 🔗 https://www.kaggle.com/datasets/samira1992/sequence-alignment-bioinformatics-dataset

- File used: `proteins.fasta`
- Includes 7 kisspeptin sequences from:
  - Human (Kiss1)
  - Mouse (Kiss1)
  - Opossum (Kiss1)
  - Frog (Kiss1 and Kiss2)
  - Zebrafish (Kiss1 and Kiss2)

---

## Methodology

The full analysis was performed using **Google Colab**, leveraging:

- `Biopython` for sequence handling and alignment parsing  
- `MUSCLE v5` for performing multiple sequence alignment  
- `Pandas` and `NumPy` for identity matrix generation  
- `Seaborn` and `Matplotlib` for heatmap and dendrogram visualization  
- `Scipy` for hierarchical clustering

All analysis steps are included and documented in the notebook:

📄 **[`kisspeptin_msa_analysis.ipynb`](./kisspeptin_msa_analysis.ipynb)**

---

## Results

- **Pairwise identity matrix** showed high conservation among mammalian Kiss1 proteins (>47%) and lower identity (<35%) for Kiss2 proteins across species.
- **Dendrogram** revealed clear evolutionary separation between Kiss1 and Kiss2 groups.
- **Consensus sequence** indicated conserved regions in Kiss1, suggesting functional preservation.

---

# AI_LAB - Hypoxia Detection in Cancer Cells via RNA-Seq Analysis

This repository contains the code and documentation for a project developed as part of the AI Lab course at **Bocconi University**. The objective is to classify cancer cells as hypoxic or normoxic by analyzing their gene expression profiles obtained through single-cell RNA sequencing.

## 🧬 Project Overview

Understanding how cancer cells adapt to different oxygen conditions is crucial to improving treatment strategies. This project focuses on:

- exploring the transcriptional changes induced by varying oxygen levels;
- analyzing single-cell RNA-seq data from two breast cancer cell lines: HCC1806 (epithelial) and MCF7 (adenocarcinoma);
- differentiating between normoxic and hypoxic conditions using exploratory data analysis, unsupervised, and supervised ML techniques.

## 📁 Data

The dataset consists of `.csv` tables where:
- columns represent individual sequenced cells with labels indicating oxygen conditions;
- rows represent genes, identified by unique gene symbols;
- data were obtained using both Smart-Seq and Drop-Seq techniques.

> **Note: Raw data is not included due to privacy constraints.**

## 📊 Methods

The project pipeline includes:
- Exploratory Data Analysis (EDA)
- Dimensionality Reduction (PCA, t-SNE)
- Clustering
- Classification Models (Logistic Regression, Random Forest, SVM, RNN)

## 🧠 Key Goals

- Identify **marker genes** associated with hypoxia.
- Understand **oxygen-driven transcriptional heterogeneity** in tumor cells.
- Build models that can **predict oxygen status** based on gene expression.

## 🛠 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebooks
- scRNA-seq data analysis libraries

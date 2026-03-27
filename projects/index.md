---
layout: page
title: Projects
---

A collection of data analytics projects completed during my Master of Science in Data Analytics at Western Governors University (Oct 2022 – Oct 2023), plus ongoing work at the intersection of clinical laboratory science and data.

---

## MS Data Analytics — WGU Projects

**[View full repository on GitHub](https://github.com/Daruwu/MSDA_WGU)**

---

### D206: Data Cleaning
**Tools:** Python, Pandas  
Real-world datasets are messy. This project focused on identifying and handling missing values, outliers, and inconsistencies to prepare data for downstream analysis. Built a repeatable cleaning pipeline that documented every transformation decision.  
[View on GitHub](https://github.com/Daruwu/MSDA_WGU/blob/main/D206)

---

### D207: Exploratory Data Analysis
**Tools:** Python, Pandas, Matplotlib, Seaborn  
Explored a healthcare dataset to uncover patterns, distributions, and relationships between variables before any modeling. Used statistical summaries and visualizations to generate hypotheses and guide further analysis.  
[View on GitHub](https://github.com/Daruwu/MSDA_WGU/blob/main/D207)

---

### D208: Predictive Modeling
**Tools:** Python, Scikit-learn  
Built and evaluated regression and classification models to predict outcomes from structured data. Covered feature selection, model tuning, cross-validation, and performance metrics including ROC-AUC and confusion matrices.  
[View on GitHub](https://github.com/Daruwu/MSDA_WGU/blob/main/D208)

---

### D209: Data Mining I
**Tools:** Python, Scikit-learn  
Applied unsupervised and supervised machine learning techniques including k-means clustering and decision trees to identify hidden structure in data. Focused on pattern recognition and actionable insight extraction.  
[View on GitHub](https://github.com/Daruwu/MSDA_WGU/blob/main/D209)

---

### D210: Representation & Reporting
**Tools:** Tableau  
Designed interactive dashboards and data visualizations to communicate analytical findings to non-technical audiences. Emphasized storytelling with data — translating complex results into clear, decision-ready visuals.  
[View on GitHub](https://github.com/Daruwu/MSDA_WGU/blob/main/D210)

---

### D211: Advanced Data Acquisition
**Tools:** SQL, PostgreSQL  
Wrote complex SQL queries to extract, join, and aggregate data from relational databases. Covered subqueries, CTEs, window functions, and database design principles for efficient data retrieval at scale.  
[View on GitHub](https://github.com/Daruwu/MSDA_WGU/blob/main/D211)

---

### D212: Data Mining II
**Tools:** Python, TensorFlow, Scikit-learn  
Advanced machine learning methods including neural networks, ensemble methods, and dimensionality reduction. Evaluated model performance and interpretability trade-offs on complex datasets.  
[View on GitHub](https://github.com/Daruwu/MSDA_WGU/blob/main/D212)

---

### D213: Advanced Data Analysis
**Tools:** Python, Statsmodels  
Applied time series analysis and NLP techniques to structured and unstructured data. Explored ARIMA modeling, sentiment analysis, and text mining to extract insights from temporal and language-based datasets.  
[View on GitHub](https://github.com/Daruwu/MSDA_WGU/blob/main/D213)

---

### D214: MS Data Analytics Capstone
**Tools:** Python, SQL, Tableau  
Culminating project integrating skills across the entire program. Defined a research question, acquired and cleaned data, performed analysis, built visualizations, and delivered a full written report and presentation.  
[View on GitHub](https://github.com/Daruwu/MSDA_WGU/blob/main/D214)

---

## Bioinformatics — Python Projects

A collection of Python scripts developed during early bioinformatics coursework, focused on DNA sequence analysis algorithms built from scratch — emphasizing an understanding of the underlying biology and computation.

---

### DNA Sequence Analysis Toolkit
**Tools:** Python, BioPython  
A suite of command-line tools for analyzing DNA sequences, including nucleotide counting, k-mer frequency analysis, and pattern matching. Scripts accept raw sequence input and return counts, positions, or frequency arrays — replicating core operations used in genome analysis pipelines.  
*Scripts: `side_project.py`, `seq.py`, `frequent_words.py`, `array_frequency.py`, `pattern.py`, `position.py`*

---

### Approximate Pattern Matching with Hamming Distance
**Tools:** Python, BioPython  
Implements approximate string matching on DNA sequences using Hamming distance — identifying where a target pattern appears in a genome even when allowing for a set number of mismatches. Directly applicable to mutation detection and primer design in genomics workflows.  
*Scripts: `Approx_Pat_Match.py`, `hamming_dist.py`, `test_code.py`*

---

### k-mer Neighborhood & Mismatch Analysis
**Tools:** Python  
Generates all k-mer neighbors within a given Hamming distance and identifies the most frequent k-mers accounting for mismatches and reverse complements. Useful for identifying transcription factor binding sites and replication origin candidates in genomic sequences.  
*Scripts: `d_neighbor.py`, `fr_words_mis.py`, `fr_mis_rev.py`*

---

### Genome Skew & Replication Origin Analysis
**Tools:** Python  
Computes the GC skew across a genome and identifies minimum skew positions — a technique used to predict the origin of replication (oriC) in bacterial genomes. Also includes clump finding to locate regions of high k-mer density.  
*Scripts: `min_skew.py`, `clump.py`*

---

### RNA-seq Differential Expression Data Processing
**Tools:** Python, NumPy, JSON  
Parses and cross-references DESeq2 differential expression output with sequence annotation files, merging datasets by gene identifier and filtering out NA log-fold change values. Outputs a clean structured table ready for downstream visualization or statistical analysis — bridging raw pipeline output and interpretable results.  
*Scripts: `converttodict.py`, `table2.py`*

---

### GC Content Analysis from FASTA Files
**Tools:** Python, BioPython  
Reads multi-sequence FASTA files, computes GC content for each record, and identifies the sequence with the highest GC percentage — a standard quality metric in genomics and a foundational Rosalind bioinformatics problem.  
*Scripts: `transcribe.py`*

# 🧬 BRCA1 Gene Sequence Analysis

A Python-based bioinformatics project for analyzing the human **BRCA1 gene sequence** and comparing its sequence characteristics with **TP53** and **INS**.

## 📌 Project Overview

This project uses computational methods to analyze the human **BRCA1 gene** at the nucleotide and protein sequence level.

The analysis focuses on:

- Retrieving and analyzing a BRCA1 reference transcript
- Examining DNA sequence characteristics
- Transcribing DNA into RNA
- Translating the nucleotide sequence into a protein sequence
- Calculating nucleotide composition and GC content
- Visualizing GC-content variation across the sequence
- Comparing BRCA1 with TP53 and INS based on sequence length and GC content

## 🧬 BRCA1 Sequence Analysis

The BRCA1 transcript analyzed in this project is:

**NCBI Accession:** `NM_007294.4`

**Description:** Homo sapiens BRCA1 DNA repair associated (BRCA1), transcript variant 1, mRNA

### Analysis Performed

- DNA sequence retrieval
- DNA sequence length calculation
- Nucleotide composition analysis
- GC content calculation
- DNA → RNA transcription
- DNA → protein translation
- Sequence visualization

### Key Result

| Feature | BRCA1 |
|---|---:|
| Accession | NM_007294.4 |
| Sequence length | 7088 bp |
| GC content | 41.77% |

The analyzed BRCA1 sequence contains **7088 base pairs** with a GC content of **41.77%**.

## 📊 Gene Comparison

BRCA1 was compared with **TP53** and **INS** to examine differences in sequence length and GC content.

| Gene | Length | GC Content |
|---|---:|---:|
| BRCA1 | 7088 bp | 41.77% |
| TP53 | 2512 bp | 53.38% |
| INS | 465 bp | 63.87% |

The comparison shows that:

- **BRCA1** has the longest sequence among the three.
- **INS** has the highest GC content.
- **TP53** has intermediate sequence length and GC content.

> Note: GC content is reported as a sequence characteristic. It should not by itself be interpreted as a direct measure of biological stability.

## 📈 Visualization

The project includes a comparative visualization of:

- GC content
- Gene length
- GC content vs. sequence length

![Human Gene Comparison](gene_comparison.png)

## 🛠️ Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Biopython**
- Sequence analysis
- Data visualization

## 📁 Project Structure

```text
BRCA1-Gene-Analysis/
│
├── BRCA1_Gene_Analysis.ipynb
├── Gene_Comparison.ipynb
├── BRCA1_analysis_report.txt
├── gene_comparison_report.txt
├── gene_comparison.png
└── README.md

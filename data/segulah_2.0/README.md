arkdown
# 🔬 Segulah‑L: Antimicrobial Resistance (AMR) Analysis Platform

**Author:** Lubanah Younes  
**Date:** March 2026  
**GitHub:** [Lubanah-Younes](https://github.com/Lubanah-Younes)

---

## 📋 Project Overview

Segulah‑L is a comprehensive bioinformatics platform for detecting and analyzing antimicrobial resistance (AMR) genes in bacterial genomes.  
The platform was developed to screen **9 Klebsiella pneumoniae genomes** and identify resistance genes from multiple families.

### 🎯 Key Achievements
- ✅ **9 bacterial genomes** fully analyzed
- ✅ **3 SHV genes** discovered and extracted
- ✅ **2 perfect matches** (100% identity with reference SHV-27)
- ✅ **16+ scientific reports** generated
- ✅ **4 publication-ready figures** created
- ✅ **BLAST validation** against NCBI database

---

## 🏗️ Project Structure
Segulah‑L/
├── 📁 data/
│ ├── 📄 SHV-*_extracted.fasta # Extracted SHV gene sequences
│ └── 📁 segulah_2.0/ # Final results (CSV, PNG, PML)
├── 📁 reports/ # All generated reports (16+)
├── 📄 Lubanah_Segulah_70_MEGA_REPORT.py # Main analysis script
├── 📄 Lubanah_Segulah_71_ULTIMATE_ANALYSIS.py
├── 📄 requirements.txt # Dependencies
└── 📄 README.md # This file

text

---

## 🔬 Key Discoveries

### 🏆 SHV-27: First 100% Match
- Found in **2 independent genomes**
- **100% identical** to reference (AF293345)
- Perfect protein conservation
- Chromosomal location (stable inheritance)

### 🎯 SHV-28: First Genomic Extraction
- Found in genome GCF_055814305.1
- **99.88% identity** to reference
- Single synonymous SNP (no protein change)

### ❓ TEM Family: Notable Absence
- **No TEM genes** found in any genome
- SHV appears to be dominant family in this collection

---

## 📊 Publication-Ready Figures

| Figure | Description | File |
|--------|-------------|------|
| Figure 1 | SHV Gene Distribution | `data/segulah_2.0/figure1_shv_distribution.png` |
| Figure 2 | Protein Properties | `data/segulah_2.0/figure2_protein_properties.png` |
| Figure 3 | BLAST Heatmap | `data/segulah_2.0/figure3_blast_heatmap.png` |
| Figure 4 | Secondary Structure | `data/segulah_2.0/figure4_secondary_structure.png` |

---

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/Lubanah-Younes/Segulah-L.git
cd Segulah-L

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the complete analysis
python Lubanah_Segulah_71_ULTIMATE_ANALYSIS.py
📚 Generated Reports
Main reports are available in the reports/ directory:

Segulah-L_MEGA_REPORT.md – Complete project overview

Segulah-L_2.0_ULTIMATE_PLUS.md – Final analysis

Segulah-L_Report_SHV_Unified.md – SHV family summary

Family-specific reports: CMY, CTX-M, KPC, NDM, OXA, SHV, TEM

🛠️ Technologies Used
Python (Biopython, Pandas, Matplotlib, Seaborn)

Bioinformatics (BLAST, ResFinder, CARD)

Data Analysis (SNP detection, sequence alignment)

Visualization (Publication-quality figures)

3D Modelling (PyMOL scripts)

📈 Project Statistics
Metric	Count
Genomes Analyzed	9
Resistance Families	8
Genes Discovered	3
Perfect Matches	2
Scientific Reports	16+
BLAST Hits	15
Visualization Files	4
📬 Contact
Lubanah Younes 081227
Bioinformatics Researcher
📍 Syria
🔗 GitHub Profile

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

Built with 🤍 by Lubanah Younes
Last updated: March 2026
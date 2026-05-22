<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,30&height=180&section=header&text=Chagas%20Disease%20Vaccine&fontSize=32&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Multi-Epitope%20Vaccine%20Design%20Against%20Trypanosoma%20cruzi&descAlignY=60&descSize=15" width="100%"/>
</div>

<h1 align="center">💉 Multi-Epitope Vaccine Against Chagas Disease</h1>
<h3 align="center">Targeting ASP-2 Protein of Trypanosoma cruzi</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Author-Ali%20Naqi-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/University-GCUF-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Field-Immunoinformatics-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Disease-Chagas-orange?style=for-the-badge"/>
</p>

---

## 📖 Abstract

Chagas disease caused by **Trypanosoma cruzi** affects 
**6-7 million people worldwide** with no approved vaccine. 
This study uses **reverse vaccinology and immunoinformatics** 
to design a multi-epitope vaccine targeting the 
**ASP-2 (Amastigote Surface Protein-2)** of T. cruzi.

---

## 🌍 Disease Overview

| Property | Details |
|----------|---------|
| **Disease** | Chagas Disease |
| **Causative Agent** | Trypanosoma cruzi |
| **Vector** | Triatomine bugs |
| **People Affected** | ~6-7 million worldwide |
| **Vaccine Status** | ❌ No approved vaccine |
| **Our Solution** | ✅ Multi-epitope computational vaccine |

---

## 🎯 Target Protein: ASP-2

| Property | Details |
|----------|---------|
| **Full Name** | Amastigote Surface Protein-2 |
| **Organism** | Trypanosoma cruzi |
| **Why ASP-2?** | Strong immunogenicity + Surface exposed |
| **Stage** | Amastigote (intracellular) |

---

## 🔬 Complete Methodology
STEP 1 → Retrieve ASP-2 sequence from NCBI/UniProt
↓
STEP 2 → Predict B-Cell Epitopes (BepiPred, Ellipro)
↓
STEP 3 → Predict CTL Epitopes/MHC-I (NetMHCpan 4.1)
↓
STEP 4 → Predict HTL Epitopes/MHC-II (NetMHCII)
↓
STEP 5 → Filter by Antigenicity (VaxiJen > 0.5)
↓
STEP 6 → Filter Non-Allergenic (AllerTop)
↓
STEP 7 → Assemble Vaccine with Linkers + Adjuvant
↓
STEP 8 → Physicochemical Analysis (ProtParam)
↓
STEP 9 → 3D Structure Prediction (AlphaFold2)
↓
STEP 10 → Molecular Docking with TLR-4 (ClusPro)
↓
STEP 11 → MD Simulation 100ns (GROMACS)
↓
STEP 12 → Validation (PROCHECK, ProSA, ERRAT)

---

## 💉 Vaccine Design

### Construct Architecture:
β-Defensin Adjuvant] - EAAAK -
[CTL Epitope 1] - AAY - [CTL Epitope 2] - AAY - [CTL Epitope 3] -
GPGPG -
[HTL Epitope 1] - GPGPG - [HTL Epitope 2] - GPGPG - [HTL Epitope 3] -
KK -
[B-Cell Epitope 1] - KK - [B-Cell Epitope 2] - KK - [B-Cell Epitope 3]

### Linkers Explained:
| Linker | Used For | Purpose |
|--------|---------|---------|
| EAAAK | Adjuvant connection | Rigid, prevents interference |
| AAY | Between CTL epitopes | Helps proteasomal cleavage |
| GPGPG | Between HTL epitopes | Flexible, maintains structure |
| KK | Between B-cell epitopes | Flexible spacer |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| NCBI / UniProt | Protein sequence retrieval |
| BepiPred 2.0 | B-cell epitope prediction |
| NetMHCpan 4.1 | CTL epitope prediction (MHC-I) |
| NetMHCII | HTL epitope prediction (MHC-II) |
| VaxiJen 2.0 | Antigenicity prediction |
| AllerTop | Allergenicity assessment |
| ToxinPred | Toxicity prediction |
| ExPASy ProtParam | Physicochemical properties |
| AlphaFold2 | 3D structure prediction |
| PyMOL | Structure visualization |
| ClusPro 2.0 | Molecular docking |
| GROMACS | MD Simulation (100 ns) |
| PROCHECK | Structure validation |

---

## 📊 Results Summary

### Epitope Selection:
| Type | Predicted | Selected |
|------|-----------|---------|
| B-Cell Epitopes | 45 | 3 |
| CTL (MHC-I) | 89 | 3 |
| HTL (MHC-II) | 67 | 3 |

### Vaccine Properties (ProtParam):
| Property | Value | Status |
|----------|-------|--------|
| Molecular Weight | ~49 kDa | ✅ Good |
| Isoelectric Point | 8.5 | ✅ Good |
| Instability Index | 32.4 | ✅ Stable |
| GRAVY Score | -0.45 | ✅ Hydrophilic |
| Antigenicity | 0.78 | ✅ Antigenic |
| Allergenicity | Non-allergenic | ✅ Safe |

### MD Simulation (100 ns):
| Parameter | Result | Status |
|-----------|--------|--------|
| RMSD | 2.1 ± 0.3 Å | ✅ Stable |
| RMSF | 1.5 ± 0.4 Å | ✅ Normal |
| Radius of Gyration | 32.4 Å | ✅ Compact |
| H-bonds | 145 ± 12 | ✅ Strong |

---

## 👨‍🔬 Author

**Ali Naqi**
- 🎓 BS Bioinformatics, GCUF
- 📧 alinaqi@gmail.com
- 🔗 GitHub: [alinaqi](https://github.com/alinaqi)
- 💼 LinkedIn: [Ali Naqi](https://linkedin.com/in/alinaqi)

---

## 📜 Citation

If you use this work please cite:
Ali Naqi (2024). Multi-Epitope Vaccine Design Against
Chagas Disease. BS Bioinformatics Project, GCUF, Pakistan.
GitHub: https://github.com/alinaqi/chagas-vaccine-design

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,30&height=100&section=footer" width="100%"/>
</div>

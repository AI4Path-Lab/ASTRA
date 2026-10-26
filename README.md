<div align="center">

# ASTRA

### Histology-based computational gatekeeper for pre-analytical molecular specimen qualification

<p>
  <img src="https://img.shields.io/badge/Status-Manuscript%20under%20preparation-orange?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/Code-Release%20upon%20acceptance-lightgrey?style=flat-square" alt="Code">
  <img src="https://img.shields.io/badge/WSIs-55%2C398-blue?style=flat-square" alt="WSIs">
  <img src="https://img.shields.io/badge/Patients%20%2F%20Donors-23%2C932-blue?style=flat-square" alt="Patients">
  <img src="https://img.shields.io/badge/Lab-AI4Path%20%40%20OSU-bb0000?style=flat-square" alt="Lab">
</p>

<p>
  <a href="#-manuscript">Manuscript</a> •
  <a href="#-study-overview">Study Overview</a> •
  <a href="#-planned-release">Planned Release</a> •
  <a href="#-data-availability">Data</a> •
  <a href="#-citation">Citation</a> •
  <a href="#-contact">Contact</a>
</p>

</div>

---

## 🔬 Overview

**ASTRA** is a pan-cancer histology representation framework designed to support specimen qualification before molecular testing using routine H&E whole-slide images.

The framework integrates three complementary components of specimen suitability:

| | Component | Description |
|:---:|:---|:---|
| **I** | **Molecular preservation** | Histology-based assessment of RNA integrity and related pre-analytical tissue states |
| **II** | **Spatial tumor adequacy** | Tumor localization and quantitative tumor-content estimation |
| **III** | **Specimen identity verification** | Preservation of tissue and disease context across cancer types |

<div align="center">

| Whole-slide images | Patients or donors | Specimen types |
|:---:|:---:|:---:|
| **55,398** | **23,932** | Fresh-frozen & FFPE |

</div>

ASTRA was evaluated across **55,398 whole-slide images from 23,932 patients or donors**, spanning fresh-frozen and formalin-fixed paraffin-embedded (FFPE) specimens from multiple public, research, and clinical cohorts.

---

## 📄 Manuscript

This repository accompanies the manuscript:

> **Routine histology as a computational gatekeeper for specimen qualification before molecular testing: a retrospective multi-cohort study**

The manuscript is currently under preparation/submission.

---

## 📦 Repository Status

This repository currently serves as the project page for ASTRA.

> [!NOTE]
> **Source code, model configurations, inference pipelines, evaluation scripts, and documentation will be released following acceptance of the manuscript.**
>
> Where permitted by the corresponding data-use agreements, pretrained model checkpoints and processed representations required to reproduce the main analyses will also be released.

---

## 🗓️ Planned Release

Following publication, this repository will provide the code, documentation, and resources needed to reproduce the main ASTRA analyses.

The release is expected to include:

- [ ] Model training and inference code
- [ ] Evaluation scripts
- [ ] Analysis pipelines
- [ ] Environment and dependency specifications
- [ ] Example configurations

Additional resources, including model checkpoints and processed features, will be shared where permitted by the corresponding data-use agreements.

---

## 🧭 Study Overview

ASTRA is designed as an upstream computational layer for molecular specimen qualification.

Routine H&E histology is used to recover complementary signals related to:

1. **Molecular preservation**
2. **Spatial tumor adequacy**
3. **Disease and specimen identity**

The framework was evaluated using fresh-frozen and FFPE whole-slide images across the following cohorts:

<div align="center">

| GTEx | TCGA | CHTN | The Ohio State University |
|:---:|:---:|:---:|:---:|
| Public | Public | Research | Independent clinical cohort |

</div>

---

## 🗄️ Data Availability

The study uses a combination of publicly available, controlled-access, and institutional datasets.

**Publicly available resources include:**

| Resource | Access |
|:---|:---|
| **GTEx** | [GTEx Portal](https://gtexportal.org/home/) |
| **The Cancer Genome Atlas (TCGA)** | [NCI Genomic Data Commons](https://portal.gdc.cancer.gov/) |
| **TCGA tumor-segmentation resources used for external evaluation** | [Zenodo](https://zenodo.org/records/18481478) |

> [!IMPORTANT]
> Controlled-access and institutional datasets are subject to their respective access, privacy, and data-governance requirements and are not redistributed through this repository.
>
> CHTN and institutional clinical pathology data are subject to their respective access, privacy, and data-governance requirements and cannot necessarily be redistributed through this repository.

Detailed data-access information will be provided in the manuscript and accompanying documentation.

---

## 💻 Code Availability

The ASTRA source code is not yet publicly available.

Code for model training, inference, downstream evaluation, transcriptomic analyses, and figure generation will be released following acceptance of the manuscript.

---

## 📚 Citation

Citation information will be added upon publication.

---

## ✉️ Contact

**Tianyang Wang**
Department of Pathology, College of Medicine
The Ohio State University Wexner Medical Center
Columbus, Ohio, USA

📧 [Tianyang.Wang@osumc.edu](mailto:Tianyang.Wang@osumc.edu)

---

<div align="center">

### AI4Path Lab

Developed by the **AI4Path Lab** at The Ohio State University.

<sub>Department of Pathology · The Ohio State University Wexner Medical Center</sub>

</div>

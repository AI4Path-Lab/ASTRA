# ASTRA

**Histology-based computational gatekeeper for pre-analytical molecular specimen qualification.**

ASTRA is a pan-cancer histology representation framework designed to support specimen qualification before molecular testing using routine H&E whole-slide images.

The framework integrates three complementary components of specimen suitability:

- **Molecular preservation** — histology-based assessment of RNA integrity and related pre-analytical tissue states
- **Spatial tumor adequacy** — tumor localization and quantitative tumor-content estimation
- **Specimen identity verification** — preservation of tissue and disease context across cancer types

ASTRA was evaluated across **55,398 whole-slide images from 23,932 patients or donors**, spanning fresh-frozen and formalin-fixed paraffin-embedded (FFPE) specimens from multiple public, research, and clinical cohorts.

---

## Manuscript

This repository accompanies the manuscript:

> **Routine histology as a computational gatekeeper for specimen qualification before molecular testing: a retrospective multi-cohort study**

The manuscript is currently under preparation/submission.

---

## Repository status

This repository currently serves as the project page for ASTRA.

**Source code, model configurations, inference pipelines, evaluation scripts, and documentation will be released following acceptance of the manuscript.**

Where permitted by the corresponding data-use agreements, pretrained model checkpoints and processed representations required to reproduce the main analyses will also be released.

---

## Planned release

The public release is expected to include:

- ASTRA model architecture and training code
- Multi-foundation-model feature integration
- Sparse mixture-of-experts contextualization
- Multi-target representation reconstruction
- Slide-level semantic alignment with structured pathology information
- RNA-quality prediction pipelines
- RIN-threshold classification
- Text-guided tumor localization
- Tumor-content estimation
- Pan-cancer specimen-identity evaluation
- Transcriptomic association and gene-set enrichment analysis
- Evaluation and figure-generation scripts
- Environment and dependency specifications
- Example inference configurations

---

## Study overview

ASTRA is designed as an upstream computational layer for molecular specimen qualification.

Routine H&E histology is used to recover complementary signals related to:

1. **Molecular preservation**
2. **Spatial tumor adequacy**
3. **Disease and specimen identity**

The framework was evaluated using fresh-frozen and FFPE whole-slide images across GTEx, TCGA, CHTN, and an independent clinical cohort from The Ohio State University.

---

## Data availability

The study uses a combination of publicly available, controlled-access, and institutional datasets.

Publicly available resources include:

- **GTEx**
- **The Cancer Genome Atlas (TCGA)**
- Publicly released TCGA tumor-segmentation resources used for external evaluation

CHTN and institutional clinical pathology data are subject to their respective access, privacy, and data-governance requirements and cannot necessarily be redistributed through this repository.

Detailed data-access information will be provided in the manuscript and accompanying documentation.

---

## Code availability

The ASTRA source code is not yet publicly available.

Code for model training, inference, downstream evaluation, transcriptomic analyses, and figure generation will be released following acceptance of the manuscript.

---

## Citation

Citation information will be added upon publication.

---

## Contact

**Tianyang Wang**  
Department of Pathology, College of Medicine  
The Ohio State University Wexner Medical Center  
Columbus, Ohio, USA  

Email: Tianyang.Wang@osumc.edu

---

## Laboratory

Developed by the **AI4Path Lab** at The Ohio State University.

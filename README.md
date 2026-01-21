# JC1-Perturb-seq
This repository contains the slides from the first **LatAm Single-Cell Community Journal Club**, focused on **Perturb-seq**, a method that combines pooled CRISPR screens with single-cell RNA sequencing to study gene regulation at single-cell resolution.

## Core Content

### From Arrayed to Pooled CRISPR Screens
Overview of arrayed versus pooled CRISPR screening strategies, highlighting how pooled designs enable scalable, high-throughput functional genomics in a shared cellular environment.

### Mechanisms of CRISPR Perturbation
Introduction to key molecular processes underlying CRISPR knockouts, including non-homologous end joining (NHEJ) and nonsense-mediated decay (NMD), and why transcript levels may not always reflect loss of protein function.

### Perturb-seq Workflow
Conceptual description of the Perturb-seq experimental design:
- Pooled lentiviral delivery of sgRNAs with expressed guide barcodes
- Control of multiplicity of infection to study single and combinatorial perturbations
- Joint profiling of perturbations and transcriptomes using droplet-based scRNA-seq

### Guide Barcode Recovery
Explanation of targeted PCR amplification to enrich guide barcodes, ensuring reliable assignment of perturbations to individual cells.

### Assessing On-Target Effects
How single-cell readouts are used to validate CRISPR perturbations by measuring changes in target gene expression, including interpretation of effect sizes and statistical significance.

### Modeling Perturbation Effects (MIMOSCA)
Introduction to the MIMOSCA framework, which uses regularized linear models to estimate the effects of perturbations and covariates on gene expression, and its extension to capture epistatic interactions.

### Application to Immune Cell Regulation
Summary of a Perturb-seq study in mouse bone marrow–derived dendritic cells, probing transcription factor function during LPS-induced immune activation.

### Regulatory Modules, Programs, and Cell States
How perturbation effects reveal transcription factor modules, gene expression programs, and shifts between immune cell states, enabling reconstruction of gene regulatory networks.

### Genetic Interactions and Feedback Circuits
Analysis of additive and non-additive interactions between transcription factors, uncovering feedback and antagonistic regulatory relationships.

### Strengths, Limitations, and Outlook
Discussion of the main advantages and challenges of Perturb-seq, along with future directions including larger screens, richer covariates, and more flexible modeling approaches.

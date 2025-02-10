# Basic Variant Calling & Visualization Course

Welcome to our one-hour bioinformatics workshop. In this workshop, we will cover:

1. **Basic Variant Calling Concepts and File Formats**  
2. **A Quick Demonstration of Using GATK for Variant Calling** (demonstration only)  
3. **Visualization Using IGV** (hands-on session)

This workshop is designed for undergraduate medical students to introduce some key bioinformatics concepts, offer a guided demonstration of GATK, and provide hands-on experience with the Integrative Genomics Viewer (IGV).

## Workshop Agenda

- **Introduction (5 minutes)**
  - Overview of workshop topics and objectives.
  
- **Section 1: Basic Variant Calling Concepts and File Formats (15 minutes)**
  - Introduction to genetic variants.
  - Overview of common file formats:
    - **FASTA/FASTQ** for raw sequences.
    - **SAM/BAM** for alignment data.
    - **VCF** for variant calls.
  - Key terminologies (e.g., SNPs, indels).

- **Section 2: GATK Demonstration (15 minutes)**
  - Brief introduction to GATK.
  - Walkthrough of a variant calling process:
    - Pre-processing and alignment.
    - Variant calling and filtering.
  - Explanation of key GATK commands (demonstration only – no hands-on).

- **Section 3: Visualization Using IGV (20 minutes)**
  - Overview of IGV.
  - Hands-on session:
    - Load and explore the provided human VCF file (and optional BAM file).
    - Navigate the IGV interface, zoom, and inspect variant annotations.
  - Discussion of how visualization aids in confirming variant calling results.

- **Wrap-Up and Q&A (5 minutes)**
  - Recap of key points.
  - Open session for questions and discussion.

## Repository Structure

This repository contains all the materials and data needed for the workshop:

- **slides/**: Presentation slides for each session.
  - `00_introduction.pdf` – Overview of workshop topics.
  - `01_variant_calling_concepts.pdf` – Detailed concepts and file formats.
  - `02_GATK_demo.pdf` – GATK pipeline demonstration slides.
  - `03_IGV_hands_on.pdf` – Step-by-step guide for the IGV session.
- **data/**: Sample data files for hands-on practice.
  - `human_sample.vcf` – A human VCF file with example variants.
  - `human_sample.bam` (optional) – Corresponding BAM file (if needed for context).
  - `reference.fasta` (optional) – A reference genome file for demonstrations.
- **scripts/**: Example scripts and command outlines.
  - `gatk_variant_calling.sh` – Example shell script demonstrating GATK commands.
  - `igv_session.xml` – Preconfigured IGV session file to load sample data easily.
- **notes/**: Supplementary reading materials and detailed guides.
  - `variant_calling_guide.md` – Extended notes on variant calling concepts.
  - `IGV_tutorial.md` – Detailed IGV user guide for beginners.

## Getting Started

**Clone the Repository**  
Open your terminal and run:
```bash
git clone https://github.com/cheahhl814/Basic-Variant-Calling-Course.git

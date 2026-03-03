# Shraavya M C – Bioinformatics & Genomic Data Engineering

# About Me
I’m an MSc Bioinformatics & Genetic Epidemiology student at Cardiff University. I build reproducible pipelines and tools for NGS data, from QC to variant calling and interactive visualization. My focus is on clean, production-ready workflows that can be scaled and maintained in real-world research or clinical genomics environments.

Key skills:  Python | R | Docker | SLURM | NGS QC & Variant Analysis | Data Visualization | Genomics Pipelines

# Projects

## 1.SARS-CoV-2 Variant Analysis Pipeline  
End-to-end NGS pipeline for variant detection, consensus genome generation, and missense mutation identification.

Developed a reproducible workflow for SARS-CoV-2 variant calling using publicly available sequencing data. The pipeline covers reference download, alignment, variant calling, filtering, consensus generation, and mutation annotation.

**Workflow Includes**
- Reference genome: NC_045512.2  
- SRA data retrieval and FASTQ conversion  
- Alignment using BWA-MEM  
- BAM processing with SAMtools  
- Variant calling with bcftools  
- Quality filtering (QUAL ≥ 30)  
- Consensus genome generation  
- Mutation annotation using Nextclade  
- Extraction of amino-acid substitutions (missense mutations)

**Technical Focus**
- Reproducible bash-based pipeline design  
- Structured variant filtering logic  
- Standardised SARS-CoV-2 mutation annotation  
- Clean project organisation

[View Repository](https://github.com/shraavyamc/sars-cov-2-variant-analysis)


# 2.Automation-Ready NGS Library Preparation Workflow  
Simulation-based workflow design translating manual NGS library preparation into structured, automation-ready logic.
Overview
This project translates a manual NGS library preparation protocol into structured, automation-ready workflow logic.
Instead of focusing on vendor-specific instrument scripts, the aim was to design a reproducible, modular system that could be adapted to high-throughput liquid-handling environments.
The focus is on workflow architecture, QC checkpoints, and scalability.

What I Built
* Structured representation of each library preparation step
* Modular workflow logic simulating step execution
* Integrated QC decision points within the workflow
* Reproducible project directory structure (data, scripts, results, docs)
* Dependency tracking via requirements.txt

Technical Focus
* Workflow abstraction of wet-lab protocols
* Automation-ready step logic
* QC-aware pipeline design
* Reproducible project structuring

Why This Matters
Manual library preparation introduces variability and limits scalability.
This project demonstrates how biological protocols can be translated into structured, programmable systems suitable for automated, high-throughput environments.

GitHub Repository: [View Repository](https://github.com/shraavyamc/automation-ready-ngs-workflow)

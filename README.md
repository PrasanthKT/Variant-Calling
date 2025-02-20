# Variant-Calling

### Authors: Prasanth Kumar Thuthika and Tejaswini Repala

### Title: Somatic Variant Analysis in Mouse Glioma Tumor Samples Using Whole Genome Sequencing Data and Genome Analysis Tool Kit (GATK)

### Objective: This project involves performing a complete NGS pipeline for variant calling, starting from downloading the raw sequencing data to final variant annotation. Additionally, functional enrichment analysis is conducted to understand the biological significance of the variants identified in two types of mouse glioma tumor samples.

### Tools and Dependencies
1. SRA-Toolkit
2. Fastqc
3. Trim Galore
4. BWA
5. Sam-tools
6. GATK
7. Vcf-tools
8. Picard
9. ANNOVAR
10. ClueGO
   
### Input files 
1. SRA IDs: The sequencing data for three samples were downloaded using the SRA Toolkit.
2. Reference Genome: Mus_musculus.GRCm39
3. Annotation File: Mus_musculus.GRCm39.109.gff3

### Execution
1.	Clone this repository.
2.	Execute the scripts provided for each step in the pipeline.
3.	Each script performs specific tasks such as data preprocessing, mapping, variant calling, annotation, and enrichment analysis.

### Output files
1. Intermediate and final output files are generated for each step.
2. The results are summarized in a detailed report, including visualization and interpretation of the findings.

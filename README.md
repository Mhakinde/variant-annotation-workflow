# Variant Annotation Workflow

A complete, beginner-friendly bioinformatics workflow that demonstrates **variant-level analysis and annotation** using **mock VCF data**.  
This project shows how to parse, filter, and visualize genetic variants — a foundational skill in **genomics and computational biology**.

---

## Goal

To demonstrate a **basic variant annotation workflow** using simulated data, walking through every step from **data generation** to **visualization**.

---

## Dataset

**File:** `mock_elaborate.vcf`  
A mock **Variant Call Format (VCF)** file containing simulated variant data with:

- Quality scores  
- Functional impact annotations  
- Gene information  

This ensures the workflow can run **independently** without access to private or sensitive biological data.

---

## Project Outline

The workflow is organized into five core stages:

1. **Create Mock VCF File**  
   Generate a synthetic VCF dataset that mimics real variant data structures.

2. **Load VCF Data**  
   Import the VCF into a `pandas` DataFrame, extracting fields such as chromosome, position, quality, gene, and functional impact.

3. **Filter Variants**  
   Apply filtering rules based on:
   - Minimum quality score threshold  
   - Functional impact category (e.g., HIGH, MODERATE, LOW)

4. **Annotate Variants**  
   Confirm and visualize gene-level annotations for the filtered variants.

5. **Analyze & Visualize**  
   Perform exploratory data analysis:
   - Count variants per gene  
   - Plot top genes with the highest variant frequency using **Matplotlib** and **Seaborn**

---

## How to Run

Follow these simple steps to execute the workflow:

1. **Open in Google Colab**  
   Upload the Jupyter Notebook and the mock VCF file.

2. **Run All Cells Sequentially**  
   Execute each step to reproduce the full variant annotation workflow — from loading the dataset to generating the final visualizations.

---

## Skills Highlighted

| Category | Tools & Concepts |
|-----------|------------------|
| **Programming** | Python |
| **Data Manipulation** | pandas |
| **Data Analysis** | Filtering, Grouping, Aggregation |
| **Genomics Concepts** | Variant data, VCF format, Annotation |
| **Visualization** | Matplotlib, Seaborn |

---

## Result
<img width="1191" height="693" alt="image" src="https://github.com/user-attachments/assets/2f5ded02-aaf9-4045-99e1-f3054cee7c18" />


## Why This Project Matters

Understanding how to process and interpret genetic variants is crucial in:
- Clinical genomics
- Cancer research
- Population genetics
- Personalized medicine

This workflow serves as a foundation for **scaling up to real variant annotation pipelines** using tools like `bcftools`, `Ensembl VEP`, or `ANNOVAR`.

---




### SARS-CoV-2 Variant Analysis:

## Project Overview:
This project performs a comparative genomic analysis of three major SARS-CoV-2 variants: Alpha (B.1.1.7), Delta (B.1.617.2), and Omicron (BA.1). 

Using Python and Biopython, I processed raw NCBI FASTA sequences to calculate key biological metrics and visualized the differences in genomic stability and protein composition.

## Tech Stack
- Language: Python
- Bioinformatics: Biopython (SeqIO, SeqUtils)
- Data Manipulation: Pandas
- Visualization: Matplotlib, Seaborn

## Workflow
1.  Data Curation: High-quality, complete genome sequences were curated from the [NCBI Virus Database](https://www.ncbi.nlm.nih.gov/labs/virus/).
2.  Sequence Processing: 
    - Computed GC Content (%) to estimate genomic stability.
    - Calculated Molecular Weight (Daltons).
    - Translated DNA sequences into Protein sequences (Amino Acids).
3.  Visualization: Generated comparative bar charts and heatmaps to identify structural difference between variants.

## Key Findings
- Stability: The GC content remains conserved (Roughly 37.9%) across all variants, indicating evolutionary constraints on viral stability.
* **Proteomic Shift:** Heatmap analysis reveals distinct amino acid frequency signatures for each variant, reflecting the mutations that drive transmissibility and immune evasion.
* **Structural Dimensions:** Molecular weight analysis confirms slight mass variations consistent with known insertions and deletions (indels) in the Omicron variant.

## How to Run
1.  Clone repository.
2.  Install dependencies:
    ```bash
    pip install biopython pandas seaborn matplotlib
    ```
3.  Open and run `variantanalysis.ipynb` in Jupyter Notebook.

---

*This project demonstrates proficiency in bioinformatics pipelines, biological data handling (FASTA), and scientific visualization.*

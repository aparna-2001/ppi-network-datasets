# PPI Network Datasets

A systematic documentation of Protein-Protein Interaction (PPI) network datasets collected from major biological databases for research purposes.

---

## Overview

Protein-Protein Interaction (PPI) networks represent the physical and functional relationships between proteins in a biological system. This repository documents the collection of PPI datasets from five major curated databases, covering human protein interactions with full provenance, versioning, and citation information.

---

## Databases Covered

| Database | Version | Organism | Approx. Proteins | Approx. Interactions | Evidence Type |
|---|---|---|---|---|---|
| [STRING](https://string-db.org) | v12.0 | Homo sapiens | ~20,000 | ~11,000,000 | Experimental + Predicted |
| [BioGRID](https://thebiogrid.org) | 5.0.257 | Homo sapiens | ~25,000 | ~900,000 | Experimental only |
| [IntAct](https://www.ebi.ac.uk/intact) | Current | Homo sapiens | ~20,000 | ~1,000,000 | Manually curated |
| [MINT](https://mint.bio.uniroma2.it) | Current | Homo sapiens | ~10,000 | ~300,000 | Manually curated |
| [DIP](https://dip.doe-mbi.ucla.edu) | Current | Homo sapiens | ~5,000 | ~25,000 | Experimental only |

---

## Repository Structure

```
ppi-network-datasets/
│
├── README.md                  ← You are here
├── collection_log.xlsx        ← Master log of all datasets
│
├── STRING/
│   └── README.txt             ← Source, version, files, citation
│
├── BioGRID/
│   └── README.txt
│
├── IntAct/
│   └── README.txt
│
├── MINT/
│   └── README.txt
│
└── DIP/
    └── README.txt
```

---

## How to Access the Data

The raw dataset files are **not stored in this repository** as they are already publicly available from the original database websites. This repository documents:

- Exact version and download URL for each dataset
- File names to download
- Evidence type and confidence thresholds
- License and citation information

To download the actual data files, refer to the `README.txt` inside each database folder for the exact URL and file name.

---

## Collection Log

The `collection_log.xlsx` file contains a master record of all datasets including:

- Database name and version
- Download URL
- Date documented
- File names
- Evidence types
- Approximate size (nodes and edges)
- License
- Full citation

---

## Citations

If you use these datasets in your work, please cite the original database papers:

- **STRING v12.0**: Szklarczyk et al., *Nucleic Acids Research*, 2023. DOI: 10.1093/nar/gkac1000
- **BioGRID 5.0**: Oughtred et al., *Protein Science*, 2021. DOI: 10.1002/pro.3978
- **IntAct**: Orchard et al., *Nucleic Acids Research*, 2014. DOI: 10.1093/nar/gkt1115
- **MINT**: Licata et al., *Nucleic Acids Research*, 2012. DOI: 10.1093/nar/gkr930
- **DIP**: Salwinski et al., *Nucleic Acids Research*, 2004. DOI: 10.1093/nar/gkh086

---

## License

This documentation repository is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).  
The original datasets retain their respective licenses as documented in each database's README.

---

## Author

Documented as part of research internship — 2026.

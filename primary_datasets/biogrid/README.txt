DATABASE: BioGRID (Biological General Repository for Interaction Datasets)
================================================================================

Version        : 4.4.212
Organism       : Homo sapiens (Human)
Taxonomy ID    : 9606
Download URL   : https://downloads.thebiogrid.org/BioGRID
Date Documented: (fill in today's date)

FILES TO DOWNLOAD
-----------------
1. BIOGRID-ORGANISM-Homo_sapiens-4.4.212.tab3.zip  → Main interaction file
2. BIOGRID-ORGANISM-Homo_sapiens-4.4.212.mitab.zip → MITAB format (alternative)

FILE FORMAT (TAB3)
------------------
BioGRID Interaction ID | Entrez Gene ID A | Entrez Gene ID B |
BioGRID ID A | BioGRID ID B | Official Symbol A | Official Symbol B |
Synonyms A | Synonyms B | Experimental System | Experimental System Type |
Author | Publication Source | Organism A | Organism B | Throughput |
Score | Modification | Phenotypes | Qualifications | Tags | Source Database

EVIDENCE TYPES INCLUDED
------------------------
- Two-hybrid (Y2H)
- Co-immunoprecipitation (Co-IP)
- Affinity Capture-MS
- Biochemical Activity
- Physical (direct) interactions only

APPROX. SIZE
------------
Nodes (proteins)   : ~25,000
Edges (interactions): ~900,000

LICENSE   : MIT License (free for academic use)
CITATION  : Oughtred et al., "The BioGRID database: A comprehensive biomedical
            resource of curated protein, genetic, and chemical interactions",
            Protein Science, 2021.
            DOI: 10.1002/pro.3978

NOTES
-----
- Gold standard for experimentally validated interactions
- No predicted interactions — experimental evidence only
- Covers genetic interactions in addition to physical PPI
- Well maintained and regularly updated

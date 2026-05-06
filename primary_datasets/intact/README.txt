DATABASE: IntAct (Molecular Interaction Database)
================================================================================

Version        : Current release
Organism       : Homo sapiens (Human)
Taxonomy ID    : 9606
Download URL   : https://ftp.ebi.ac.uk/pub/databases/intact/current/psimitab/
Date Documented: (fill in today's date)

FILES TO DOWNLOAD
-----------------
1. intact.zip       → All interactions in MITAB 2.7 format
2. intact.txt       → Tab-delimited full dataset

FILE FORMAT (MITAB 2.7)
-----------------------
ID(s) interactor A | ID(s) interactor B | Alt. ID(s) A | Alt. ID(s) B |
Alias(es) A | Alias(es) B | Interaction detection method |
Publication 1st author | Publication ID | Taxid interactor A |
Taxid interactor B | Interaction type | Source database |
Interaction identifier | Confidence value

EVIDENCE TYPES INCLUDED
------------------------
- Manually curated from published literature
- Experimental only (no predictions)
- Each interaction linked to specific PubMed publication

APPROX. SIZE
------------
Nodes (proteins)   : ~20,000
Edges (interactions): ~1,000,000+

LICENSE   : Creative Commons CC BY 4.0
CITATION  : Orchard et al., "The MIntAct project — IntAct as a common curation
            platform for 11 molecular interaction databases",
            Nucleic Acids Research, 2014.
            DOI: 10.1093/nar/gkt1115

NOTES
-----
- Hosted by EMBL-EBI (European Bioinformatics Institute)
- Very high precision due to manual curation
- Every interaction traceable to original paper
- Uses PSI-MI standard format (interoperable with other DBs)

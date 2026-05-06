DATABASE: STRING (Search Tool for the Retrieval of Interacting Genes/Proteins)
================================================================================

Version        : v12.0
Organism       : Homo sapiens (Human)
Taxonomy ID    : 9606
Download URL   : https://string-db.org/cgi/download
Date Documented: (fill in today's date)

FILES TO DOWNLOAD
-----------------
1. 9606.protein.links.v12.0.txt.gz         → All interactions + confidence scores
2. 9606.protein.links.detailed.v12.0.txt.gz → Interactions with evidence breakdown
3. 9606.protein.info.v12.0.txt.gz           → Protein names and descriptions

FILE FORMAT
-----------
protein1 | protein2 | combined_score
- Each row = one interaction between two proteins
- Score range: 150–1000 (400+ = medium, 700+ = high confidence)

EVIDENCE TYPES INCLUDED
------------------------
- Experimental (lab validated)
- Text mining (extracted from papers)
- Database (imported from other DBs)
- Co-expression
- Neighborhood / Gene fusion (predicted)

APPROX. SIZE
------------
Nodes (proteins)  : ~20,000
Edges (interactions): ~11,000,000

LICENSE   : Creative Commons CC BY 4.0
CITATION  : Szklarczyk et al., "The STRING database in 2023",
            Nucleic Acids Research, 2023.
            DOI: 10.1093/nar/gkac1000

NOTES
-----
- Most widely used PPI database in research
- Includes both experimental and predicted interactions
- Use confidence threshold ≥ 400 for medium quality
- Use confidence threshold ≥ 700 for high quality only

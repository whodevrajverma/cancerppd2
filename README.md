# CancerPPD2: Anticancer Peptides & Proteins Database

Welcome to the official repository for CancerPPD2, a comprehensive and manually curated database of experimentally validated anticancer peptides (ACPs) and proteins. This resource is designed to support researchers in peptide therapeutics, cancer biology, and computational drug discovery.

Web Server: http://webs.iiitd.edu.in/raghava/cancerppd2/
API Access: https://webs.iiitd.edu.in/raghava/cancerppd2/api/rest.html

## Citation

Chauhan, M., Gupta, A., Tomer, R., & Raghava, G. P. S. (2025).
CancerPPD2: an updated repository of anticancer peptides and proteins.
Database. https://doi.org/10.1093/database/baaf030


## About the Database

CancerPPD2 is an updated version of the original CancerPPD database, significantly expanding the scope and depth of anticancer peptide data. It consolidates scattered experimental findings into a centralized platform, enabling systematic exploration of peptide sequences, structures, modifications, and biological activities.

The database integrates information from:

* Literature (PubMed, Google Scholar, Patent Lens)
* Public repositories (UniProt, PDB, PubChem, ChEMBL)

  
## Key Features

Massive Dataset 

* 6521 total entries
* 5919 anticancer peptides
* 541 anticancer proteins

Extensive Coverage 

* 392 cancer cell lines
* 28 tissue types
* 47 clinical trial-linked entries

Rich Annotations 
Each entry includes:

* Sequence, length, chirality
* Origin and biological source
* Cancer type and cell line
* Assay details and activity (e.g., IC50)

Modified Peptides Focus 

* 781 chemically modified peptides
* 3018 N-/C-terminal modified entries

Structural Data 

* Experimental + predicted structures
* SMILES representations for molecular analysis

## Overview

CancerPPD2 provides experimentally validated data along with:

* Anticancer activity profiles
* Cell line specificity
* Physicochemical and structural properties
* Chemical modifications
* Clinical relevance
* Cross-references (UniProt, DrugBank, PDB)


### Structure Prediction

Structures were obtained or predicted using:

* PDB (experimental structures)
* PEPstrMOD (modified peptides)
* AlphaFold
* I-TASSER


### Improvements Over Previous Version

* ~85% increase in data
* Inclusion of modified peptides
* Integration of REST API
* Enhanced structure prediction coverage
* Clinical trial linkage


### Limitations

* Structural prediction challenges for:
    * Complex chemical modifications
    * Peptides lacking sequence data
* Force-field limitations in prediction tools


## Applications

* Anticancer peptide design
* Machine learning model training
* Structure-function analysis
* Translational oncology research


## Contact & Authors

Prof. Gajendra P. S. Raghava
raghava@iiitd.ac.in
http://webs.iiitd.edu.in/raghava/

Developed at Indraprastha Institute of Information Technology (IIIT Delhi), India

## License

This database is distributed under the
Creative Commons Attribution License (CC BY 4.0)


## Acknowledgements

Supported by:

* AICTE
* DST-INSPIRE
* DBT

We acknowledge all researchers whose work contributed to this dataset.

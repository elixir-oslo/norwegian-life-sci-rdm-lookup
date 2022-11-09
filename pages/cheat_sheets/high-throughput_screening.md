---
title: High-Throughput Screening Cheat Sheet
search_exclude: true
contributors: [Federico Bianchini, Alexandra Gade]
page_id: [HTS]
---

## High-throughput screening

### Description


### Type of data/experiments/methods
#### Type 1
- [Tab-separated values (TSV)](https://fairsharing.org/bsg-s001547)
- [Comma-separated values (CSV)](https://fairsharing.org/bsg-s001546)

#### multidimensional image data
[Open Microscopy Environment - Tagged Image File Format (OME-TIFF)](https://fairsharing.org/bsg-s000537)

#### Flow Cytometry Data
[Flow Cytometry Data File Standard (FCS)](https://fairsharing.org/bsg-s000565)

### Metadata Standards
#### General
- Ontologies:
  - [IUPAC Chemical Identifier (InChI) for chemical structures](https://fairsharing.org/bsg-s000648)
- Standards:
  - [Minimum Information about Flow Cytometry (MIFlowCyt)](https://doi.org/10.25504/FAIRsharing.kcnjj2)
  - [Minimal information for Chemosensitivity Assays (MICHA)](https://fairsharing.org/1435)

#### EU Openscreen
- Ontologies:
  - [BioAssay Ontology for assays](https://fairsharing.org/bsg-s002687)
  - [Cellosaurus Ontology for cell lines](https://doi.org/10.25504/FAIRsharing.hkk309)
  - [BRENDA Tissue/Enzyme Source Ontology for tissues](https://fairsharing.org/bsg-s000063)
  - [NCBI Taxonomy for organisms](https://fairsharing.org/bsg-s000154)
  - [Reactome for biological pathways](https://doi.org/10.25504/FAIRsharing.tf6kj8)
  - [Gene Ontology as basis for ChemBl drug target subset](https://fairsharing.org/bsg-s000089)
  - [Units Ontology](https://fairsharing.org/bsg-s002611)
  
#### Recommended Metadata for Biological Images (REMBI)
- Ontologies:
  - [EDAM Bioimaging Ontology (EDAM-BIOIMAGING)](https://doi.org/10.25504/FAIRsharing.g593w1)
  - [Experimental Factor Ontology(EFO)](https://doi.org/10.25504/FAIRsharing.1gr4tz)
  - [NCBI Taxonomy (NCBITAXON)](https://doi.org/10.25504/FAIRsharing.fj07xj)
  - [Biological Imaging methods Ontology (FBbi)](https://doi.org/10.25504/FAIRsharing.ny3z9j)
  - [Open Microscopy Environment Ontology(OME-OWL)](https://fairsharing.org/350)
- [FAIRsharing entry link](https://fairsharing.org/bsg-s001615)



### Sources for Reusable Data
#### [PubChem BioAssay](https://pubchem.ncbi.nlm.nih.gov/)
- Small-molecule and RNAi screening data
- [Citation guidelines (No usage license)](https://pubchemdocs.ncbi.nlm.nih.gov/citation-guidelines)
- Identifiers
- [How to access BioAssay data](https://pubchemdocs.ncbi.nlm.nih.gov/bioassays)

#### [ChEMBL](https://www.ebi.ac.uk/chembl/)
- Manually curated database of bioactive drug-like small molecules
- [CC BY-SA 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/)
- Identifiers:
  - Depositor unique identifier (ChEMBLID) for compounds, targets, assays, documents, tissues and cell types in ChEMBL 
- Access via [web interface](https://www.ebi.ac.uk/chembl/g/#search_results/all) or [download](https://chembl.gitbook.io/chembl-interface-documentation/downloads) data directly

### [European Chemical Biology Database (ECBD)](https://ecbd.eu/)
- Small molecule screening data generated within the [EU-OPENSCREEN](https://www.eu-openscreen.eu/) network
- [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)
- Identifiers: 
  - Depositor unique identifier (EOS#) for assays, compounds, and targets
  - InChIKey as unique compound identifier
  - Additional identifiers for compounds: PubChem CID, MolPort number, and if available: ZINC, Mcule, eMolecules identifiers
- [Search](https://ecbd.eu/assays/) the database from a web interface or [download](https://ecbd.eu/download) the data directly

### Storage and Computing
<!--Add information about e.g. NeLS-->

### Data Deposition Repository
#### PubChem BioAssay
- [Data submission policy (no license available)](https://pubchemdocs.ncbi.nlm.nih.gov/data-submission-policy)
- Identifiers
- [Submit chemical structures, annotations, and bioassay results](https://pubchemdocs.ncbi.nlm.nih.gov/submissions-getting-started)
- [Embargo for up to 1 year](https://pubchemdocs.ncbi.nlm.nih.gov/delay-publication-release)

#### ChEMBL
- [CC BY-SA 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/)
- Identifiers
- Submission by e-mail request to [chembl-help@ebi.ac.uk](mailto:chembl-help@ebi.ac.uk)
  - Data sets deposited in ChEMBL are incorporated into PubChem
  - [Check the ChEMBL Loader documentation if your data are suitable for deposition](https://chembl.gitbook.io/chembl-loader/)
- Embargo unknown

### Ethics and Regulations
<!--Add information about laws and policies in Norway for relevant data types-->
#### Data Type Name (e.g. Human Data) 
- Reidentifiable

#### Data Type Name (e.g. Biodiversity Data) 
- Regulations

### Services in Norway
<!--Add one line description-->
#### RDM Services
- Name
- Description of services offered
- Contact Information / Website Link

#### Scientific Services
- Name
  - Description of services offered
  - Contact Information / Website Link
- Name
  - Description of services offered
  - Contact Information / Website Link

### Useful Links
<!--Add a list of relevant external/global tools-->
[NOR-Openscreen Website](https://openscreen.no)
[UniChem tool for converting molecule identifiers](https://www.ebi.ac.uk/unichem/)

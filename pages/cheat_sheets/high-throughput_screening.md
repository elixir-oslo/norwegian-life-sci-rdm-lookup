---
title: High-Throughput Screening Cheat Sheet
search_exclude: true
contributors: [Federico Bianchini, Alexandra Gade]
page_id: [HTS]
---

## High-throughput screening

### Description
<!--Write about the domain, its purpose/use, and 2-3 lines on data management challenge when it comes to said domain research in Norway-->
High-throughput screening (HTS) involves automated testing of chemical and/or biological compounds against a target, typically biological. The process is automated through the use of microwell plates and/or microarrays, robotics, liquid handling, data processing, and sensitive detection systems. The detection systems are typically optical plate reader data, imaging data, or flow cytometry data.  
Screening data generated in Norway are collected using a large quantity of compounds from diverse suppliers that are tested against a variety of targets in many different assay types using various detection methods. Such heterogeneities make unifying HTS data generated in Norway an ongoing challenge.

### Type of data/experiments/methods
#### Plate reader data as text files
- [Tab-separated values (TSV)](https://fairsharing.org/bsg-s001547)
- [Comma-separated values (CSV)](https://fairsharing.org/bsg-s001546)

#### Multidimensional image data (High content screening - HCS)
[Open Microscopy Environment - Tagged Image File Format (OME-TIFF)](https://fairsharing.org/bsg-s000537)

#### Flow Cytometry Data
- [Flow Cytometry Data File Standard (FCS)](https://fairsharing.org/bsg-s000565)
- [XML-based gating definitions (Gating-ML)](https://doi.org/10.25504/FAIRsharing.qpyp5g)


### Metadata Standards
#### Standards
- [Minimal information for Chemosensitivity Assays (MICHA)](https://fairsharing.org/1435)
- [Recommended Metadata for Biological Images (REMBI)](https://fairsharing.org/bsg-s001615)
- [Minimum Information about Flow Cytometry (MIFlowCyt)](https://doi.org/10.25504/FAIRsharing.kcnjj2)

#### Ontologies
- General:
  - [IUPAC Chemical Identifier (InChI) for chemical structures](https://fairsharing.org/bsg-s000648)
  - [Units Ontology (UO)](https://fairsharing.org/bsg-s002611)
  - [NCBI Taxonomy (NCBITAXON)](https://doi.org/10.25504/FAIRsharing.fj07xj)
  - [Experimental Factor Ontology (EFO)](https://doi.org/10.25504/FAIRsharing.1gr4tz)
- EU-Openscreen-specific:
  - [BioAssay Ontology (BAO) for assays](https://fairsharing.org/bsg-s002687)
  - [Cellosaurus Ontology for cell lines](https://doi.org/10.25504/FAIRsharing.hkk309)
  - [BRENDA Tissue/Enzyme Source (BTO) Ontology for tissues](https://fairsharing.org/bsg-s000063)
  - [Reactome for biological pathways](https://doi.org/10.25504/FAIRsharing.tf6kj8)
  - [Gene Ontology (GO) as basis for ChemBl drug target subset](https://fairsharing.org/bsg-s000089)
- Imaging-specific:
  - [EDAM Bioimaging Ontology (EDAM-BIOIMAGING)](https://doi.org/10.25504/FAIRsharing.g593w1)
  - [Biological Imaging methods Ontology (FBbi)](https://doi.org/10.25504/FAIRsharing.ny3z9j)
  - [Open Microscopy Environment Ontology(OME-OWL)](https://fairsharing.org/350)
- Flow Cytometry-specific:
  - [Ontology for Biomedical Investigations (OBI)](https://doi.org/10.25504/FAIRsharing.284e1z)
  - [Cell Ontology (CL) for cell types](https://doi.org/10.25504/FAIRsharing.j9y503)


### Sources for Reusable Data
#### [PubChem](https://pubchem.ncbi.nlm.nih.gov/) BioAssay
- Small-molecule and RNAi screening data
- [Citation guidelines (No usage license)](https://pubchemdocs.ncbi.nlm.nih.gov/citation-guidelines)
- [Identifiers](https://pubchemdocs.ncbi.nlm.nih.gov/data-organization):
  - Resource unique identifiers for single chemical structures (CID), substances (SID), and assays (AID)
  - Other identifiers:
    - Targets (genes/proteins): NCBI Gene IDs/NCBI Protein accession IDs 
    - Taxonomy: NCBI Taxonomy ID, the common name, or scientific name of an organism
    - [Pathways](https://pubchem.ncbi.nlm.nih.gov/sources/#type=Pathways): integrated from various sources and identified by SOURCE:ExternalID
    - Patents: for chemicals mentioned in a patent, unique patents identified by patent number (e.g. US5969156)
- [How to access BioAssay data](https://pubchemdocs.ncbi.nlm.nih.gov/bioassays)

#### [ChEMBL](https://www.ebi.ac.uk/chembl/)
- Manually curated database of bioactive drug-like small molecules
- [CC BY-SA 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/)
- Identifiers:
  - Resource unique identifier (ChEMBLID) for compounds, targets, assays, documents, tissues and cell types in ChEMBL
  - ChEMBLIDs for molecules can be converted to many other identifiers via [UniChem](https://www.ebi.ac.uk/unichem/)
- Access via [web interface](https://www.ebi.ac.uk/chembl/g/#search_results/all) or [download](https://chembl.gitbook.io/chembl-interface-documentation/downloads) data directly

#### [European Chemical Biology Database (ECBD)](https://ecbd.eu/)
- Small molecule screening data generated within the [EU-OPENSCREEN](https://www.eu-openscreen.eu/) network
- [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)
- Identifiers: 
  - Resource unique identifier (EOS#) for assays, compounds, and targets
  - InChIKey as unique compound identifier
  - Additional identifiers for compounds: PubChem CID, MolPort number, and if available: ZINC, Mcule, eMolecules identifiers
- [Search](https://ecbd.eu/assays/) the database from a web interface or [download](https://ecbd.eu/download) the data directly

### Storage and Computing
<!--Add information about e.g. NeLS, update this section when SEEK is deployed for NOR-OS metadata?-->
HTS data collected in Norway are analyzed and stored at individual screening sites in NOR-Openscreen.  
Metadata for screens run in Norway will be compiled into a central database.

### Data Deposition Repository
#### PubChem BioAssay
- [Data submission policy (no license available)](https://pubchemdocs.ncbi.nlm.nih.gov/data-submission-policy)
- Identifiers:
  - CID for unique chemical structures
  - SID assigned to each record (substance or annotation) submitted, can be associated to multiple CIDs
  - Experiments submitted on different substances are assigned unique BioAssay identifiers (AID)
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
#### Patient Data
- Preapproval for medicinal/health-related research projects from the [Regional Ethics Committee](https://rekportalen.no/#hjem/home) is required
- Projects handling personal data must apply to [NSD](https://www.nsd.no/)
- Otherwise data must be fully anonymized - neither directly or indirectly identifiable to an individual

### Services in Norway
<!--Add one line description-->
#### RDM Services
- Name
- Description of services offered
- Contact Information / Website Link

#### Scientific Services
- Chemical Biology Platform at NCMM/UiO
  - Chemical biology and high-throughput screening services
  - [mailto:chembio@ncmm.uio.no](chembio@ncmm.uio.no) / [Website Link](https://www.med.uio.no/english/research/core-facilities/chemical-biology-screening/)
- Biophysics, structural biology, and screening (BiSS) at UiB
  - Core facility for studing the interactions of small molecules with macromolecules, protein biophysics, and for crystallization.
  - [mailto:biss@uib.no](biss@uib.no) / [Website Link](https://www.uib.no/en/rg/biss)
- High throughput Screening at SINTEF Biotechnology and Nanomedicine
  - High-throughput screening services specialized in microbial cultivation, enzyme evolution, and mass spectrometry
  - [Geir Klinkenberg](geir.klinkenberg@sintef.no) / [Website Link](https://www.sintef.no/en/expertise/sintef-industry/biotechnology-and-nanomedicine/high-throughput-screening/)
- Marine Bioprospecting (Marbio) at UiT
  - Analytical platform for natural products
  - [mailto:jeanette.andersen@uit.no](jeanette.andersen@uit.no) / [Website Link](https://en.uit.no/forskning/forskningsgrupper/gruppe?p_document_id=380005)

### Useful Links
<!--Add a list of relevant external/global tools-->
[NOR-Openscreen Website](https://openscreen.no)
[UniChem tool for converting molecule identifiers](https://www.ebi.ac.uk/unichem/)
[Create a data management plan for your HTS project](https://elixir-no.ds-wizard.org/projects/create/from-template)

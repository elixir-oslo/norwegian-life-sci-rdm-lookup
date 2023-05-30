---
layout: page
type: cheat_sheet
title: Light microscopy
search_exclude: false
contributors: [Xian Hu, Korbinian Bösl]
page_id: light_microscopy
description: Data from different light microscopy technologies
affiliations: ["Norwegian advanced light microscopy imaging network (NALMIN)"]
sidebar: cheat_sheets
dsw:
- name: "Light microscopy"
  uuid: d8594508-6684-4032-ae7e-07ead4ff078d
related_pages:
  cheat_sheet: [HTS]
---

## Optical Light Microscopy
<!--Example: High-Throughput Screening-->


### Description
Light microscopy technologies are widely adopted in modern biological and medical research projects. As the field grows, the number of imaging techniques, processing methods as well as the size of the data increases. To avoid loss or degradation of data in the late stage of a project period and after the end of the project, data management of light microscopy data needs to be considered, planned and executed throughout the data life-cycle.

### Type of data/experiments/methods

#### OME-tiff
- [OME-tiff](https://doi.org/10.25504/FAIRsharing.cq8tg2)
- Open Format
- Currently preferred format

#### OME-NGFF
- [OME-NGFF](https://fairsharing.org/3887)
- Open Format
- Upcoming
- Optimized for (cloud) object storage and partial transfer

#### HDF5
- [HDF5 Library and File format](https://www.hdfgroup.org/solutions/hdf5)
- Open Format

#### [CZI-zeiss](https://www.zeiss.com/microscopy/en/products/software/zeiss-zen/czi-image-file-format.html)
- Zeiss
- Proprietary format

#### LIF
- Leica
- Propriertary format

#### ND2
- Nikon
- Propriertary format

#### PNG, JPEG, TIFF
- Lossy formats
- *Not* recommended for storing microscopy image

### Metadata Standards

#### [Recommended Metadata for Biological Images (REMBI)](https://fairsharing.org/bsg-s001615)
- [REMBI reference](https://www.ebi.ac.uk/bioimage-archive/rembi-model-reference/)

#### Ontologies
- General:
  - [IUPAC Chemical Identifier (InChI) for chemical structures](https://doi.org/10.25504/FAIRsharing.ddk9t9)
  - [Units Ontology (UO)](https://doi.org/10.25504/FAIRsharing.mjnypw)
  - [NCBI Taxonomy (NCBITAXON)](https://doi.org/10.25504/FAIRsharing.fj07xj)
  - [Experimental Factor Ontology (EFO)](https://doi.org/10.25504/FAIRsharing.1gr4tz)
  - [EDAM Bioimaging Ontology (EDAM-BIOIMAGING)](https://doi.org/10.25504/FAIRsharing.g593w1)
  - [Biological Imaging methods Ontology (FBbi)](https://doi.org/10.25504/FAIRsharing.ny3z9j)
  - [Open Microscopy Environment Ontology(OME-OWL)](https://fairsharing.org/350)

### Sources for Reusable Data

#### [IDR](https://idr.openmicroscopy.org/)
- A public repository for reference imaging datasets. Research community can submit search and access the raw datasets and analyses.
- Usually [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) or [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Identifiers:
  - DOI and accession number for all datasets
  - See also: [Ontologies](#### Ontologies)
  - Other identifiers: Targets (genes/proteins): Gene IDs/UniProt Protein accession IDs
- Access possible through [API](https://idr.openmicroscopy.org/about/api.html) and [direct download](https://idr.openmicroscopy.org/about/download.html), you can run [image analysis workflows](https://training.galaxyproject.org/training-material/topics/imaging/) directly on IDR datasets on [usegalaxy.no](https://usegalaxy.no) using the [IDR download tool](https://usegalaxy.eu/root?tool_id=toolshed.g2.bx.psu.edu/repos/iuc/idr_download_by_ids/idr_download_by_ids/)

#### [BioImageArchive]((https://www.ebi.ac.uk/bioimage-archive/))
- Free, publicly available online resource which stores and distributes biological images
- Some accessions have individual licenses - these are explicitly stated on the page for that accession. Where no license is stated, data is available under the [EMBL-EBI Terms of Use](https://www.ebi.ac.uk/about/terms-of-use/)
- Identifiers:
  - BioImage Archive accession number
  - DOI for selected datasets
  - See also: [Ontologies](#### Ontologies)
  - Other identifiers: Targets (genes/proteins): Gene IDs/UniProt Protein accession IDs
- Access possible through [webinterface, direct download and API](https://www.ebi.ac.uk/biostudies/help)

### Storage and Computing
<!--Add information about e.g. NeLS-->
- [Nels](https://nels.bioinfo.no/pages/user-terms.xhtml)
- [usegalaxy.no](https://usegalaxy.no) can be used to run [image analysis workflows](https://training.galaxyproject.org/training-material/topics/imaging/)
- [UiO Storage Hotel](https://www.uio.no/english/services/it/store-collaborate/storage-hotel/)

### Data Deposition Repository

#### [IDR](https://idr.openmicroscopy.org/)
- usually [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) or [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Identifiers:
  - DOI and accession number for all datasets
  - See also: [Ontologies](#### Ontologies)
- [How to submit to IDR](https://idr.openmicroscopy.org/about/submission.html)
- [Scheduling a release date is possible with limitations](https://idr.openmicroscopy.org/about/faq/)

#### BioImageArchive
- Specification of license possible - usually [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) or [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Where no license is stated, data is available under the [EMBL-EBI Terms of Use](https://www.ebi.ac.uk/about/terms-of-use/)
- Identifiers:
  - BioImage Archive accession number
  - DOI for selected datasets
  - ORCID for authors
  - See also: [Ontologies](#### Ontologies)
  - Other identifiers: Targets (genes/proteins): Gene IDs/UniProt Protein accession IDs
- [How to submit to BioImageArchive](https://www.ebi.ac.uk/bioimage-archive/)
- [Embargo until publication possible](https://www.ebi.ac.uk/bioimage-archive/help-faq/)


### Services in Norway
<!--Add one line description-->
#### RDM Services
- For help with bioimage data management please contact [ELIXIR Norway](https://elixir.no/helpdesk) or [NALMIN Norway](https://nalmin.no/index.php/data-management/)

#### Scientific Services
- [The Imaging Facilities of the OuS Institute for Cancer Research](https://ous-research.no/microscopy/)
- [Oslo NorMIC Imaging Platform at UiO](https://www.mn.uio.no/ibv/english/research/infrastructure/facilities/life-science/imaging/normic/)
- [Molecular Imaging Center (MIC) at UiB](https://www.uib.no/en/rg/mic)
- [Cellular & Molecular Imaging Core Facility (CMIC) at NTNU](https://www.ntnu.edu/mh/cmic)
- [Center for Advanced Microscopy (CAM) at NTNU](https://www.ntnu.edu/nv/cam)
- [The Advanced Microscopy Core Facility (AMCF) at UiT](https://en.uit.no/infrastruktur/enhet?p_document_id=701241)

### Reference and Useful Links
<!--Add a list of relevant external/global tools-->
- [RDMkit: Bioimaging data](https://rdmkit.elixir-europe.org/bioimaging_data)
- [Global BioImaging: Data Management](https://globalbioimaging.org/international-training-courses/repository/image-data)
- [Protocol for storing correlative microscopy imaging data](https://star-protocols.cell.com/protocols/374)

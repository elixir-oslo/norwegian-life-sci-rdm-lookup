---
layout: page
type: cheat_sheet
title: High-Throughput Screening Cheat Sheet
search_exclude: false
contributors: [Xian Hu, Korbinian Bösl]
page_id: HTS
description: Data from different light microscopy technologies
affiliations:
sidebar: cheat_sheets
---

## Optical Light Microscopy
<!--Example: High-Throughput Screening-->


### Description
Light microscopy technologies has been widely adopted to mordern biological and medical research projects. As the field grows, the number of imaging technique, processing method as well as the size of the data increases every day. To avoid chaos in the late stage of project period, the data management of light microscopy data needs to be considered, planed and executed throughout the data life cycle.


### Type of data/experiments/methods
#### CZI
- Zeiss [CZI-zeiss](https://www.zeiss.com/microscopy/en/products/software/zeiss-zen/czi-image-file-format.html)
- Proprietary format

#### LIF
- Leica
- Propriertary format

#### ND2
- Nikon
- Propriertary format

#### OME-tiff
- [OME-tiff](https://doi.org/10.25504/FAIRsharing.cq8tg2)
- Open Format
- currently preferred format

#### OME-NGFF
- [OME-NGFF](https://fairsharing.org/3887)
- Open Format
- upcoming
- optimized for (cloud) object storage and partial transfer

#### HDF5
- [HDF5 Library and File format](https://www.hdfgroup.org/solutions/hdf5)
- Open Format

#### PNG, JPEG, TIFF
- Lossy formats
- Not recommended for storing microscopy image

### Metadata Standards

#### REMBI
- Current status of BioImaging Data Management
- (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8606015/)

#### EDAM BioImaging Ontology
- Controlled vocabularies
- (https://github.com/edamontology/edam-bioimaging)

### Sources for Reusable Data

#### IDR
- A public repository for reference imaging datasets. Research community can submit search and access the raw datasets.
- Standard License
- Identifiers
- [How to access](https://idr.openmicroscopy.org/)

#### BioImageArchive
- A public repository for imaging datasets. Research community can submit search and access the raw datasets.
- Identifiers
- [How to access](https://www.ebi.ac.uk/bioimage-archive/)

### Storage and Computing
<!--Add information about e.g. NeLS-->
- [Nels](https://nels.bioinfo.no/pages/user-terms.xhtml)
- [Storage Hotel](https://www.uio.no/english/services/it/store-collaborate/storage-hotel/)

### Data Deposition Repository

#### IDR
- A public repository for imaging datasets from research data sets. Research community can submit search and access the raw datasets.
- Standard License
- Identifiers
- [How to submit to IDR ](https://idr.openmicroscopy.org/about/submission.html)

#### BioImageArchive
- A public repository for imaging datasets. Research community can submit search and access the raw datasets.
- Identifiers
- [How to submit to BioImageArchive ](https://www.ebi.ac.uk/bioimage-archive/)

### Ethics and Regulations
<!--Add information about laws and policies in Norway for relevant data types-->
- In Norway, same rules on research data applies to the handling of imaging data.

### Services in Norway
<!--Add one line description-->
- The subproject BioMedData under [Elixir Norway](https://elixir.no/organization/biomeddata) together with [NALMIN Norway](https://nalmin.no/) provide consultation on request regards imaging data management

### Reference and Useful Links
<!--Add a list of relevant external/global tools-->
- [Global BioImaging Data Management](https://globalbioimaging.org/international-training-courses/repository/image-data)
- [Protocol for storing correlative microscopy imaging data](https://star-protocols.cell.com/protocols/374)

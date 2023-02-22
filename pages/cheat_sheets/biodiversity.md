---
layout: page
title: Species occurrence data
type: cheat_sheet
search_exclude: false
contributors: [Michal Torma, Nazeefa Fatima]
page_id: biodiversity
description: Biodiversity data about species recorded in space and time.
affiliations: ["Norwegian node of the Global Biodiversity Information Facility (GBIF-NO)"]
sidebar: cheat_sheets
dsw:
- name: "Bio occurrence data"
  uuid: 8201e668-3b6e-499d-b279-82932d5510c7
---

### Description
Biodiversity data is data about species recorded in space and time. Such data is useful for the modeling of future species distribution, impact of climate change etc. Many natural studies inadvertently collect biodiversity data in different shape and form therefore it is often challenging to reshape the data into standardised form.

### Type of data/experiments/methods
All publishable biodiversity data should follow [Darwin Core](https://dwc.tdwg.org/) data standard. Data in spreadsheets or databases can easily be converted to the Darwin Core standard using the IPT (Integrated Publishing Toolkit).
This standard supports the following data structures:

#### Occurrence data
- [Learn about how to publish occurence data](https://ipt.gbif.org/manual/en/ipt/latest/occurrence-data)

#### Sampling event data
- [How to transform data to sampling event data](https://ipt.gbif.org/manual/en/ipt/latest/sampling-event-data)

#### Checklist data
- [How to prepare data in table structures](https://ipt.gbif.org/manual/en/ipt/latest/checklist-data)

### Metadata Standards
#### Ecological Metadata Language (EML)
Metadata standard used is [EML](https://eml.ecoinformatics.org/). To create metadata for your dataset, you will fill in a form during the IPT dataset publication process.

#### Ontologies
EML accepts various vocabularies, some examples include:
- [ECSO (Ecosystem Ontology)](https://doi.org/10.25504/FAIRsharing.a4ww64)
- [EnvO (Environment Ontology)](https://doi.org/10.25504/FAIRsharing.azqskx)
- [NCBI Taxonomy](https://doi.org/10.25504/FAIRsharing.fj07xj)
- [OBOE (The Extensible Observation Ontology)](https://doi.org/10.25504/FAIRsharing.5970hq)
- [ROR (Research Organization Registry)](https://doi.org/10.25504/FAIRsharing.1jKfji)

### Sources for Reusable Data
#### [GBIF](https://gbif.org)
- All published biodiversity data, from different sources, is available through [GBIF](https://gbif.org) portal.  
- [Data user guidelines](https://www.gbif.org/terms/data-user)
- Identifiers:
  - Filtered datasets are provided with unique DOIs for tracking data use.
- It is also possible to use the [GBIF API](https://www.gbif.org/developer/summary) with [R](https://cran.r-project.org/web/packages/rgbif/index.html) or [Python](https://www.gbif.org/tool/OlyoYyRbKCSCkMKIi4oIT/pygbif-gbif-python-client) to retrieve data.

### Storage and Computing
Storage is provided by individual Integrated Publishing Toolkit (IPT) providers.

### Data Deposition Repository
File formats that are supported by IPT are:
- Plain text formats
  - [Tab-separated values (TSV)](https://doi.org/10.25504/FAIRsharing.a978c9)
  - [Comma-separated values (CSV)](https://doi.org/10.25504/FAIRsharing.1943d4)
  - Open formats
- XLSX and XLS
- SQL databases (e.g. MariaDB, PostgreSQL)

#### GBIF Norway IPT
- [GBIF Norway's IPT Homepage](https://ipt.gbif.no)
- [Contact GBIF](mailto:helpdesk@gbif.no) to get user credentials
- Post on the [GBIF Norway GitHub issue list](https://github.com/gbif-norway/helpdesk/issues) for general questions about data publication. You can also see questions others have posted here.

### Useful Links
<!--Add a list of relevant external/global tools-->
- In addition to the GBIF Norway HelpDesk at GitHub, there is a [global GBIF GitHub issue list](https://github.com/gbif/ipt/issues?q=) for data publication and IPT usage questions
- [Darwin core extensions](https://rs.gbif.org/extension/)
- [Earth BioGenome Project (EBP) Norway](https://www.ebpnor.org/english/)
- [European Reference Genome Atlas (ERGA)](https://www.erga-biodiversity.eu/)

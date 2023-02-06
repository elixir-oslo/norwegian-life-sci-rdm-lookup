---
layout: page
type: cheat_sheet
title: Next generation sequencing data
search_exclude: false
contributors: [Federico Bianchini, Korbinian Bösl, Nazeefa Fatima]
page_id: sequencing
description: Next generation sequencing data
affiliations: ["Norwegian consortium for sequencing and personalized medicine (NorSeq)"]
sidebar: cheat_sheets
dsw:
- name: "Non-quantitative next generation sequencing of non-human data"
  uuid: 5363b48a-83a0-4153-bca8-311408e33e97
- name: "Non-quantitative next generation sequencing of human data"
  uuid: 27a7fdf2-4b40-4f13-af6f-227b8eb94b48  
---

## Next generation sequencing of non-human data

### Description

### Type of data/experiments/methods
<!---When mentioning file format, it would be useful to mention format type -->

#### Sequencing data
- [FASTQ format](https://doi.org/10.25504/FAIRsharing.r2ts5t)
- [Sequence Alignment Map (SAM) format](https://doi.org/10.25504/FAIRsharing.k97xzh)
- [Binary Alignment Map (BAM) format](https://doi.org/10.25504/FAIRsharing.hza1ec)

#### Variation data
- [Variant Call Format (VCF)](https://doi.org/10.25504/FAIRsharing.cfzz0h)

### Metadata Standards
#### [Minimum Information about any (x) Sequence (MIxS)](https://doi.org/10.25504/FAIRsharing.9aa0zp)
The minimum information about any (x) sequence (MIxS) is an overarching framework of sequence metadata
- Ontologies:
  - [Experimental Factor Ontology (EFO)](https://doi.org/10.25504/FAIRsharing.1gr4tz)
  - [NCBI Taxonomy (NCBITAXON)](https://doi.org/10.25504/FAIRsharing.fj07xj)
  - [Phenotypic QualiTy Ontology (PATO)](https://doi.org/10.25504/FAIRsharing.ezwdhz)
  - [Disease Ontology (DOID)](https://doi.org/10.25504/FAIRsharing.8b6wfq)
  - [Envcironment Ontology ENVO)](https://doi.org/10.25504/FAIRsharing.azqskx)
  - [Plant Ontology (PO)](https://doi.org/10.25504/FAIRsharing.3ngg40)
- Controlled vocabularies:
  - [Chemical Entities of Biological Interest ChEBI)](https://doi.org/10.25504/FAIRsharing.62qk8w)

#### [European Variation Archive metadata template](https://www.ebi.ac.uk/eva/files/EVA_Submission_template.V1.1.4.xlsx)
This standard is required for submission of variation data on [EVA](https://www.ebi.ac.uk/eva/)

### Sources for Reusable Data
#### [Ensemlb](https://doi.org/10.25504/FAIRsharing.fx0mw7)
- Ensembl creates, integrates and distributes reference datasets and analysis tools that enable genomics.
- Data is open-access and can be downloaded free of charge ([disclaimer](https://www.ensembl.org/info/about/legal/index.html))
- Identifiers: [Ensembl stable ID](https://www.ensembl.org/Help/Faq?id=488)
- How to access: account (username and password)

### Storage and Computing
#### [ELIXIR Norway](https://elixir.no) infrastructures
- [The Norwegian e-infrastructure for life sciences (NeLS)](https://nels.bioinfo.no)
  - Free of charge allocation of 1–10 TB disk space
  - Storing active research data for analysing and processing
  - Granular data sharing with collaborators
- [National instance of Galaxy](https://usegalaxy.no/)
  - Provides ~2000 tools data processing and analyses
  - Create, customise and reuse workflows
  - Data stored in NeLS is readily available for processing on Galaxy
    - Data redundancy is avoided
- StoreBioInfo
  - Access through the [NeLS portal]((https://nels.bioinfo.no))
  - Long term (until the end of a project) storage of non-active data
  - Store up to 10 GB of data free of charge

If your data is produced by the [NorSeq core facilities](https://www.norseq.org/),
direct upload to the ELIXIR Norway storage infrastructures is possible. Non-sensitive data
will be uploaded on [NeLS](https://nels.bioinfo.no) following
[these procedures](https://elixir.no/Services-bak/data_produced_NorSeq).
If your data has been produced by another sequence provider,
follow [these instructions](https://elixir.no/Services-bak/non-norseq-data) to request a project on NeLS.
#### [Sigma2](https://www.sigma2.no/) ([Sikt](https://sikt.no/)) infrastructures
- [High-performance computing](https://www.sigma2.no/high-performance-computing)
  - [Overview](https://documentation.sigma2.no/hpc_machines/hardware_overview.html) of available machines
- [NIRD data storage](https://www.sigma2.no/data-storage)
  - Storage of active data for processing and analysis
  - Granular data sharing with collaborators
- [NIRD Service Platform](https://www.sigma2.no/nird-service-platform)
  - Run cloud services including tools for processing and visualisation.
  - The services can be used to consume data without moving it from the NIRD storage location.

### Data Deposition Repository
#### European Nucleotide Archive (ENA)
- [Homepage](https://www.ebi.ac.uk/ena/browser/)
- [DOI(FAIRsharing)](https://doi.org/10.25504/FAIRsharing.dj8nt8)
- License: refer to the [Policies page](https://www.ebi.ac.uk/ena/browser/about/policies)
- Identifiers: [Accession numbers](https://ena-docs.readthedocs.io/en/latest/submit/general-guide/accessions.html)
- How to submit data:
  - [General guide on data submission](https://www.ebi.ac.uk/ena/browser/submit)
  - [ENA checklists](https://www.ebi.ac.uk/ena/browser/checklists) (i.e. supported metadata standards required for submission)
- Embargo: possible, set status to [confidential](https://ena-docs.readthedocs.io/en/latest/faq/release/data-availability-policy.html?highlight=confidential) upon submission
- More general RDM information about ENA on [RDMguide](https://rdm.elixir-belgium.org/ena) (ELIXIR Belgium)

#### European Variation Archive (EVA)
- [Homepage](https://www.ebi.ac.uk/eva/)
- [DOI(FAIRsharing)](https://doi.org/10.25504/FAIRsharing.6824pv)
- License: [EMBL-EBI terms of use](https://www.ebi.ac.uk/about/terms-of-use)
- Identifiers: accession numbers
- [Submit data](https://www.ebi.ac.uk/eva/?Submit-Data)
  - [Metadata template](https://www.ebi.ac.uk/eva/files/EVA_Submission_template.V1.1.4.xlsx)
- Embargo: Data submitted to the EVA can be held privately for up to two years.
The date of publication is set by the submitter using the "Hold Date" field of the
[EVA metadata template](https://www.ebi.ac.uk/eva/files/EVA_Submission_template.V1.1.4.xlsx)
  (see the [help page](https://www.ebi.ac.uk/eva/?Help#submitted-data-held-privately)).

### Ethics and Regulations
<!--Add information about laws and policies in Norway for relevant data types-->
- [General guidance for research ethics](https://www.forskningsetikk.no/en/guidelines/general-guidelines/)
- [Guidelines for Research Ethics in Science and Technology](
https://www.forskningsetikk.no/en/guidelines/science-and-technology/guidelines-for-research-ethics-in-science-and-technology/)
- [Institutional guidelines](https://rdmkit.elixir-europe.org/no_resources#institutional-policies-on-research-data)

### Services in Norway
<!--Add one line description-->

#### RDM Services
- [ELIXIR helpdesk](https://elixir.no/helpdesk)
  - Provides assistance with:
    - Data management planning
    - Storage and computing
    - Metadata standards
    - Data deposition to [ELIXIR databases](https://elixir-europe.org/platforms/data/elixir-deposition-databases)
  - Contact: ELIXIR helpdesk

- Data Stewardship Wizard (DSW)
  - Data management planning:
  - The ELIXIR Norway instance of the [Data Stewardship Wizard](
https://elixir-no.ds-wizard.org/)
provides exemplary DMPs for projects generating NGS data.
    - [Start from exemplary DMP](https://elixir-no.ds-wizard.org/projects/create/from-template?selected=5363b48a-83a0-4153-bca8-311408e33e97)
    - [Start from scratch](https://elixir-no.ds-wizard.org/projects/create/custom?selected=elixir.no:lifesciences-elixir-norway:latest)
  - Contact: ELIXIR helpdesk
- Institutional research data teams (listed on the [RDMkit national page](https://rdmkit.elixir-europe.org/no_resources#support-services))

#### Scientific Services
- [The National Consortium for Sequencing and Personalized Medicine (NorSeq)](https://www.norseq.org/)
  - [Equipment and Services](https://www.norseq.org/services/)
  - Contact: get in touch directly with the NorSeq site that best suits your requirements:
    - [NorSeq-Oslo, Oslo University Hospital and University of Oslo](https://www.sequencing.uio.no/)
    - [NorSeq-Cancer, Oslo University Hospital](http://oslo.genomics.no/)
    - [NorSeq-Bergen, University of Bergen and Haukeland University Hospital](https://www.uib.no/en/clin2/genomics)
    - [NorSeq-Trondheim, Norwegian University of Science and Technology (NTNU) and St.Olav's Hospital](https://www.ntnu.edu/mh/gcf)
    - [NorSeq-Tromsø, UiT - The Arctic University of Norway and University Hospital of Northern Norway](https://uit.no/prosjekter/prosjekt?p_document_id=468291)

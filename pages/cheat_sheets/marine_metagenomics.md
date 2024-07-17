---
layout: page
type: cheat_sheet
title: Marine Metagenomics
search_exclude: false
contributors: [Espen Åberg, Nazeefa Fatima]
page_id: marine_metagenomics
description: Data from marine (meta-) genomics
affiliations:
sidebar: cheat_sheets
dsw:
- name: "Marine Metagenomics"
  uuid: e4397aab-67e8-4aec-814a-eeb1399ef492
related_pages:
    cheat_sheet: [sequencing]
---

## Description
Collection of resources, tools and standards relevant for those interested in analysing marine (meta-) genomic datasets (e.g. genomes, metagenomes, and transcriptomes).

## Type of data/experiments/methods
### File formats
#### Commonly used raw file formats for sequencing data
- [FASTQ Sequence and Sequence Quality Format](https://doi.org/10.25504/FAIRsharing.r2ts5t)
- [FASTA](https://fairsharing.org/FAIRsharing.rz4vfg)
- [FASTQ Original Read Archive (ORA)](https://support-docs.illumina.com/SW/ORA_Format_Specification/Content/SW/ORA/ORAFormatSpecification.htm)
- [Illumina Binary Base Call](https://www.illumina.com/informatics/sequencing-data-analysis/sequence-file-formats.html)
- [PacBio legacy basecall File Format (bas.h5/bax.h5)](http://files.pacb.com/software/instrument/2.0.0/bas.h5%20Reference%20Guide.pdf)
- [PacBio Alignment File Format (cmp.h5)](https://pacbiofileformats.readthedocs.io/en/11.0/legacy/CmpH5Spec.html)
- [POD5 File Format](https://github.com/nanoporetech/pod5-file-format) for Oxford Nanopore Technology (ONT) data
- [Fast5](https://bioinformatics.cvr.ac.uk/exploring-the-fast5-format/) for ONT data

#### Alignment Formats
[Sequence Alignment Map
(SAM)](http://samtools.github.io/hts-specs/SAMv1.pdf)
	- [FAIRsharing](https://fairsharing.org/FAIRsharing.k97xzh)
	- Open Format

[Binary Alignment Map Format
(BAM)](https://genome.ucsc.edu/FAQ/FAQformat.html#format1)
	- [FAIRsharing](https://fairsharing.org/FAIRsharing.hza1ec)
 	- Open Format

[Compressed Reference-oriented Alignment Map (CRAM)](https://www.sanger.ac.uk/tool/cram/)
	- [FAIRsharing](https://fairsharing.org/FAIRsharing.f846bd)
	- Open Format

#### Annotation formats
[GenBank Sequence Format (GB, GBK)](https://www.ncbi.nlm.nih.gov/Sitemap/samplerecord.html)
	- [FAIRsharing](https://fairsharing.org/FAIRsharing.rg2vmt)
	- Open Format

ENA Sequence Flat File Format (formerly EMBL Sequence Flat File Format)
	- [FAIRsharing](https://fairsharing.org/FAIRsharing.q9nh66)
	- Open format

[Browser Extensible Data Format (BED)](http://genome.cse.ucsc.edu/FAQ/FAQformat.html#format1)
	- [FAIRsharing](https://fairsharing.org/FAIRsharing.mwmbpq)
	- Open format

[Generic Feature Format Version 3 (GFF3)](https://github.com/The-Sequence-Ontology/Specifications/blob/master/gff3.md)
	- [FAIRsharing](https://doi.org/10.25504/FAIRsharing.dnk0f6)
	- Open format

[Gene Transfer Format (GTF)](http://mblab.wustl.edu/GTF22.html)
	- [FAIRsharing](https://doi.org/10.25504/FAIRsharing.sggb1n)
	- Open format

[Variant Call Format (VCF)](https://samtools.github.io/hts-specs/VCFv4.3.pdf)
	- [FAIRsharing](https://doi.org/10.25504/FAIRsharing.cfzz0h)
	- Open format

## Metadata Standards
#### Standards
- [Minimum Information about any (x) Sequence](https://github.com/GenomicsStandardsConsortium/mixs/) <br>
The minimum information about any (x) sequence (MIxS) is an overarching framework of sequence metadata
	- [FAIRsharing entry link](https://fairsharing.org/bsg-s000518)
	- [MixS Checklist](https://genomicsstandardsconsortium.github.io/mixs/)

- [Minimum Information about a (Meta)Genome Sequence
(MIxS - MIGS/MIMS)](https://fairsharing.org/FAIRsharing.va1hck)

- [Meta-omics Data and Collection Objects
(MOD-CO)](https://www.mod-co.net/wiki/Schema_Representations)
	- [FAIRsharing](https://doi.org/10.25504/FAIRsharing.rvvbCB)

- [Genomic Contextual Data Markup Language
(GCDML)](https://wiki.gensc.org/index.php?title=GCDML)
	- [FAIRsharing](https://doi.org/10.25504/FAIRsharing.2hh7g7)

- [Minimum Information about an Uncultivated Virus Genome
(MIUViG)](https://www.ncbi.nlm.nih.gov/biosample/docs/packages/MIUVIG.5.0/)
	- [FAIRsharing](https://doi.org/10.25504/FAIRsharing.bd9566)

- [Minimum Information Standard for Engineered Organism Experiments
(MIEO)](https://www.nature.com/articles/s42003-018-0220-6)
	- [FAIRsharing](https://doi.org/10.25504/FAIRsharing.9fe00b)

- [Marine Microbial Biodiversity, Bioinformatics, Biotechnology Checklist
(Micro B3)](http://www.ebi.ac.uk/ena/submit/microb3-checklist)
   	- [FAIRsharing](https://doi.org/10.25504/FAIRsharing.2b3at8)

#### Ontologies

- [Environment Ontology (ENVO)](http://environmentontology.org/)
	- [FAIRsharing](https://fairsharing.org/919)

- [Metagenome/Microbes Environmental Ontology (MEO)](https://bioportal.bioontology.org/ontologies/MEO)
	- [FAIRsharing](https://fairsharing.org/bsg-s002785)

- [Gene Ontology (GO)](http://www.geneontology.org)
	- [FAIRsharing](https://doi.org/10.25504/FAIRsharing.6xq0ee)


## Sources for Reusable Data
#### MGnify

- **Description:** EBI Metagenomics has changed its name to MGnify to reflect a change in scope. This is a free-to-use resource aiming at supporting all metagenomics researchers. The service is an automated pipeline for the analysis and archiving of metagenomic data that aims to provide insights into the phylogenetic diversity as well as the functional and metabolic potential of a sample. You can freely browse all the public data in the repository.
- **Standard License:** [EMBL-EBI Terms of Use](https://www.ebi.ac.uk/about/terms-of-use)
- **identifiers.org:** [MGnify Sample](https://registry.identifiers.org/registry/mgnify.samp#!), [MGnify Project](https://registry.identifiers.org/registry/mgnify.proj#!)
- **How to access:**
	- [Homepage](https://www.ebi.ac.uk/metagenomics/)
	- [FAIRsharing entry link](https://fairsharing.org/FAIRsharing.dxj07r)

#### MAR databases

- **Description:** The MAR database is a collection of manually curated marine microbial contextual and sequence databases, based at the Marine Metagenomics Portal. This was developed as a part of the ELIXIR EXCELERATE project in 2017 and is maintained by The Center for Bioinformatics (SfB) at the UiT The Arctic University of Norway. SfB is hosting the UiT node of ELIXIR Norway. The MarRef, MarDb, MarFun and MarCat contextual databases are built by compiling data from a number of public available sequence, taxonomy and literature databases in a semi-automatic fashion.
- **identifiers.org:** [MarRef](https://registry.identifiers.org/registry/mmp.ref#!), [MarDB](https://registry.identifiers.org/registry/mmp.db#!), [MarFun](https://registry.identifiers.org/registry/mmp.fun#!), [MarCat](https://registry.identifiers.org/registry/mmp.cat#!)
- **How to access:**
	- [Homepage](https://mmp2.sfb.uit.no/databases/)
	- [FAIRsharing entry link](https://doi.org/10.25504/FAIRsharing.SnTbUa)

#### IMG/VR
(Integrated Microbial Genomes and Microbiomes - Viral Resources)

- **Description:** Since 2016, the IMG/VR database has provided access to the largest collection of viral sequences obtained from (meta)genomes. The 3rd version of IMG/VR (Sept 2020) is composed of 18,373 cultivated and 2,314,329 uncultivated viral genomes (UViGs), nearly tripling the total number of sequences compared to the previous version. UViGs in IMG/VR are reported as single viral contigs, integrated proviruses, or genome bins, and are annotated with a new standardized pipeline including genome quality estimation using CheckV, taxonomic classification reflecting the latest ICTV update, and expanded host taxonomy prediction. The new IMG/VR interface enables users to efficiently browse, search, and select UViGs based on genome features and/or sequence similarity.
- **identifiers.org:** [Integrated Microbial Genomes Taxon](https://registry.identifiers.org/registry/img.taxon#!), [Integrated Microbial Genomes Gene](https://registry.identifiers.org/registry/img.gene#!)
- **How to access:**
	- [Homepage](https://img.jgi.doe.gov/vr/)
	- [FAIRsharing entry link](https://doi.org/10.25504/FAIRsharing.2KIa7T)

## Storage and Computing
<!--Add information about e.g. NeLS-->

### Data Deposition Repositories

#### European Nucleotide Archive (ENA)
- [Homepage](https://www.ebi.ac.uk/ena/browser/)
- [DOI(FAIRsharing)](https://doi.org/10.25504/FAIRsharing.dj8nt8)
- License: refer to the [Policies page](https://www.ebi.ac.uk/ena/browser/about/policies)
- Identifiers: [Accession numbers](https://ena-docs.readthedocs.io/en/latest/submit/general-guide/accessions.html)
- How to submit data:
  - [General guide on data submission](https://ena-docs.readthedocs.io/en/latest/submit/general-guide.html)
  - [ENA checklists](https://www.ebi.ac.uk/ena/browser/checklists) (i.e. supported metadata standards required for submission)
- Embargo: possible, set status to [confidential](https://ena-docs.readthedocs.io/en/latest/faq/release/data-availability-policy.html?highlight=confidential) upon submission
- More general RDM information about ENA on [RDMguide](https://rdm.elixir-belgium.org/ena) (ELIXIR Belgium)

#### World Register of Marine Species [(WoRMS)](http://www.marinespecies.org)

- Standard License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- [identifiers.org](https://registry.identifiers.org/registry/worms#!)
- How to submit data: [Through WoRMS contributing databases](https://www.marinespecies.org/about.php#partners)

### Ethics and Regulations
<!--Add information about laws and policies in Norway for relevant data types-->
- [General guidance for research ethics](https://www.forskningsetikk.no/en/guidelines/general-guidelines/)
- [Guidelines for Research Ethics in Science and Technology](
https://www.forskningsetikk.no/en/guidelines/science-and-technology/guidelines-for-research-ethics-in-science-and-technology/)
- [Institutional guidelines](https://rdmkit.elixir-europe.org/no_resources#institutional-policies-on-research-data)

### Services in Norway
<!--Add one line description-->
#### The Marine Metagenomics Portal (MMP)

- The Marine Metagenomics Portal provides access to high-quality curated and freely accessible marine microbial genomics and metagenomics resources. It includes the MAR databases, a collection of richly annotated and manually curated contextual and sequence databases, and MetaPipe, a complete workflow for the analysis of marine metagenomic data.
- Contact information
	- [ELIXIR Norway - Tromsø Node](https://elixir.no/organization/organisation/elixir-uit)
	- [Website Link](https://mmp2.sfb.uit.no)

#### Metapipe
- META-pipe is a complete workflow for the analysis of marine metagenomic data. It provides assembly of high-throughput sequence data, functional annotation of predicted genes, and taxonomic profiling.
- Contact information
	- [ELIXIR Norway - Tromsø Node](https://elixir.no/organization/organisation/elixir-uit)
	- [Website Link](https://mmp2.sfb.uit.no/metapipe/)

#### Data management planning:
The ELIXIR-NO instance of the [Data Stewardship Wizard](https://norway.dsw.elixir-europe.org/wizard/) provides support for data management planning for marine metagenomics in Norway. An exemplary Data Management Plan model for marine metagenomics in Norway is available [here](https://norway.dsw.elixir-europe.org/wizard/projects/create?selectedProjectTemplate=e4397aab-67e8-4aec-814a-eeb1399ef492). General guidance from RDMkit on [how to write a Data Management Plan](https://rdmkit.elixir-europe.org/data_management_plan)

#### Data storage
- The Norwegian e-infrastructure for life sciences (NeLS)
- ELIXIR Norway offers an infrastructure for storage of scientific data, intended for scientific research projects with larger sets of data (minimum 1TB) for mid-term storage. We currently offer free storage of data up to 10TB. For larger projects, please [contact us at ](mailto:contact@bioinfo.no).
- Contact information
	- [NeLS](https://nels.bioinfo.no)
	- [ELIXIR Norway](https://elixir.no)

#### Bioinformatics
- ELIXIR Norway offers general advice and experimental design consultancy, programming and scripting assistance and support for data analysis on marine metagenomics in Norway. [ELIXIR Norway's HelpDesk](https://elixir.no/helpdesk) can also assist you on:
  - Data management planning
  - Storage and computing
  - Metadata standards
  - Data deposition to [ELIXIR databases](https://elixir-europe.org/platforms/data/elixir-deposition-databases)

## Useful Links
[Norwegian tool assembly for marine metagenomics data management](https://rdmkit.elixir-europe.org/marine_metagenomics_assembly.html)

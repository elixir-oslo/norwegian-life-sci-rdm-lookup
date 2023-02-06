---
layout: page
title: Biodiversity
type: cheat_sheet
search_exclude: false
contributors: [Michal Torma]
page_id: biodiversity
description: Biodiversity data about species recorded in space and time.
affiliations: ["Norwegian node of the Global Biodiversity Information Facility (GBIF-NO)"]
sidebar: cheat_sheets
dsw:
- name: "Bio occurrence data"
  uuid: 8201e668-3b6e-499d-b279-82932d5510c7
---

## Biodiversity data

### Description
Biodiversity data is data about species recorded in space and time. Such data is useful for the modeling of future species distribution, impact of climate change etc. Many natural studies inadvertently collect biodiversity data in different shape and form therefore it is often challenging to reshape the data into standardised form.

### Type of data/experiments/methods
All publishable biodiversity data should follow [Darwin Core](https://dwc.tdwg.org/) data standard. Data in spreadsheets or databases can easily be converted to the Darwin Core standard using the IPT (Integrated Publishing Toolkit).
This standard supports the following data structures:

#### Occurrence data
- [How to publish](https://ipt.gbif.org/manual/en/ipt/2.4/occurrence-data)

#### Sampling event data
- [How to publish](https://ipt.gbif.org/manual/en/ipt/2.4/sampling-event-data)

#### Checklist data
- [How to publish](https://ipt.gbif.org/manual/en/ipt/2.4/checklist-data)

### Metadata Standards
#### EML
Metadata standard used is [EML](https://eml.ecoinformatics.org/). To create metadata for your dataset, you will fill in a form during the IPT dataset publication process.

### Sources for Reusable Data
#### GBIF
All published biodiversity data (from different sources) is available through [GBIF](https://gbif.org) portal. Filtered datasets are provided with unique DOIs for tracking data use. It's also possible to use the [GBIF API](https://www.gbif.org/developer/summary) with [R](https://cran.r-project.org/web/packages/rgbif/index.html) or [python](https://www.gbif.org/tool/OlyoYyRbKCSCkMKIi4oIT/pygbif-gbif-python-client) to retrieve data.

### Storage and Computing
Storage is provided by individual IPT (Integrated Publishing Toolkit) providers.

### Data Deposition Repository
file formats supported by IPT are:
- CSV and plain text formats
- XLSX and XLS
- SQL databases (e.g. Mariadb, Postgres)

#### GBIF Norway IPT
- [Contact us](mailto:helpdesk@gbif.no) to get user credentials
- [IPT url](https://ipt.gbif.no)
- Post on the [GBIF Norway github issue list](https://github.com/gbif-norway/helpdesk/issues) for general questions about data publication. You can also see questions others have posted here.

### Useful Links
<!--Add a list of relevant external/global tools-->
- In addition to the Norwegian helpdesk github, there is a [global GBIF github issue list](https://github.com/gbif/ipt/issues?q=) for data publication and IPT usage questions
- [Darwin core extensions](https://rs.gbif.org/extension/)

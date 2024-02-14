---
title: Manuscript Title
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-02-14'
author-meta:
- John Doe
- Jane Roe
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Manuscript Title" />
  <meta name="citation_title" content="Manuscript Title" />
  <meta property="og:title" content="Manuscript Title" />
  <meta property="twitter:title" content="Manuscript Title" />
  <meta name="dc.date" content="2024-02-14" />
  <meta name="citation_publication_date" content="2024-02-14" />
  <meta property="article:published_time" content="2024-02-14" />
  <meta name="dc.modified" content="2024-02-14T22:16:25+00:00" />
  <meta property="article:modified_time" content="2024-02-14T22:16:25+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="John Doe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@johndoe" />
  <meta name="citation_author" content="Jane Roe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <link rel="canonical" href="https://AlexsLemonade.github.io/ScPCA-manuscript/" />
  <meta property="og:url" content="https://AlexsLemonade.github.io/ScPCA-manuscript/" />
  <meta property="twitter:url" content="https://AlexsLemonade.github.io/ScPCA-manuscript/" />
  <meta name="citation_fulltext_html_url" content="https://AlexsLemonade.github.io/ScPCA-manuscript/" />
  <meta name="citation_pdf_url" content="https://AlexsLemonade.github.io/ScPCA-manuscript/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://AlexsLemonade.github.io/ScPCA-manuscript/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://AlexsLemonade.github.io/ScPCA-manuscript/v/c750b62cf3b82afb80a08f0b04905af8f006be68/" />
  <meta name="manubot_html_url_versioned" content="https://AlexsLemonade.github.io/ScPCA-manuscript/v/c750b62cf3b82afb80a08f0b04905af8f006be68/" />
  <meta name="manubot_pdf_url_versioned" content="https://AlexsLemonade.github.io/ScPCA-manuscript/v/c750b62cf3b82afb80a08f0b04905af8f006be68/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://AlexsLemonade.github.io/ScPCA-manuscript/v/c750b62cf3b82afb80a08f0b04905af8f006be68/))
was automatically generated
from [AlexsLemonade/ScPCA-manuscript@c750b62](https://github.com/AlexsLemonade/ScPCA-manuscript/tree/c750b62cf3b82afb80a08f0b04905af8f006be68)
on February 14, 2024.
</em></small>



## Authors



+ **John Doe**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [johndoe](https://twitter.com/johndoe)
    · ![Mastodon icon](images/mastodon.svg){.inline_icon width=16 height=16}
    [\@johndoe@mastodon.social](https://mastodon.social/@johndoe)
    <br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Jane Roe**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [janeroe](https://github.com/janeroe)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/AlexsLemonade/ScPCA-manuscript/issues)
or email to
Jane Roe \<jane.roe@whatever.edu\>.


:::


## Abstract {.page_break_before}




## Introduction

Since the introduction of single-cell RNA-seq technology, the number of studies that utilize single-cell RNA-seq has grown rapidly[@doi:10.1038/nprot.2017.149].
Unlike its predecessor, bulk RNA-seq, which averages the profiles of all cells within a sample, single-cell technology quantifies gene expression in individual cells.
Tumors are known to be transcriptionally heterogeneous, so many studies have highlighted the importance of using single-cell RNA-seq in studying tumor samples [@doi:10.1101/gr.190595.115].
Researchers can use tumor single-cell RNA-seq to analyze and identify individual cell populations that may play important roles in tumor growth, resistance, and metastasis [@doi:10.1126/science.1254257].
Additionally, single-cell RNA-seq data provides insight into how tumor cells may be interacting with normal cells in the tumor microenvironment[@10.1038/s41588-022-01141-9].

With the growing number of single-cell RNA-seq datasets, efforts have emerged to create central, harmonized sources for datasets.
Harmonized data resources allow researchers to leverage more samples from various biological contexts to complete their analysis and elucidate previously unknown similarities across samples and disease types.
The Human Cell Atlas (HCA) and Human Tumor Atlas Network (HTAN) are two of many such examples.
The HCA, which aims to use single-cell genomics to provide a comprehensive map of all cell types in the human body [@doi:10.7554/eLife.27041], contains uniformly processed single-cell RNA-seq data obtained from normal tissue with few samples derived from diseased tissue.
The HTAN also hosts a collection of genomic data collected from tumors across multiple cancer types, including single-cell RNA-seq [@doi:10.1016/j.cell.2020.03.053].

Existing resources have focused on making large quantities of harmonized data from normal tissue or adult tumor samples publicly available, but there are considerably fewer efforts to harmonize and publicize data from pediatric tumors.
Pediatric cancer is much less common than adult cancer, so the number of available samples from pediatric tumors is smaller compared to the number of adult tumors [@url:https://www.cancer.gov/types/childhood-cancers/child-adolescent-cancers-fact-sheet#how-do-cancers-in-adolescents-and-young-adults-differ-from-those-in-younger-children].
Additionally, not every institution has access to data from pediatric tumors.
Thus, it is imperative to provide harmonized data from pediatric tumors to all pediatric cancer researchers [@doi:10.1186/s13040-018-0190-8].
To address this unmet need, Alex's Lemonade Stand Foundation and the Childhood Cancer Data Lab developed and maintain the Single-cell Pediatric Cancer Atlas (ScPCA) Portal (https://scpca.alexslemonade.org/), an open-source data resource for single-cell and single-nuclei RNA sequencing data of pediatric tumors.

The ScPCA Portal holds uniformly processed summarized gene expression from 10X Genomics' droplet-based single-cell and single-nuclei RNA-seq for over 500 samples from a diverse set of over 50 types of pediatric cancers.
Originally comprising data from 10 projects funded by Alex's Lemonade Stand Foundation, the Portal has since expanded to include data contributed by pediatric cancer research community members.
In addition to gene expression data from single-cell and single-nuclei RNA-seq, the Portal includes data obtained from bulk RNA-seq, spatial transcriptomics, and feature barcoding methods, such as ADT/CITE-seq and cell hashing.
All data provided on the portal are available in formats ready for downstream analysis, such as SingleCellExperiment or AnnData, with objects containing normalized gene expression counts, dimensionality reduction results, and cell type annotations.

To ensure that all current and future data on the Portal are uniformly processed, we created scpca-nf, a Nextflow-based open-source pipeline (https://github.com/AlexsLemonade/scpca-nf).
Using a consistent pipeline for all data increases transparency and allows users to perform analysis across multiple samples and projects without having to do any re-processing.
The scpca-nf workflow uses alevin-fry [@doi:10.1038/s41592-022-01408-3] for fast and efficient quantification of gene expression for all samples on the Portal, including single-cell RNA-seq data and any associated ADT/CITE-seq or cell hash data, spatial transcriptomics data, and bulk RNA-seq data.
The scpca-nf pipeline also serves as a resource for the community, allowing others to process their own samples for comparison to samples available on the Portal and allowing us to accept uniformly processed community contributions.

Here, we present the Single-cell Pediatric Cancer Atlas as a resource for all pediatric cancer researchers.
The ScPCA Portal provides downloads ready for immediate use, allowing researchers to skip time-consuming data re-processing and wrangling steps.
We provide comprehensive documentation about data processing and the contents of files on the portal, including a guide to getting started working with an ScPCA dataset (https://scpca.readthedocs.io/).
The ScPCA Portal helps advance pediatric cancer research by accelerating researchers' ability to answer important biological questions.


# Results

## The Single-cell Pediatric Cancer Atlas Portal

1. History and overview of the Portal
  - In 2022, the Childhood Cancer Data Lab launched the Single-cell Pediatric Cancer Atlas (ScPCA) Portal to make uniformly processed, summarized single-cell and single-nuclei RNA-seq data and de-identified metadata available for download
  - The Portal currently holds X amount of samples from X amount of tumor types
  - Data available on the Portal was obtained using two mechanisms - accepting raw data from ALSF-funded investigators and investigators who used our open-source pipeline to produce summarized gene expression data for inclusion on the portal.
  - In addition to providing summarized gene expression data, we collect a core set of metadata that is provided on the Portal for all samples including, age, sex, diagnosis, subdiagnosis (if applicable), tissue location, and disease stage.
  - All metadata that is provided by the submitter is reviewed to standardize as much as possible. We also utilize ontology ID's where possible.
  - Fig. 1A shows how many samples we have from each type of tumor. For each diagnosis, we also indicate what proportion of the samples come from each disease stage (e.g., initial diagnosis, recurrence, post-mortem).
  - The samples obtained on the portal are mostly from patient tumors, although some are from patient-derived xenografts and human cell lines
  - In addition to single-cell and single-nuclei RNA-seq, many samples have associated bulk RNA-seq, ADT data (CITE-seq), cell hashing, or spatial transcriptomics.
  - Fig. 1B summarizes the total number of samples that are single-cell vs. single-nuclei. Additionally, we show how many of the samples on the portal also have either bulk, CITE, cell hashing, or spatial data.
  - Supplemental Table 1 shows a breakdown of how many of each modality is found in each project.

2. Obtaining additional project information
  - On the Portal, samples are organized by project. Each project is a collection of similar samples from a single investigator.
  - To select projects of interest, users can filter based on diagnosis, modality included, single-cell or single-nuclei and 10X version. Additionally, users will be able to filter based on if the project includes cell line samples or xenografts.
  - A summary of each project, including a list of samples found in each project, is displayed on the Portal.
  - Fig.1C shows an example of this summary which include an abstract, links to any external information about the projects such as any associated publication information, and links to external places where data may be stored such as SRA or GEO.
  - If a project includes bulk, CITE, spatial, or multiplexing, this will also be indicated on the project card.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>


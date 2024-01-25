---
title: Manuscript Title
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-01-25'
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
  <meta name="dc.date" content="2024-01-25" />
  <meta name="citation_publication_date" content="2024-01-25" />
  <meta property="article:published_time" content="2024-01-25" />
  <meta name="dc.modified" content="2024-01-25T19:57:24+00:00" />
  <meta property="article:modified_time" content="2024-01-25T19:57:24+00:00" />
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
  <link rel="alternate" type="text/html" href="https://AlexsLemonade.github.io/ScPCA-manuscript/v/fa36ed255b53d40e32346d7c8f782314c94e0383/" />
  <meta name="manubot_html_url_versioned" content="https://AlexsLemonade.github.io/ScPCA-manuscript/v/fa36ed255b53d40e32346d7c8f782314c94e0383/" />
  <meta name="manubot_pdf_url_versioned" content="https://AlexsLemonade.github.io/ScPCA-manuscript/v/fa36ed255b53d40e32346d7c8f782314c94e0383/manuscript.pdf" />
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
([permalink](https://AlexsLemonade.github.io/ScPCA-manuscript/v/fa36ed255b53d40e32346d7c8f782314c94e0383/))
was automatically generated
from [AlexsLemonade/ScPCA-manuscript@fa36ed2](https://github.com/AlexsLemonade/ScPCA-manuscript/tree/fa36ed255b53d40e32346d7c8f782314c94e0383)
on January 25, 2024.
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

- Intro to single-cell analysis and the need for a central repository with harmonized data
  - The amount of single-cell RNA-seq data has been rapidly growing
  - Unlike bulk, which averages the profiles of all cells within a sample, Single-cell RNA-seq allows for analysis and identification of individual cell populations that may play important roles in tumor growth, resistence, and metastasis
  - Single-cell RNA-seq of tumor samples also allows us to understand how tumor cells may interact with normal cells in the tumor microenvironment
  - With the growing number of single-cell RNA-seq datasets, efforts have emerged to create central, harmonized sources for datasets such as the Human Cell Atlas, which mainly contains normal tissue with a smaller proportion of samples derived from diseased tissue
  - Additionally, the Human Tumor Atlas Network hosts a collection of genomics data, including Single-cell RNA-seq, across multiple cancer types
  - By harmonizing data across multiple studies and diseases, researchers can better perform joint analysis, taking advantage of more samples to complete their analysis and illuminate previously unknown similarities

- Intro to ScPCA portal and how it fills a gap in the field
  - However, there previously was no collection of Single-cell RNA seq datasets specific to pediatric cancer
  - A sentence about why do we care about pediatric. We should mention something about the number of samples available from pediatric tumors being low compared to adult tumors and limited by institution, so it's even more important to make data available to all researchers.
  - To fill this unmet need, we developed and currently maintain the Single-cell Pediatric Cancer Atlas (ScPCA) Portal, an open-source data resource for single-cell and single-nuclei RNA sequencing data of pediatric tumors


- What is the ScPCA portal
  - The ScPCA Portal holds uniformly processed summarized gene expression for over 500 samples from a diverse set of over 50 types of cancers
  - Data comes from 10 projects funded by ALSF and additional community contributed datasets
  - In addition to gene expression data from single-cell and single-nuclei RNA sequencing, the Portal holds data obtained from bulk RNA sequencing, spatial transcriptomics, and feature barcoding methods, such as CITE-seq and cell hashing
  - Data provided on the portal is available in formats ready for downstream analysis, such as SingleCellExperiment or AnnData objects.
  - All samples contain normalized gene expression counts, dimensionality reduction results and cell type annotations (technically most will not all)


- Why is the ScPCA portal important
  - Data on the portal has been uniformly processed using scpca-nf, a Nextflow-based open-source pipeline developed by the Childhood Cancer Data Lab.
  - The scpca-nf workflow uses alevin-fry for fast and efficient processing of all data currently available on the portal, including single-cell RNA-seq data and any associated CITE-seq or cell hash data, spatial transcriptomics data, and bulk RNA sequencing.
  - This makes it easy to perform analysis across multiple samples and projects without having to do any re-processing
  - We also provide scpca-nf as a resource to the community to easily allow others to process their own samples for comparison to those on the Portal.
  - In addition to uniformly processed data across multiple cancer types, we provide comprehensive documentation about data processing and the contents of files on the portal, including a guide to getting started working with an ScPCA dataset.
  - The data included on the Portal will serve as a resource for all pediatric cancer researchers by providing uniformly processed data ready for immediate use to help researchers answer their important biological questions, without the need for time consuming data re-processing and data wrangling.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>


---
title: Manuscript Title
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-02-28'
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
  <meta name="dc.date" content="2024-02-28" />
  <meta name="citation_publication_date" content="2024-02-28" />
  <meta property="article:published_time" content="2024-02-28" />
  <meta name="dc.modified" content="2024-02-28T15:31:55+00:00" />
  <meta property="article:modified_time" content="2024-02-28T15:31:55+00:00" />
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
  <link rel="alternate" type="text/html" href="https://AlexsLemonade.github.io/ScPCA-manuscript/v/d09b4b36d9241003fd27cb92d7d09b9076a173d1/" />
  <meta name="manubot_html_url_versioned" content="https://AlexsLemonade.github.io/ScPCA-manuscript/v/d09b4b36d9241003fd27cb92d7d09b9076a173d1/" />
  <meta name="manubot_pdf_url_versioned" content="https://AlexsLemonade.github.io/ScPCA-manuscript/v/d09b4b36d9241003fd27cb92d7d09b9076a173d1/manuscript.pdf" />
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
([permalink](https://AlexsLemonade.github.io/ScPCA-manuscript/v/d09b4b36d9241003fd27cb92d7d09b9076a173d1/))
was automatically generated
from [AlexsLemonade/ScPCA-manuscript@d09b4b3](https://github.com/AlexsLemonade/ScPCA-manuscript/tree/d09b4b36d9241003fd27cb92d7d09b9076a173d1)
on February 28, 2024.
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

In March of 2022, the Childhood Cancer Data Lab launched the Single-cell Pediatric Cancer Atlas (ScPCA) Portal to make uniformly processed, summarized single-cell and single-nuclei RNA-seq data and de-identified metadata from pediatric tumor samples available for download.
Data available on the Portal was obtained using two different mechanisms: raw data was accepted from ALSF-funded investigators and processed using our open-source pipeline, `scpca-nf`, or investigators processed their raw data using `scpca-nf` and submitted the output for inclusion on the Portal.

All samples on the Portal include a core set of metadata obtained from investigators, including age, sex, diagnosis, subdiagnosis (if applicable), tissue location, and disease stage.
Some investigators submitted additional metadata, such as treatment and tumor stage, which can also be found on the Portal.
All submitted metadata was standardized to maintain consistency across projects before adding to the Portal.
In addition to providing a human-readable value for the submitted metadata, we also provide an ontology term ID, if applicable.
Submitted metadata was mapped to an associated ontology term IDs obtained from HsapDV (age) [@url:https://www.ebi.ac.uk/ols4/ontologies/hsapdv], PATO (sex) [@url:https://www.ebi.ac.uk/ols4/ontologies/pato], NCBI taxonomy (organism) [@url:https://www.ncbi.nlm.nih.gov/taxonomy], MONDO (disease) [@url:https://www.ebi.ac.uk/ols4/ontologies/mondo], UBERON (tissue) [@url:https://www.ebi.ac.uk/ols4/ontologies/uberon], and Hancestro (ethnicity, if applicable) [@url:https://www.ebi.ac.uk/ols4/ontologies/hancestro]. 
Including ontology term IDs for each sample provides users with standardized metadata terms that can be used across all projects.

The Portal contains data from 500 samples and over 50 tumor types.
<!-- TODO: Update numbers -->
The total number of samples for each diagnosis is shown in Figure 1A, along with a breakdown of the proportion of samples from each disease stage within a diagnosis group.
Figure 1A summarizes all samples from patient tumors or patient-derived xenografts currently available on the Portal.
Most samples found on the Portal were obtained from patients with leukemia (n = 192). 
The Portal also includes samples from brain and central nervous system tumors (n = 154), sarcoma and soft tissue tumors (n = 68), and a variety of other solid tumors (n = 87). 
Most samples were collected at initial diagnosis (n = 424), with a smaller number of samples collected either at recurrence (n = 64), during progressive disease (n = 10), or post-mortem (n = 2). 
Along with the patient tumors, the Portal contains a small number of human tumor cell line samples (n = 4).


Each of the available samples contains summarized gene expression data from either single-cell or single-nuclei RNA sequencing. 
However, some samples also include additional data, such as quantified expression data from tagging cells with Antibody-derived tags (ADT), like CITE-seq antibodies [@doi:10.1038/nmeth.4380], or multiplexing samples with hashtag oligonucleotides (HTO)[@doi:10.1186/s13059-018-1603-1] prior to sequencing. 
Out of the 500 samples, 96 have associated CITE-seq data, and 19 have associated multiplexing data. 
In some cases, multiple libraries from the same sample were collected for additional sequencing, either for bulk RNA-seq or spatial transcriptomics. 
Specifically, 118 samples on the Portal were sequenced using bulk RNA-seq and 94 samples were sequenced using spatial transcriptomics.
A summary of the number of samples with each additional modality is shown in Figure 1B, and a detailed summary of the total samples with each sequencing method broken down by project is available in Supplemental Table 1.

Samples on the Portal are organized by project, where each project is a collection of similar samples from an individual lab.
Users can filter projects based on diagnosis, included modalities (e.g., CITE-seq, bulk RNA-seq), 10X Genomics version (e.g., 10Xv2, 10Xv3), and whether or not a project includes samples derived from patient-derived xenografts or cell lines.
The project card displays an abstract, the total number of samples included, a list of diagnoses for all samples included in the Project, and links to any external information associated with the project, such as publications and links to external data, such as SRA or GEO (Figure 1C).
The project card will also indicate the type(s) of sequencing performed, including the 10X Genomics kit version, the suspension type (cell or nucleus), and if additional sequencing is present, like bulk RNA-seq or multiplexing.

## Uniform processing of data available on the ScPCA Portal

All data available on the Portal was uniformly processed using [`scpca-nf`](https://github.com/AlexsLemonade/scpca-nf), an open-source and efficient Nextflow[@url:https://www.nextflow.io/docs/latest/index.html] workflow for quantifying single-cell and single-nuclei RNA-seq data. 
Using Nextflow as the backbone for the `scpca-nf` workflow ensures both reproducibility and portability.
All dependencies for the workflow are handled automatically, as each process in the workflow is run in a Docker container.
Nextflow is compatible with various computing environments, including high-performance computing and cloud-based computing, allowing users to run the workflow in their preferred environment. 
Setup requires organizing input files and updating a single configuration file for your computing environment after installing Nextflow and either Docker or Singularity. 
Nextflow will also handle parallelizing sample processing as allowed by your environment, minimizing run time. 
The combination of being able to execute a Nextflow workflow in any environment and run individual processes in Docker containers makes this workflow easily portable for external use. 

When building `scpca-nf`, we sought a fast and memory-efficient tool for gene expression quantification to minimize processing costs.
We expected many users of the Portal to have their own single-cell or single-nuclei data processed with Cell Ranger[@url:https://www.10xgenomics.com/support/software/cell-ranger/latest], due to its popularity.
Thus, selecting a tool with comparable results to Cell Ranger was also desirable.
In comparing `alevin-fry` [@doi:10.1038/s41592-022-01408-3] to Cell Ranger, we found `alevin-fry` had a lower run time and memory usage (Supplemental Figure 1A), while retaining comparable mean gene expression for all genes (Supplemental Figure 1B), total UMIs per cell (Supplemental Figure 1C),  or total genes detected per cell (Supplemental Figure 1D). 
<!--TODO: Do we like including this here or is it not worth mentioning? --> 
(All analyses comparing gene expression quantification tools are available in a public analysis repository[@url:https://github.com/AlexsLemonade/alsf-scpca].)
Based on these results, we elected to use `salmon alevin` and `alevin-fry` [@doi:10.1038/s41592-022-01408-3] in `scpca-nf` to quantify gene expression data.

`scpca-nf` takes FASTQ files as input (Figure 2A).
Reads are aligned using the selective alignment option of `salmon alevin` to an index with transcripts corresponding to spliced cDNA and intronic regions, denoted by `alevin-fry` as a `splici` index. 
The output from `alevin-fry` includes a gene-by-cell count matrix for all barcodes identified, even those that may not contain true cells. 
This unfiltered counts matrix is stored in a `SingleCellExperiment` object[@doi:10.1038/s41592-019-0654-x] and output from the workflow to a `.rds` file with the suffix `_unfiltered.rds`.

`scpca-nf` performs filtering of empty droplets, removal of low-quality cells, normalization, dimensionality reduction, and cell type annotation (Figure 2A). 
The unfiltered gene by cell counts matrices are filtered to remove any barcodes that are not likely to contain cells using `DropletUtils::emptyDropsCellRanger()`[@doi:10.1186/s13059-019-1662-y], with all cells that pass being saved to a `SingleCellExperiment` object and `.rds` file with the suffix `_filtered.rds`.
Then, low-quality cells are identified and removed with `miQC` [@doi: 10.1371/journal.pcbi.1009290], which jointly models the proportion of mitochondrial reads and detected genes per cell and calculates a probability that each cell is compromised. 
The remaining cells are normalized [@doi:10.1186/s13059-016-0947-7] and undergo dimensionality reduction using both principal component analysis (PCA) and UMAP.
Finally, cell types are classified using two automated methods, `SingleR`[@doi:10.1038/s41590-018-0276-y] and `CellAssign`[@doi:10.1038/s41592-019-0529-1]. 
The results from this analysis are stored in a processed `SingleCellExperiment` object saved to a `.rds` file with the suffix `_processed.rds`.

To make downloading from the Portal convenient for R and Python users, downloads are available as either `SingleCellExperiment` or `AnnData`[@doi:10.1101/2021.12.16.473007] objects.
All `SingleCellExperiment` objects saved as `.rds` files are converted to `AnnData` objects and saved as `.hdf5` files in `scpca-nf` (Figure 2A).
Downloads contain the unfiltered, filtered, and processed objects from `scpca-nf` to allow users to choose to perform their own filtering and normalization or to start their analysis from a processed object.

All downloads from the Portal include a quality control (QC) report with a summary of processing information (e.g., `alevin-fry` version), library statistics (e.g., the total number of cells), and a collection of diagnostic plots for each library (Figure 2B-G).
The knee plot includes all droplets (i.e., before removing empty droplets) sorted based on the total number of UMIs, and those retained after filtering empty droplets are indicated in the plot (Figure 2B).
For each cell that remains after filtering empty droplets, the number of total UMIs, genes detected, and mitochondrial reads are calculated and summarized in a scatter plot (Figure 2C). 
We include plots showing the `miQC` model and which cells are kept and removed after filtering with `miQC` (Figure 2D-E).
A UMAP plot with cells colored by the total number of genes detected and a faceted UMAP plot where cells are colored by the expression of a top highly variable gene are also available (Figure 2F-G).


## Making samples with additional modalities available on the Portal

1. Processing samples with additional modalities
  - In addition to samples that have single-cell and single-nuclei RNA-seq, we also received samples from submitters with additional sequencing modalities, including CITE-seq, cell hashing, spatial transcriptomics, and bulk RNA-seq.
  - To make all the data that we received available, we included additional modules in `scpca-nf` that would accommodate these additional sequencing modalities.
  - For a full summary of the libraries and samples available with additional modalities, see supplemental Table 1.
  - `scpca-nf` is capable of processing samples that are from a mix of sample types. This means that libraries with and without ADT data or any of the modalities discussed here can be processed together in a single run. Nextflow will handle the parallel processing such that each sample type is run through the correct processes for that modality type.

2. CITE-seq (Fig. S2A-B)
  - For all libraries with associated ADT or CITE-seq data, we provide both the RNA and ADT gene expression data in the files available for download on the portal.
  - Both FASTQ from single-cell/single-nuclei and from ADT were input into `scpca-nf` and quantified using `salmon alevin` and `alevin-fry`.
  - We required a barcodes file from each submitter that contained the ADT labels and the associated barcode. This was used to build the index used for quantification of the ADT FASTQ and creation of the cell by ADT matrix.
  - Unlike with RNA counts, we do not perform any filtering of cells due to low quality ADT expression. However, we do include the results from running `DropletUtils::cleanTagCounts()` in both the filtered and processed objects produced by `scpca-nf`.
  - Similar to RNA counts, we do normalize ADT data and provide the normalized counts matrix in the processed SCE object, but we do not provide any dimensionality reduction of ADT data, only the RNA data is used for dimensionality reduction.
  - ADT data can be found in the `altExp` slot of each `SingleCellExperiment` object or as a separate `_adt.hdf5` file for `AnnData` objects.
  - This section includes a summary of statistics such as how many cells express each ADT.
  - For libraries with ADT, we also include additional plots.
  - As mentioned above, we include the results from `DropletUtils::cleanTagCounts()`, but do not filter any ADTs or cells from the object. Instead we include a column in the `colData` of the processed SCE object that indicates if it is recommended to remove ADTs or not. In the QC report, we summarize filtering taking into account removal of cells because of low quality RNA or ADT. The plot shown in the report highlights which cells would be removed if only filtering using RNA, only ADT, or both.
  - Similar to the UMAPs for the RNA data from single-cell/single-nuclei that highlight the top variable genes, the report includes UMAPs highlighing the 4 most variable ADTs in the data. This is shown with UMAPs and ridge plots.

3. Cell hashing (Fig. S2C)
  - Similar to ADT data, if any libraries were multiplexed and have an associated cell hashing library, both the RNA and HTO FASTQ are provided as input to the workflow and quantified with `salmon alevin` and `alevin-fry`. We also include a library pools file which indicates which libraries contain which samples and the associated tags used to label each sample.
  - Although we quantify the HTO data and include the cell by HTO counts matrix in all objects, we do not demultiplex the samples so that there is one sample per library. Instead, we apply multiple demultiplexing methods including genetic demultiplexing, demultiplexing with `DropletUtils::hashedDrops()`, and demultipilexing with `Seurat::HTODemux()`. The results from these three methods are included in the filtered and processed objects.
  - Add some more details about how we do genetic demultiplexing, using vireo and bulk RNA-seq
  - If a library has associated HTO data, an additional section is added to the QC report included on the portal and output by `scpca-nf`.
  - This section includes a summary of statistics such as how many cells express each HTO.
  - For HTO, we do not include any additional plots, but we do show a table summarizing how many cells belong to each sample included in the multiplexed library using each of the demultiplexing methods mentioned.

4. Bulk and Spatial (Fig S3)
  - Some samples underwent sequencing using both single-cell/single-nuclei and an additional method like bulk RNA-seq or spatial transcriptomics.
  - `scpca-nf` is able to quantify both of these additional sequencing methods.
  - Bulk RNA FASTQ are first trimmed using `fastp` and then aligned using `salmon`. The bulk output is a single tsv file with the sample by gene matrix for all samples in that project.
  - For spatial transcriptomics, the spatial RNA FASTQ and slide image are input into `scpca-nf` and quantified using `spaceranger`. The output includes the spot by gene matrix along with a summary report, produced by `spaceranger`.

## Downloading projects from the ScPCA Portal

1. Users can download all samples for a given project together
  - The portal has two different options to allow users to download data for all samples in a given ScPCA Project, either as invididual files for each sample or as a single merged file.
  - By default, when downloading a project, the download will include a folder for each sample that is included in the project.
  - That folder will contain all individual `SingleCellExperiment` objects as `.rds` files or `AnnData` objects as `.hdf5` files, depending on the file format chosen by the user (Fig. 3A).
  - Each of these objects contains the gene expression data and metadata for a single library.
  - If a given project has associated bulk RNA-seq, then a sample by gene counts matrix, `bulk_quant.tsv`, including the quantified gene expression data for all samples in a project with associated bulk RNA-seq will be included.
2. Merged objects
  - Providing all data from all libraries withing a single file makes it easier for users to perform joint analysis on multiple samples at the same time. 
  Specifically, these objects can be useful for comparing gene-level metrics across multiple samples, such as differential expression analysis and gene set enrichment analysis.
  - Therefore, we make a single, merged `SingleCellExperiment` or `AnnData` object (Fig. 3B) available for each project (without batch-correction or integration).
  - This file contains one object with all raw and normalized gene expression data and metadata for all single-cell and single-nuclei RNA-seq libraries within a given ScPCA project
  - If downloading a project that contains at least one library with CITE-seq, the quantified CITE-seq expression data will also be merged. In SCEs this is provided as an `altExp` within the main object, but for `AnnData` objects, the quantified CITE-seq data is provided as a separate file.

2. The merged object workflow (Fig. 3C and 3D)
  - To create the merged objects, we created an additional stand-alone workflow for merging the output from `scpca-nf`, `merge.nf` (Fig. 3C).
  - Following processing of each `SingleCellExperiment` object with `scpca-nf`, all processed objects from all libraries and samples within a project are input to the merge workflow, which combines all input data into a single merged object.
  - The merged object contains raw and normalized gene expression counts for all cells in all libraries. The same index was used for processing all individual libraries, so the genes found will be the same as in an invididual object.
  - After merging, the top 2000 high-variance genes are calculated by modeling variance within each library included in the merged object.
  - These high-variance genes are used to calculate new PCA coordinates using `batchelor::multiBatchPCA()` and specifying librares as batches.
  - The top 50 PCs were selected and used as input to calculate new UMAP embeddings on the merged object.
  - Similar to `scpca-nf`, the merged `SingleCellExperiment` object is converted to a merged `AnnData` object and both formats are provided as download options on the Portal.
  - Along with the merged objects, for each project, a merged summary report is created and output.
  - This report includes a brief summary of the samples and libraries included in the merged object, including a summary of the type of libraries (e.g., single-cell, single-nuclei, with CITE-seq) and sample diagnoses included in the object.
  - The report also contains a UMAP showing all cells from all libraries included in the merged object. For each library, a separate panel is shown, and cells from that library are colored while all other cells are gray (Fig. 3D).
  


## Materials and Methods

### Data generation
  - how data was generated in different labs using 10X and then sent to the Data Lab

### Data processing (do we need this section?)
  - Mention that all data was processing using `scpca-nf` either by us or external submitters

### Processing single-cell and single-nuclei RNA-seq data with alevin-fry
  - Use of salmon alevin and alevin-fry to process all raw FASTQ files
  - Information on index used
  - Parameter choices for alevin-fry

### Post alevin-fry processing of single-cell and single-nuclei RNA-seq data
  - filtering of empty droplets
  - removal of low quality cells
  - normalization
  - HVG selection
  - PCA and UMAP calculation

### Quantifying gene expression for libraries with CITE-seq or cell hashing
  - How we used alevin-fry to quantify ADT and HTO libraries

### Processing CITE-seq expression data
  - Filtering low quality cells based on ADT data
  - Normalization of ADT data

### Genetic demultiplexing
  - Use of vireo and matching bulk RNA-seq

### HTO demultiplexing
  - Seurat
  - DropletUtils

### Quantification of spatial transcriptomics data
  - Use of space ranger

### Quantification of bulk RNA-seq data
  - Use of salmon

### Cell type annotation
  - Implementation of SingleR and CellAssign
  - Description of metrics used (e.g., what is the delta median and where does the probability come from)

### Generating merged data
  - combining counts data and metadata

### Converting SingleCellExperiment objects to AnnData objects
  - use of zellkonverter

### Code and data availability


## Figure Titles and Legends

![**Figure 1. Overview of ScPCA Portal contents.**](https://raw.githubusercontent.com/AlexsLemonade/scpca-paper-figures/main/figures/compiled_figures/pngs/figure_1.png?sanitize=true){#fig:fig1 width="7in"}

A. Barplots showing sample counts across four main cancer groupings in the ScPCA Portal, with each bar displaying the number of samples for each cancer type.
Each bar is shaded based on the number of samples with each disease timing, and total sample counts for each cancer type are shown to the right of each bar.
B. Barplot showing sample counts across types of modalities present in the ScPCA Portal.
All samples in the portal are shown under the "All Samples" heading.
Samples under the "Samples with additional modalities" heading represent a subset of the total samples with the given additional modality.
Colors shown for each additional modality indicate the suspension type that the single-cell or single-nuclei sample is associated with.
For example, 75 single-cell samples and 43 single-nuclei samples have accompanying Bulk RNA-seq data.
C. Example of a project card as displayed on the "Browse" page of the ScPCA Portal.
This project card is associated with project `SCPCP000009`.
Project cards include information about the number of samples, technologies and modalities, additional sample metadata information, submitter-provided diagnoses, as well as submitter-provided abstract.
Where available, submitter-provided citation information as well as other databases where this data has been deposited are also provided.


![**Figure 2. Overview of the `scpca-nf` workflow.**](https://raw.githubusercontent.com/AlexsLemonade/scpca-paper-figures/main/figures/compiled_figures/pngs/figure_2.png?sanitize=true){#fig:fig2 width="7in"}

A. An overview of `scpca-nf`, the primary workflow for processing single-cell and single-nuclei data for the ScPCA Portal.
Mapping is first performed with `alevin-fry` to generate a gene-by-cell count matrix, which is read into `R` and converted into a `SingleCellExperiment` (`SCE`) object.
This `SCE` object is exported as the `Unfiltered SCE Object` before further post-processing.
Next, empty droplets are filtered out, and the resulting `SCE` is exported as the `Filtered SCE Object`.
The filtered object undergoes additional post-processing, including removing low-quality cells, normalizing counts, and performing dimension reduction including principal components analysis and UMAP calculation.
The object undergoes cell type annotation and is exported as the `Processed SCE Object`.
A summary QC report and a supplemental cell type report are prepared and exported.
Finally, all `SCE` files are converted to `AnnData` format and exported.
Panels B-G show example figures that appear in the summary QC report, shown here for `SCPCL000001`, as follows.
B. The total UMI count for each cell in the `Filtered SCE Object`, ordered by rank.
Points are colored by the percentage of cells that pass the empty droplets filter.
C. The number of genes detected in each cell passing the empty droplets filter against the total UMI count.
Points are colored by the percentage of mitochondrial reads in the cell.
D. `miQC` model diagnostic plot showing the percent of mitochondrial reads in each cell against the number of genes detected in the `Filtered SCE Object`.
Points are colored by the probability that the cell is compromised as determined by `miQC`.
E. The percent of mitochondrial reads in each cell against the number of genes detected in each cell.
Points are colored by whether the cell was kept or removed, as determined by both `miQC` and a minimum unique gene count cutoff, prior to normalization and dimensionality reduction.
F. UMAP embeddings of log-normalized RNA expression values where each cell is colored by the number of genes detected.
G. UMAP embeddings of log-normalized RNA expression values for the top four most variable genes, colored by the given gene's expression.
In the actual summary QC report, the top 12 most highly variable genes are shown.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>


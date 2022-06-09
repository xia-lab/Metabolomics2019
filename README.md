# Metabolomics 2022: Spectra processing, functional integration and covariate adjustment of global metabolomics data using MetaboAnalyst 5.0

![alt text](https://github.com/xia-lab/Metabolomics2019/blob/master/metabolomics2022_xialab.png)

For this tutorial, we will be covering three workflows: 1) Optimized LC-MS spectra processing and peak annotation, 2) functional analysis and integration with other omics data, and 3) exploratory statistical analysis with complex metadata. Details for each workflow are below. 

#### <ins>Before you start this tutorial, please download our latest Protocols for MetaboAnalyst 5.0 from [here](https://www.dropbox.com/s/q2ppaa34xrwm0y1/NP-MetaboAnalyst-2022.pdf?dl=0).</ins>

## 1) LC-MS Spectra Processing and Annotation ([Tutorial](https://dev.metaboanalyst.ca/resources/data/1_Raw%20Spectral%20Processing.pdf))

The aim of this workflow is use the **LC-MS Spectra Processing module** in [MetaboAnalyst](https://www.metaboanalyst.ca/) to analyze the raw spectra data from a real-world experiments. The data was obtained using untargeted metabolomics (Q-Exactive Plus Orbitrap MS in positive ion mode) of blood samples from 6 malaria semi-immune patients and 6 naive controls. 6 pooled QC samples are also included. In this section, students will learn how to run the auto-optimized raw spectra processing workflow.

For this workflow, users could use the 2nd example directly from the module page or optionally download [here](https://www.dropbox.com/s/ift0zrkh0rx3v80/malaria_raw.zip?dl=0).

## 2) Functional Analysis and Integration ([Functional Analysis Tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/SDP_microbiomeanalyst.pptx)) ([MetaboAnalyst Tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/targeted_metabolomics_metaboanalyst.pptx)) ([OmicsNet Tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/using_omicsnet.pptx))

For this workflow, users will first need to download the example data [here](https://github.com/xia-lab/Metabolomics2019/blob/master/crc_data_june23.zip).

The aim of this workflow is to perform statistical analysis and data integration on a subset of colorectal cancer (CRC) samples from a recent paper by [Yachida et al](https://www.nature.com/articles/s41591-019-0458-7). The data consists of shotgun metagenomic + targeted metabolomic analysis of fecal metabolome samples of 149 healthy subjects and 68 Stage 3 or 4 CRC patients. 

First begin by performing shotgun data analysis in [MicrobiomeAnalyst](https://www.microbiomeanalyst.ca/) to obtain a list of significantly enriched KOs. Then use [MetaboAnalyst](https://www.metaboanalyst.ca/) to identify the metabolomic CRC signature. Finally, perform multi-omics data integration using the Network Explorer module within [MetaboAnalyst](https://www.metaboanalyst.ca/) or with [OmicsNet](https://www.omicsnet.ca/).

## 3) Metabolomics + Transcriptomics Data Integration ([NetworkAnalyst Tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/transcriptomics_networkanalyst.pptx)) ([OmicsNet Tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/using_omicsnet.pptx))

For this workflow, users will first need to download the example data [here](https://github.com/xia-lab/Metabolomics2019/blob/master/breast_cancer.zip).

The aim of this workflow is to perform statistical analysis and data integration on a subset of breast cancer samples from a paper by [Terunuma et al](https://www.ncbi.nlm.nih.gov/pubmed/24316975). The data consists of untargeted metabolomics (Metabolon) of 352 known metabolites and microarrary analysis (Affymetrix Human Gene 1.0 ST Array) of the tissue samples. Tissue samples were obtained from 67 human breast tumors and 65 tumor-adjacent noncancerous tissue samples.

To begin, perform microarray data analysis using [NetworkAnalyst](https://www.networkanalyst.ca) to obtain a list of enriched genes. Next, use [MetaboAnalyst](https://www.metaboanalyst.ca/) to obtain the list of enriched metabolites. Note that though this pptx presents a different dataset, the same workflow can be applied to the breast cancer data. Finally, perform multi-omics data integration and 3D visualization using [OmicsNet](https://www.omicsnet.ca/).

## Additional Reference Documents

To understand more background knowledge on metabolomics data analysis further, you can follow these documents/protocols below. 

#### MetaboAnalyst & other omics tools
[Using MetaboAnalyst for Metabolomics Data Analysis](https://www.dropbox.com/s/7uxzeacpgx6zjux/Metabolomics_MetaboAnalyst_Intro_2022.pptx?dl=0)

#### Key statistical concepts & approaches
[General Concepts & Workflow in Omics Data Analysis](https://www.dropbox.com/s/stsp01glned47gg/Metabolomics_Stats_Intro_2022.pptx?dl=0)

#### Protocols of Other Modules in MetaboAnalyst
[Using MetaboAnalyst 4.0 for Comprehensive and Integrative Metabolomics Data Analysis](https://currentprotocols.onlinelibrary.wiley.com/doi/10.1002/cpbi.86)

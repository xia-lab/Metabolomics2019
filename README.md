# Metabolomics 2022: Spectra processing, functional integration and covariate adjustment of global metabolomics data using MetaboAnalyst 5.0

![alt text](https://github.com/xia-lab/Metabolomics2019/blob/master/metabolomics2022_xialab.png)

For this tutorial, we will be covering three workflows: 1) Optimized LC-MS spectra processing and peak annotation, 2) functional analysis and integration with other omics data, and 3) exploratory statistical analysis with complex metadata. Details for each workflow are below. 

### <ins>Before you start this tutorial, please download our latest Protocols for MetaboAnalyst 5.0 [here](https://www.dropbox.com/s/q2ppaa34xrwm0y1/NP-MetaboAnalyst-2022.pdf?dl=0).</ins>

<br/>

## 1) LC-MS Spectra Processing and Annotation

The aim of this workflow is use the **LC-MS Spectra Processing module** in [MetaboAnalyst](https://www.metaboanalyst.ca/) to analyze the raw spectra data from a real-world experiments. The data was obtained using untargeted metabolomics (Q-Exactive Plus Orbitrap MS in positive ion mode) of blood samples from 6 malaria semi-immune patients and 6 naive controls. 6 pooled QC samples are also included. In this section, students will learn how to run the auto-optimized raw spectra processing workflow.

For this workflow, users could use the 2nd example directly from the module page or optionally download [here](https://www.dropbox.com/s/ift0zrkh0rx3v80/malaria_raw.zip?dl=0).

The tutorial of this module is available [here](https://dev.metaboanalyst.ca/resources/data/1_Raw%20Spectral%20Processing.pdf) for further reference. Watch this [video](https://youtu.be/NSwc7Ywvbpw) to see a live demo of raw spectra data processing with MetaboAnalyst.

<br/>

## 2) Functional Analysis and Integration 

The aim of this workflow is to perform functional integration on different Omics data types. Three cases are included: Integration of transcriptomics with targeted metabolomics, transcriptomics with untargeted (global) metabolomics, and multiple metabolomics.

The first example is from a study of COVID-19 [Ariel et al](https://doi.org/10.1016/j.cels.2020.10.003). The data consists of Illumina RNA-Seq + targeted metabolomic analysis (GC-MS) of metabolome samples. The second example is from a study on clinical tolerance on infection of P. vivax between patients (Semi-immune vs. Naïve) from [Li et al](https://doi.org/10.1016/j.redox.2018.04.011). The transcriptomics data is generated by Illumina HiSeq, while metabolomics data is from LC-MS. The third example is from a metabolomics meta-analysis on COVID-19 ([Pang et al.](https://doi.org/10.3390/metabo11010044)).

For this workflow, users will first need to download three example data from the links below: 

- [Transcriptomics Targeted Metabolomics](https://github.com/xia-lab/Metabolomics2019/blob/master/Pathway_Integration_trans_targetedMetabo.zip).

- [Transcriptomics Global Metabolomics](https://github.com/xia-lab/Metabolomics2019/blob/master/Pathway_Integration_trans_globalMetabo.zip).

- [Multiple Global Metabolomics](https://github.com/xia-lab/Metabolomics2019/blob/master/Pathway_Integration_multipleMetabo.zip).

The tutorials for this modules are available: [Joint Pathway Analysis](https://www.metaboanalyst.ca/resources/data/4_Joint%20Pathway%20Analysis.pdf) and [Functional Meta-analysis](https://www.metaboanalyst.ca/resources/data/3_Meta%20Functional%20Analysis.pdf); The video demos of these two modules are available here: [Joint Pathway Analysis](https://youtu.be/CGpIi1RgR9I) and [Functional Meta Analysis](https://youtu.be/LQ8Imra3DgQ).

<br/>

## 3) Metabolomics Statistical Analysis with Complex Metadata

The aim of this workflow is to perform statistical analysis based on complex metadata. Covariate analysis will be used to deal with a metabolomics data, which is highly affected by multiple metadata factos. This study mainly focus on a peak intensity table from a trichloroethylene (TCE) exposure [study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5100622/) for covariate analysis. The data consists of untargeted metabolomics (a peak table) of 352 known metabolites and a metadata. In details, untargeted metabolomics (LC-MS peak intensity) data from plasma samples of 175 individuals to study trichloroethylene (TCE) exposure has been included. Nine metadata - 6 categorical and 3 numeric was organized for analysis.

For this workflow, users will first need to download the example data [here](https://github.com/xia-lab/Metabolomics2019/blob/master/Statistical_analysis_metadata.zip).

<br/>

## Additional Reference Documents

To understand more background knowledge on metabolomics data analysis further, you can follow these documents/protocols below. 

#### MetaboAnalyst & other omics tools
[Using MetaboAnalyst for Metabolomics Data Analysis](https://www.dropbox.com/s/7uxzeacpgx6zjux/Metabolomics_MetaboAnalyst_Intro_2022.pptx?dl=0)

#### Key statistical concepts & approaches
[General Concepts & Workflow in Omics Data Analysis](https://www.dropbox.com/s/stsp01glned47gg/Metabolomics_Stats_Intro_2022.pptx?dl=0)

#### Protocols of Other Modules in MetaboAnalyst
[Using MetaboAnalyst 4.0 for Comprehensive and Integrative Metabolomics Data Analysis](https://currentprotocols.onlinelibrary.wiley.com/doi/10.1002/cpbi.86)

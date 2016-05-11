# CancerGeneAnnotator

## About

A recurrent task in cancer genome analysis is annotation of an observed set of variants for causal implications of their corresponding genes in cancer. This repository contains a few pointers, and wrapper functions to streamline this task.

Two primary external resources for implications of genes in cancer are used. The first one comes from a landmark review study by B. Vogelstein et al [1]. This resource includes two sets of driver genes in cancer: those affected by subtle alterations, and those affected by amplification or homozygous deletion. In each set, genes are divided into tumor suppressor gene (TSG) and oncogene categories. The second resource is the cancer gene census data from COSMIC [2]. In this dataset, implicated cancer genes are annotated by their involvement in germline or somatic state.

Please note that this repository does not include data from the resources above in observance of publisher/institution rights. Academic users are able to obtain excel format files from each of the resources above free of charge, either directly or after registration.

Here, we assume that absolute system paths to the two excel files above are listed in `resource.path` file as follows.

```
Landscapes	/path/to/file/1235122TablesS1-4.xlsx
CGS	/path/to/file/Census_all.xlsx
```

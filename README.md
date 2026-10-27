# Periodontics Datasets

A curated catalogue of publicly discoverable datasets for periodontal research and AI.

**Last reviewed: 27 October 2026.** The catalogue contains **30 records**, including six NHANES cycles. Records are not necessarily independent cohorts. It is a broad, expandable catalogue, **not a claim that every existing dataset has been found**.

This repository contains source links and metadata, not patient files. Download from the original providers. Public descriptions, open files, and unrestricted reuse are different things. File contents and download integrity have not yet been audited.

## Start here

- **Images and text:** Gingivitis image-captioning dataset (1,096 images).
- **Photographic classification:** MIO (765 images).
- **Plaque and clinical records:** two-part orthodontic plaque dataset (148 patients; augmented images included).
- **Bone-loss landmarks:** perio-KPT; access is restricted.
- **Population data:** NHANES periodontal cycles.
- **Longitudinal care:** 883 patients and 11,842 maintenance visits in a newly published PhysioNet dataset (2026-10-05).
- **Molecular research:** GEO gingival expression and single-cell datasets, a salivary BioProject, and a new 40-participant periodontal microbiome deposit.
- **Controlled-access omics:** OMIX017754 is indexed but cannot currently be downloaded.
- **Periodontal tissue mechanobiology:** a Dryad experimental dataset provides figure-level CSVs for gingival stiffness, cytokines and fibroblast responses; it is not a patient-level diagnostic cohort.

Browse the tables below or download [CSV](data/datasets.csv) / [JSON](data/datasets.json). See [research-use guidance](docs/RESEARCH_GUIDE.md), [additional leads and gaps](docs/ADDITIONAL_LEADS.md), and [search and verification log](docs/SEARCH_LOG.md).

## Photographs and multimodal

| Dataset | Size reported | Contents | Access | Terms | Source |
|---|---|---|---|---|---|
| Gingivitis image captioning | 1096 images | Gingivitis labels and three captions per image | Public download listed | CC BY 4.0 | [Record](https://data.mendeley.com/datasets/3253gj88rr/1) |
| MIO v2 | 765 images | Healthy; gingivitis; periodontitis | Open files | Not established from retrieved metadata | [Record](https://zenodo.org/records/22047269) |
| Orthodontic dental plaque multimodal dataset (two parts) | 148 patients; >10000 images including augmentation | Four plaque severity labels; clinical bleeding and hygiene records | Public download listed | CC BY 4.0 | [Record](https://data.mendeley.com/datasets/g8yhdvgjy2/3) |

## Radiographs and bone loss

| Dataset | Size reported | Contents | Access | Terms | Source |
|---|---|---|---|---|---|
| perio-KPT v2 | 192 main images; 15 external images | Periodontal keypoints and bounding boxes; YOLO pose | Restricted files | Non-commercial research only; inspect access agreement | [Record](https://zenodo.org/records/17272200) |
| BoneLoss-PAN769 v2 | 769 panoramic radiographs | Crown polygons and alveolar-ridge annotations; COCO-compatible | Restricted files | Not established from retrieved metadata | [Record](https://zenodo.org/records/21939261) |
| TL-pano v2 | 197 annotated and 114 unannotated panoramics | Tooth layers; numbering; upper/lower alveolar bone | Restricted files | Non-commercial research only; inspect access agreement | [Record](https://zenodo.org/records/18715533) |

## Periodontal ultrasound

| Dataset | Size reported | Contents | Access | Terms | Source |
|---|---|---|---|---|---|
| DentScanNet | 20 healthy and 12 diseased participants | GM; CEJ; ABC; tooth; gingiva; bone masks | Restricted files | Not established from retrieved metadata | [Record](https://zenodo.org/records/20468531) |

## Clinical and epidemiology

| Dataset | Size reported | Contents | Access | Terms | Source |
|---|---|---|---|---|---|
| NHANES periodontal 1999-2000 | See eligible sample in cycle codebook | OHXPERIO | Public XPT files listed | CDC/NCHS data-use terms | [Record](https://wwwn.cdc.gov/nchs/nhanes/Search/DataPage.aspx?Component=Examination) |
| NHANES periodontal 2001-2002 | See eligible sample in cycle codebook | OHXPRL_B + OHXPRU_B | Public XPT files listed | CDC/NCHS data-use terms | [Record](https://wwwn.cdc.gov/nchs/nhanes/Search/DataPage.aspx?Component=Examination) |
| NHANES periodontal 2003-2004 | See eligible sample in cycle codebook | OHXPRL_C + OHXPRU_C | Public XPT files listed | CDC/NCHS data-use terms | [Record](https://wwwn.cdc.gov/nchs/nhanes/Search/DataPage.aspx?Component=Examination) |
| NHANES periodontal 2009-2010 | See eligible sample in cycle codebook | OHXPER_F | Public XPT files listed | CDC/NCHS data-use terms | [Record](https://wwwn.cdc.gov/nchs/nhanes/Search/DataPage.aspx?Component=Examination) |
| NHANES periodontal 2011-2012 | See eligible sample in cycle codebook | OHXPER_G | Public XPT files listed | CDC/NCHS data-use terms | [Record](https://wwwn.cdc.gov/nchs/nhanes/Search/DataPage.aspx?Component=Examination) |
| NHANES periodontal 2013-2014 | See eligible sample in cycle codebook | OHXPER_H | Public XPT files listed | CDC/NCHS data-use terms | [Record](https://wwwn.cdc.gov/nchs/nhanes/Search/DataPage.aspx?Component=Examination) |
| Periodontitis and biological age (NHANES derivative) | Not established | Attachment loss; probing depth; biological age; systemic variables | Public download listed | CC BY 4.0 | [Record](https://data.mendeley.com/datasets/m6f6s5pj62/1) |
| Gingival phenotype and periodontal diagnosis | 60 patients | Gingival thickness; keratinized/attached gingiva; hygiene | Public download listed | CC BY 4.0 | [Record](https://data.mendeley.com/datasets/6g6zz3mwff/1) |
| Oral contraceptives and gingivitis | 60 participants | Bleeding; plaque; inflammation; contraceptive exposure | Public download listed | CC BY 4.0 | [Record](https://data.mendeley.com/datasets/p9rjt3vkjf/1) |
| Plaque-induced gingivitis in Peruvian Amazon schoolchildren | Not established | Gingivitis and risk factors; Excel and instruments described | Public download listed | CC BY 4.0 | [Record](https://data.mendeley.com/datasets/6cyhst5ybw/1) |

## Treatment outcomes

| Dataset | Size reported | Contents | Access | Terms | Source |
|---|---|---|---|---|---|
| Manual versus ultrasonic nonsurgical periodontal treatment | 31 patients | Plaque; pockets; inflammation | Public download listed | CC BY 4.0 | [Record](https://data.mendeley.com/datasets/h7c5cn2drn/1) |
| Ozonated water versus chlorhexidine adjunct | 50 patients | Plaque; pocket depth; gingival inflammation | Public download listed | Not established from retrieved excerpt | [Record](https://data.mendeley.com/datasets/8hjdg4x5x2/1) |
| Adjunctive topical melatonin gel trial | Not established | Trial data; exact variables not established | Public download listed | CC BY 4.0 | [Record](https://data.mendeley.com/datasets/kt4jrtyc5y/1) |
| Supportive Periodontal Therapy Clinical Examination Data v1.0.0 | 883 patients; 11,842 maintenance visits | Longitudinal probing depth, bleeding, recall intervals and smoking; patient-linked visits | Public files | CC BY 4.0 | [Record](https://physionet.org/content/supportive-periodontal-therapy/1.0.0/) |

## Host transcriptomics

| Dataset | Size reported | Contents | Access | Terms | Source |
|---|---|---|---|---|---|
| GSE10334 | 247 samples from 90 patients | Healthy and diseased gingival sites; microarray | Public GEO download listed | NCBI/depositor terms; no CC license inferred | [Record](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE10334) |
| GSE16134 | 310 arrays from 120 patients | Gingival expression and subgingival bacterial context | Public GEO download listed | NCBI/depositor terms; no CC license inferred | [Record](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE16134) |
| GSE23586 | 6 microarrays from 3 patients | Paired healthy and affected gingiva | Public GEO download listed | NCBI/depositor terms; no CC license inferred | [Record](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE23586) |
| GSE294615 | 3 scRNA-seq samples | Periodontal granulation tissue after treatment; UK study | Public NCBI GEO/SRA files listed | NCBI/depositor terms; no CC license inferred | [Record](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE294615) |
| GSE299738 | 3 scRNA-seq samples; associated 49-patient parent study | Granulation tissue and inflamed gingiva; 16S/histology in related parent cohort | Public NCBI GEO/SRA files listed | NCBI/depositor terms; no CC license inferred | [Record](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE299738) |
| OMIX017754 | 6 biopsies: 3 healthy, 3 periodontitis | Human gingival single-cell atlas; neutrophils | **Files unavailable** (controlled-access registration pending) | Not stated | [Record](https://ngdc.cncb.ac.cn/omix/release/OMIX017754) |

## Microbiome

| Dataset | Size reported | Contents | Access | Terms | Source |
|---|---|---|---|---|---|
| PRJNA601054 | Not established | Salivary microbiome; periodontitis; diabetes; metformin | Public BioProject record; runs not tested | NCBI/depositor terms; no CC license inferred | [Record](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA601054) |
| GCF and subgingival plaque 16S in periodontitis and Alzheimer disease | 40 participants (19 vs 21) | Raw and processed 16S profiles described | Public download listed | CC BY 4.0 | [Record](https://data.mendeley.com/datasets/99t29dynkz/1) |

## Experimental periodontal biology

| Dataset | Size reported | Contents | Access | Terms | Source |
|---|---|---|---|---|---|
| Matrix stiffness governs fibroblasts' regulation of gingival immune homeostasis | 318.63 KB; figure-level CSVs, not a patient cohort | Gingival collagen, ECM stiffness, fibroblast cytokines and transcriptomic summaries, hydrogel and explant experiments | Public Dryad files | Dryad standard CC0 terms; verify file-level rights | [Record](https://datadryad.org/dataset/doi:10.5061/dryad.xksn02vw6) |

## Scope and maintenance

Included: periodontal photographs, bone-loss imaging, ultrasound, plaque, gingival phenotype, clinical measurements, longitudinal treatment outcomes, epidemiology, host transcriptomics, single-cell omics, microbiome data and experimental gingival mechanobiology. The two granulation-tissue GEO accessions come from distinct UK and Hong Kong studies; each has only three scRNA-seq samples. Within the Hong Kong study, the 49-patient parent cohort and its 16S, histology and scRNA components must not be counted as independent cohorts. Restricted records are included for discovery and clearly marked.

Apical-periodontitis datasets are primarily endodontic and are excluded from the core periodontal catalogue. General tooth-segmentation or implant-type datasets are supporting resources, not periodontal disease benchmarks.

Missing licenses are recorded as unknown, never assumed to be CC BY. Follow the original dataset citation, version and access conditions. Do not upload private clinical data here.

Contributions: follow [CONTRIBUTING.md](CONTRIBUTING.md). Updates require source review; periodic curator checks and external monitoring may update the catalogue, but neither instant nor exhaustive discovery is guaranteed.

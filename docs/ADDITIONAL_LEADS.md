# Additional leads, related resources and gaps

These entries are **not counted in the 30-record catalogue**. Some are supplementary-only, unconfirmed releases, general-purpose resources or paper-level leads. Do not treat them as ready-to-train datasets.

| Lead | Source | What remains to verify |
|---|---|---|
| SDPSeg stained plaque segmentation: 565 scanner and 1,304 camera images described | https://github.com/anaanaa/SDPSeg-dataset | README still says dataset will come soon; download release unconfirmed |
| Root-coverage prediction from intraoral photographs (Sun et al., 2025) | https://pmc.ncbi.nlm.nih.gov/articles/PMC12699937/ | Data availability and access route not established |
| GEO GSE223328, GSE223924, GSE243173, GSE273165, GSE27993 | https://pmc.ncbi.nlm.nih.gov/articles/PMC12666856/ | Primary accession metadata and subject overlap need verification; paper reports these additional expression cohorts |
| Pooled periodontal oral metagenomics | https://pmc.ncbi.nlm.nih.gov/articles/PMC11575188/ | Retrieve constituent accessions and avoid counting pooled samples as a new independent cohort |
| Macrophage-associated periodontitis biomarkers | https://data.mendeley.com/datasets/sgszyym28d | Deposit describes supplementary tables, not a confirmed raw multi-omics cohort |
| Periodontitis and diabetic kidney disease experimental results | https://data.mendeley.com/datasets/mj43mc6kvy | Separate in-vivo/in-vitro data from human clinical data; inspect files and license |
| hBD3 chiral configurations and periodontitis | https://data.mendeley.com/datasets/3ystwvct9c | Experimental material; inspect biological system, files and license |
| Local sustained-release drugs in periodontitis and diabetes | https://data.mendeley.com/datasets/npnhbbr3mf | Meta-analysis deposit; identify extractable tables; not individual-patient data |
| Gingival recession and quality of life supplement | https://frontiersin.figshare.com/articles/dataset/Data_Sheet_1_The_impact_of_perceived_gingival_recession_on_oral_health-related_quality_of_life_a_cross-sectional_study_of_Saudi_adults_docx/32990837/1 | DOCX supplement; raw participant data not confirmed |
| Dental Implant Periapical Radiograph Dataset | https://data.mendeley.com/datasets/2ghjcpwphd/1 | Sparse metadata; peri-implantitis labels not confirmed |
| Implant panoramic dataset | https://data.mendeley.com/datasets/x4gr6mmwy4/1 | Implant-type classes; not a peri-implantitis benchmark |
| STS-Tooth | https://zenodo.org/records/10597292 | Supporting tooth segmentation; periodontal labels not established |
| Teeth3DS+ | https://crns-smartvision.github.io/teeth3ds | Supporting 3D anatomy; recession/root-coverage labels not established |

## New leads and cautions from 27 October 2026

| Lead | Source | What remains to verify |
|---|---|---|
| Spatially resolved single-cell atlas of periodontal epithelium (2026) | https://pubmed.ncbi.nlm.nih.gov/42805970/ | Paper reports spatial transcriptomics (4 healthy, 6 periodontitis) and scRNA-seq (2 healthy, 6 periodontitis); primary data accession and licence not yet established; **publication lead only** |
| Ferroptosis-driven periodontitis single-cell study (2026) | https://pubmed.ncbi.nlm.nih.gov/42780883/ | Identify primary accession, independently generated versus reused cells, sample IDs, and access; **publication lead only** |
| DentalOPG-1550 v2 (cross-specialty panoramic imaging) | https://data.mendeley.com/datasets/rtt726b26d/2 | 1,550 panoramics and only 38 periodontitis-labeled objects. Included in the general dental imaging catalogue, **not** counted as an independent periodontal-disease cohort in this dedicated list; determine diagnostic label granularity and patient overlap before periodontal benchmarking |
| Periodontal-Reasoning-40k (Hugging Face) | https://huggingface.co/datasets/Wildstash/periodontal-reasoning-40k | 40,000 labelled prompt/completion rows, apparently a synthetic/preference-training resource; provenance, clinical correctness and independence not verified. Do not treat as real patient data or validated diagnostic benchmark |
| InReDD/BoneLoss-PAN769 annotation release comparison | https://physionet.org/content/inredd-pan924-ext-boneloss-769/1.0.0/ | The 2026-09-17 PhysioNet extension reports 21,047 annotations, whereas the Zenodo v2 record reports 21,064; both derive from the same 769-image InReDD cohort. Reconcile audit versions; do **not** count as separate independent datasets |

## Deliberate exclusions

- Apical lesions: https://data.mendeley.com/datasets/kx52tk2ddj/3 — endodontic scope.
- Endodontic microbiome: https://data.mendeley.com/datasets/8f5nmkxxrt — apical disease, not periodontal pocket microbiome.
- Reviews and case-report PDFs without reusable dataset files are not promoted to core datasets.
- Unattributed scraped images and mirrors without clear provenance are not promoted to verified resources.

## Coverage gaps

Continue searching for paired pre/post periodontal surgery photographs, recession segmentation, peri-implantitis labels, furcation-specific datasets, periodontal CBCT annotations, histology, single-cell/spatial omics, proteomics/metabolomics and longitudinal clinical cohorts. No exhaustive coverage claim is made.

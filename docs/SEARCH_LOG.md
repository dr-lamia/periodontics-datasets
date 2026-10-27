# Search and verification log

Search date: 2026-10-26 (Africa/Cairo).

## Sources and strategy

Web discovery used general and site-restricted queries across Mendeley Data, Zenodo, Figshare, NCBI GEO/BioProject, CDC NHANES, GitHub, and primary research papers. Queries included:

- periodontitis dataset mendeley data radiographs gingivitis
- periodontal datasets gingival recession zenodo figshare
- periodontal bone loss dataset public zenodo mendeley
- gingival recession dataset public data
- periodontitis GEO GSE10334 GSE16134 GSE23586
- site:data.mendeley.com/datasets gingivitis
- site:data.mendeley.com/datasets periodontitis
- periodontitis microbiome site:ncbi.nlm.nih.gov/bioproject
- gingival recession dataset zenodo figshare root coverage
- peri implantitis dataset public data
- SDPSeg dataset github

## Evidence and limitations

Catalogue metadata is supported by linked provider pages. GEO direct page opens encountered browser checks; indexed NCBI accession descriptions supplied the three catalogue records. Counts are provider-reported, not independently recounted. Files were not downloaded or inspected. 'Public download listed' means a provider advertises downloads, not that end-to-end downloads were tested.

Zenodo versions were checked: MIO v2 22047269; BoneLoss-PAN769 v2 21939261; TL-pano v2 18715533; perio-KPT v2 17272200. Prior versions were not counted as additional datasets. Orthodontic plaque parts were combined into one record. Six NHANES cycles are counted separately, with upper/lower files combined within each cycle.

This is a targeted discovery catalogue, not a systematic review or exhaustive database export. Search engines can omit records. All unknown terms, sizes and access details remain explicitly unknown. No claim is made that a source's scientific findings have been validated.

## Update: 27 October 2026 (Africa/Cairo)

Searched and cross-checked PhysioNet, Zenodo, Mendeley Data, Figshare, NCBI GEO/SRA/BioProject, ENA, NGDC OMIX, Europe PMC/PubMed, Grand Challenge, NIDCR, Kaggle, Dryad, OSF and Dataverse via targeted web discovery. Some sources yielded no sufficiently verifiable new primary periodontal records; searches were not exhaustive, and primary GEO page rendering was intermittently blocked. No patient files were downloaded. Original provider links and DOI/title/accession checks were compared against all 24 existing catalogue records and general dental-datasets-hub curated/automatic discovery sources.

**Five new verified-metadata records added to the core catalogue (24 → 29):**

- TRT04: [PhysioNet Supportive Periodontal Therapy v1.0.0](https://physionet.org/content/supportive-periodontal-therapy/1.0.0/) (released 2026-10-05; DOI 10.13026/cn9b-2632): 883 patients and 11,842 longitudinal visits, public CC BY 4.0. Clinical visits are nested within patients; source paper 2019 uses the same historical cohort, not new patients. Direct files not independently downloaded.
- MIC02: [Mendeley 16S GCF/subgingival plaque](https://data.mendeley.com/datasets/99t29dynkz/1) (2026-08-06; DOI 10.17632/99t29dynkz.1): 40 participants with periodontitis (19 with Alzheimer disease, 21 cognitively normal); public download listed, CC BY 4.0. Raw and processed 16S described; subject/sample mapping not inspected.
- GEO04: [GSE294615](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE294615), corroborated by [original Journal of Clinical Periodontology paper](https://doi.org/10.1111/jcpe.70048): 3 UK patient-derived scRNA-seq samples; SRA SRP578643, BioProject PRJNA1250847. Original paper explicitly cites accession; re-used comparator cohorts are not independent new patients. NCBI/depositor terms; no CC licence inferred.
- GEO05: [GSE299738](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE299738), corroborated by [NCBI SRA BioSample](https://www.ncbi.nlm.nih.gov/biosample/SAMN44413079) and [original paper](https://doi.org/10.1111/jcpe.70108): 3 scRNA-seq samples, while the related multi-assay parent cohort reports 49 periodontitis patients; BioProject PRJNA1177177, SRA SRP540527. The 16S, histology and scRNA-seq modalities from the parent study share patients; do not multiply cohort counts. NCBI/depositor terms; direct downloads not audited.
- OMX01: [OMIX017754](https://ngdc.cncb.ac.cn/omix/release/OMIX017754) (2026-06-17; PRJCA060690): six human gingival biopsies (3 healthy, 3 periodontitis); primary provider says all files are **unavailable** pending human genetic resource registration. Included as a controlled/unavailable discovery record, not as downloadable training data. Licence not established.

**Review leads only:** [spatial periodontal atlas paper](https://pubmed.ncbi.nlm.nih.gov/42805970/) and [ferroptosis single-cell paper](https://pubmed.ncbi.nlm.nih.gov/42780883/) have no independently confirmed dataset accessions in this check. [DentalOPG-1550 v2](https://data.mendeley.com/datasets/rtt726b26d/2) is a general dental image resource with only 38 periodontitis-labelled objects, not a standalone periodontal cohort. [InReDD PhysioNet](https://physionet.org/content/inredd-pan924-ext-boneloss-769/1.0.0/) and [BoneLoss-PAN769 Zenodo](https://zenodo.org/records/21939261) describe the same source images with annotation count differences (21,047 vs 21,064), so the discrepancy is flagged, not duplicated.

Checks: schema preserved; CSV and JSON record IDs/fields compared; README counts and sections updated. Source metadata and licences were read from provider pages where possible, but no binary download, checksum or clinical annotation audit was performed. A public Lovable preview does not prove website publication or synchronization; verify the Atlas separately.

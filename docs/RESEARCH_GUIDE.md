# Research-use guide

## Match the dataset to the question

| Research question | Starting records | Limitation |
|---|---|---|
| Gingival image captioning or image-text models | IMG01 | Check patient identifiers and split leakage |
| Photographic periodontal classification | IMG02 | Image labels do not substitute for clinical probing/radiographic diagnosis |
| Plaque severity with clinical information | IMG03 | Orthodontic cohort; augmentation inflates image count |
| Bone-loss landmarks and segmentation | RAD01–RAD03 | Restricted access; different annotation tasks |
| Ultrasound landmarks | US01 | Healthy/diseased groups from different sites |
| Risk associations | EPI01–EPI07 | Complex survey design and changing protocols |
| Treatment outcomes | TRT01–TRT03 | Verify raw tables, allocation, follow-up and missingness |
| Gene-expression biomarkers | GEO01–GEO03 | Paired/repeated samples; batch effects; possible cohort overlap |
| Salivary microbial associations | MIC01 | Diabetes and medication are relevant covariates |

## Root coverage and recession

No openly downloadable, paired pre/post root-coverage image benchmark was confirmed in this search. Gingivitis photographs, ultrasound landmarks and gingival phenotype tables are not substitutes for such a dataset. See the root-coverage study lead in ADDITIONAL_LEADS.md; its file availability remains unconfirmed.

## Before modelling

1. Download from the source and record accession/version, date, license and checksum.
2. Count original patients, teeth, sites and images separately. Check annotation schema and missing fields.
3. Split at the patient level before augmentation. Keep repeated visits and paired tissue samples together.
4. Check overlap between original datasets, derivatives, auxiliary data and external validation sets. NHANES derivatives are not independent cohorts.
5. Confirm the clinical target definition and reference standard. Do not equate gingivitis, periodontal bone loss and apical periodontitis.
6. For NHANES, read the cycle codebook, examination eligibility, survey weights, strata and PSU documentation. Earlier and later examination protocols differ.
7. For GEO/SRA, retrieve sample/run manifests and check batch effects and participant overlap before pooling.
8. Preserve provider attribution and restrictions. A paper's open-access license does not automatically license its patient data.

These are research resources, not validated clinical decision tools.

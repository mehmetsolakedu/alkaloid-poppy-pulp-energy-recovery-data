# Final Raw Data / Replicate / Statistics Audit and Correction Report

Date: 2026-07-04

## Scope

This audit checked whether the manuscript can safely make replicate-level or inferential statistical claims after recovering raw analytical files from Google Drive. The audit used the recovered local raw-data package, the extracted XRF/FTIR/EA/TGA/ICP materials, the Turkish laboratory report, and the corrected manuscript version:

- Raw package: `google_drive_raw_data_20260704`
- Corrected manuscript: `alkaloid_poppy_pulp_Q1_science_Q1_language_final_v18_raw_stat_corrected_20260704.docx`
- Render QA folder: `render_v18_raw_stat_corrected`

## Raw Data Pulled Into The Local Folder

The Google Drive raw-data materials were copied into the manuscript folder.

- Total files in `google_drive_raw_data_20260704`: 60
- Folder size: approximately 41 MB
- Checksum manifest: `google_drive_raw_data_20260704/SHA256SUMS.txt`
- Checksum entries: 60

Subfolder inventory:

- `direct_main_folder`: 9 files
- `additional_candidates`: 9 top-level files, plus extracted FTIR contents
- `analysis_reports`: 1 DOCX report
- `photos`: 37 image files

## Evidence Found

Recovered analytical files include:

- 13 workbook files in the audit set
- 8 TGA workbooks
- 4 ICP workbook copies
- 1 EA workbook converted from the original `.xls`
- 2 `.dpt` FTIR spectra
- 3 FTIR `.zip` packages
- 3 PDF/report-style files in the scanned evidence set
- Extracted XRF workbooks from the `.rar` package
- `MEHMET SOLAK PAKET 8 ANALIZI.docx` laboratory report

The ICP files contain technical repeat/reading structure. The Turkish analysis report also states that ICP-OES prepared samples were read three times and calculations were made from the average. However, the four ICP workbooks are duplicate copies by checksum, so they do not represent four independent experiments.

The TGA workbooks contain repeated curve-like analytical files for sample codes, but the current evidence does not yet provide a fully mapped treatment-level replicate design across all manuscript outputs.

The FTIR `.dpt` files and zip packages support spectrum-level raw evidence. They do not, by themselves, support inferential statistics for the manuscript's fuel, physical-property, ENplus or nutrient claims.

## Main Audit Decision

The recovered package contains partial technical-repeat evidence, especially for selected ICP-OES readings and repeated analytical files. It does not contain a complete, consistently mapped replicate-level variance dataset for proximate analysis, ultimate analysis, calorimetry, pellet physical properties, ENplus comparisons, nutrient screening and all torrefaction indicators.

Therefore the safe manuscript position is descriptive statistics only:

- no p-values
- no confidence intervals
- no inferential significance claims
- changes interpreted as measured differences and practical-quality boundaries

## Critical Data Correction

The recovered elemental-analysis file showed that the manuscript nitrogen values were incorrect.

Recovered EA values:

- PP mapped to N23_1958: N = 0.510%, C = 27.218%, H = 5.174%
- T-PP mapped to N23_1959: N = 0.607%, C = 29.967%, H = 4.783%

The manuscript's C and H values already matched N23_1958 and N23_1959, so the correct nitrogen values are 0.51% and 0.61%, not 1.3% and 1.22%.

This also changes the nitrogen torrefaction indicator:

- Old DN: 20.01%
- Corrected apparent DN: -1.49%

The corrected value should be interpreted as apparent retention/concentration within the descriptive dataset, not as a statistically tested nitrogen-removal response.

## Automatic Manuscript Corrections Applied

The following corrections were applied automatically in the v18 DOCX:

- Table 2 / ultimate-proximate table: N changed to `0.51 / 0.61`
- Table 5 / torrefaction indicators: DN changed to `-1.49`
- ENplus comparison table: N changed to `0.51 / 0.61`
- Nutrient table: N changed from unsupported `N 13000` to `N 5100`
- Methods/statistics paragraph revised to state descriptive treatment only
- Discussion paragraph revised to avoid nitrogen-removal overclaim
- ENplus discussion revised: nitrogen is below B-class threshold after correction, but remains an A1/A2 constraint
- Limitations and conclusion revised to state that complete replicate-level variance is not available across all measurements

## Render And Text QA

The corrected DOCX was rendered successfully to PDF and 30 PNG pages:

- PDF: `render_v18_raw_stat_corrected/alkaloid_poppy_pulp_Q1_science_Q1_language_final_v18_raw_stat_corrected_20260704.pdf`
- PNG pages: 30

Visual spot-checks were performed on the pages containing the revised statistics paragraph, Table 2, Table 5, ENplus table and nutrient table. No visible table overflow or page corruption was observed.

DOCX/PDF text verification confirmed:

- `Data treatment was descriptive` is present
- `0.51% to 0.61%` is present
- `DN (%) | N/A | -1.49` is present
- `N 5100` is present
- `below the B-class threshold` is present
- stale `20.01` is absent
- stale `N 13000` is absent
- stale `13,000` is absent
- stale old B-class-limit failure wording is absent
- stale inferential nitrogen-removal wording is absent

## Residual Risks Left Outside This Pass

The XRF material confirms several ash/mineral entries, but some K/Ca and basis-conversion relationships remain ambiguous between ash-basis and whole-material-basis reporting. Those values were not automatically changed in this pass because a wrong basis conversion would create a new error.

The TGA repeated files should not be used for variance or statistical testing until sample-code mapping, run conditions and replicate roles are explicitly reconstructed.

The current manuscript is safer after this pass, but the next high-value audit is an XRF/ICP basis audit for Table 9 and the nutrient-recovery section.

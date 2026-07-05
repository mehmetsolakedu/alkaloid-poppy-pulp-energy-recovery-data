# Raw Replicate / Statistical Audit With Google Drive Raw Data

Date: 2026-07-04

## Scope

- Raw source folder: `google_drive_raw_data_20260704/`
- Manuscript checked: `alkaloid_poppy_pulp_Q1_science_Q1_language_final_v17_20260704.docx`
- Audit question: whether the newly recovered raw files support replicate-level statistics, or only measured/processed single-run evidence and bounded descriptive claims.

## High-Level File Counts

- Spreadsheet workbooks read: 13
- FTIR `.dpt` files read: 2
- ZIP archives inventoried: 3
- PDF reports sampled: 3
- Workbook classes: `{'TGA': 8, 'ICP': 4, 'EA': 1}`

## Workbook Evidence Summary

| Class | File | Sheets | Curve-like sheets | Sample codes seen | Stat/replicate traces | Interpretation |
|---|---|---:|---:|---|---|---|
| TGA | `sonuc-N23-1956-TGA01-8cbb.xlsx` | 2 | 1 | - | - | instrument curve workbook; supports thermal-profile extraction, not replicate statistics by itself |
| TGA | `sonuc-N23-1956-TGA01-c9e2.xlsx` | 2 | 1 | - | - | instrument curve workbook; supports thermal-profile extraction, not replicate statistics by itself |
| ICP | `sonuc-N23-1957-ICP01-d786.xlsx` | 1 | 0 | N23-1956, N23-1957, N23-1958, N23-1959 | variation:8 | analysis result workbook; supports reported composition values, not replicate statistics by itself |
| TGA | `sonuc-N23-1957-TGA01-424d.xlsx` | 2 | 1 | - | - | instrument curve workbook; supports thermal-profile extraction, not replicate statistics by itself |
| TGA | `sonuc-N23-1957-TGA01-ac1a.xlsx` | 2 | 1 | - | - | instrument curve workbook; supports thermal-profile extraction, not replicate statistics by itself |
| ICP | `sonuc-N23-1958-ICP01-0c74.xlsx` | 1 | 0 | N23-1956, N23-1957, N23-1958, N23-1959 | variation:8 | analysis result workbook; supports reported composition values, not replicate statistics by itself |
| ICP | `sonuc-N23-1959-ICP01-a0bf.xlsx` | 1 | 0 | N23-1956, N23-1957, N23-1958, N23-1959 | variation:8 | analysis result workbook; supports reported composition values, not replicate statistics by itself |
| TGA | `sonuc-N23-1959-TGA01-d45b.xlsx` | 2 | 1 | - | - | instrument curve workbook; supports thermal-profile extraction, not replicate statistics by itself |
| ICP | `sonuc-N23-1956-ICP01-775e (3).xlsx` | 1 | 0 | N23-1956, N23-1957, N23-1958, N23-1959 | variation:8 | analysis result workbook; supports reported composition values, not replicate statistics by itself |
| TGA | `sonuc-N23-1958-TGA01-2a19.xlsx` | 2 | 1 | - | - | instrument curve workbook; supports thermal-profile extraction, not replicate statistics by itself |
| TGA | `sonuc-N23-1958-TGA01-6b9d (1).xlsx` | 2 | 1 | - | - | instrument curve workbook; supports thermal-profile extraction, not replicate statistics by itself |
| TGA | `sonuc-N23-1959-TGA01-46a5.xlsx` | 2 | 1 | - | - | instrument curve workbook; supports thermal-profile extraction, not replicate statistics by itself |
| EA | `sonuc-N23-1956-EA01-6516 (2).xlsx` | 1 | 0 | N23-1956, N23-1957, N23-1958, N23-1959 | - | analysis result workbook; supports reported composition values, not replicate statistics by itself |

## First Non-Empty Rows By Workbook

### `sonuc-N23-1956-TGA01-8cbb.xlsx`

- Sheet `1956.tgd`: max_row=39623, max_column=10, nonempty_rows_scanned=24998, numeric_cells_scanned=124898, likely_curve_data=True
  - R1: Module | STA
  - R2: Channel | GAA0748000002
  - R3: Data Name | 1956.tgd
  - R4: Measurement Time | 7/4/2023 3:18:53 PM
  - R5: Sample Name | 1956
  - R6: Sample Weight | 7.545 | mg
- Sheet `Chart`: max_row=1, max_column=1, nonempty_rows_scanned=0, numeric_cells_scanned=0, likely_curve_data=False

### `sonuc-N23-1956-TGA01-c9e2.xlsx`

- Sheet `1956.tgd`: max_row=117623, max_column=10, nonempty_rows_scanned=24998, numeric_cells_scanned=124898, likely_curve_data=True
  - R1: Module | STA
  - R2: Channel | GAA0748000002
  - R3: Data Name | 1956.tgd
  - R4: Measurement Time | 7/18/2023 3:24:02 PM
  - R5: Sample Name | 1956
  - R6: Sample Weight | 10.341 | mg
- Sheet `Chart`: max_row=1, max_column=1, nonempty_rows_scanned=0, numeric_cells_scanned=0, likely_curve_data=False

### `sonuc-N23-1957-ICP01-d786.xlsx`

- Sheet `Sayfa1`: max_row=49, max_column=19, nonempty_rows_scanned=39, numeric_cells_scanned=335, likely_curve_data=False
  - R10: NOT: SEYRELTME FAKTÖRÜ 100'DÜR VE TÜM SONUÇLARIN SEYRELTME FAKTÖRÜ İLE (100 İLE) ÇARPILMASI GEREKMEKTEDİR. PPM VE PPB Bİ
  - R11: Sample | Type | Cr | Cu | Zn | Cd | Pb | As | S |  | Sample | Type | Na | S | Si | Mg
  - R12:  |  | ppb | ppb | ppb | ppb | ppb | ppb | ppb |  |  |  | ppm | ppm | ppm | ppm
  - R13: N23-1956 | 1 | 16806 | 342425 | 68435 | 3802 | 34169 | 16643 | 1583.12 |  | N23-1956 | 1 | 7876 | 0.391 | < -2.899 | 24620
  - R14:  | 2 | 18087 | 343627 | 72009 | 3898 | 37125 | 18358 | 1657.74 |  |  | 2 | 7942 | 0.427 | < -2.897 | 24938
  - R15:  | 3 | 21273 | 342316 | 73559 | 4008 | 37572 | 19202 | 1702.65 |  |  | 3 | 7915 | 0.441 | < -3.015 | 24886

### `sonuc-N23-1957-TGA01-424d.xlsx`

- Sheet `1957.tgd`: max_row=39623, max_column=10, nonempty_rows_scanned=24998, numeric_cells_scanned=124898, likely_curve_data=True
  - R1: Module | STA
  - R2: Channel | GAA0748000002
  - R3: Data Name | 1957.tgd
  - R4: Measurement Time | 7/5/2023 11:53:22 AM
  - R5: Sample Name | 1957
  - R6: Sample Weight | 7.065 | mg
- Sheet `Chart`: max_row=1, max_column=1, nonempty_rows_scanned=0, numeric_cells_scanned=0, likely_curve_data=False

### `sonuc-N23-1957-TGA01-ac1a.xlsx`

- Sheet `1957.tgd`: max_row=117622, max_column=10, nonempty_rows_scanned=24998, numeric_cells_scanned=124898, likely_curve_data=True
  - R1: Module | STA
  - R2: Channel | GAA0748000002
  - R3: Data Name | 1957.tgd
  - R4: Measurement Time | 7/19/2023 2:50:39 PM
  - R5: Sample Name | 1957
  - R6: Sample Weight | 7.097 | mg
- Sheet `Chart`: max_row=1, max_column=1, nonempty_rows_scanned=0, numeric_cells_scanned=0, likely_curve_data=False

### `sonuc-N23-1958-ICP01-0c74.xlsx`

- Sheet `Sayfa1`: max_row=49, max_column=19, nonempty_rows_scanned=39, numeric_cells_scanned=335, likely_curve_data=False
  - R10: NOT: SEYRELTME FAKTÖRÜ 100'DÜR VE TÜM SONUÇLARIN SEYRELTME FAKTÖRÜ İLE (100 İLE) ÇARPILMASI GEREKMEKTEDİR. PPM VE PPB Bİ
  - R11: Sample | Type | Cr | Cu | Zn | Cd | Pb | As | S |  | Sample | Type | Na | S | Si | Mg
  - R12:  |  | ppb | ppb | ppb | ppb | ppb | ppb | ppb |  |  |  | ppm | ppm | ppm | ppm
  - R13: N23-1956 | 1 | 16806 | 342425 | 68435 | 3802 | 34169 | 16643 | 1583.12 |  | N23-1956 | 1 | 7876 | 0.391 | < -2.899 | 24620
  - R14:  | 2 | 18087 | 343627 | 72009 | 3898 | 37125 | 18358 | 1657.74 |  |  | 2 | 7942 | 0.427 | < -2.897 | 24938
  - R15:  | 3 | 21273 | 342316 | 73559 | 4008 | 37572 | 19202 | 1702.65 |  |  | 3 | 7915 | 0.441 | < -3.015 | 24886

### `sonuc-N23-1959-ICP01-a0bf.xlsx`

- Sheet `Sayfa1`: max_row=49, max_column=19, nonempty_rows_scanned=39, numeric_cells_scanned=335, likely_curve_data=False
  - R10: NOT: SEYRELTME FAKTÖRÜ 100'DÜR VE TÜM SONUÇLARIN SEYRELTME FAKTÖRÜ İLE (100 İLE) ÇARPILMASI GEREKMEKTEDİR. PPM VE PPB Bİ
  - R11: Sample | Type | Cr | Cu | Zn | Cd | Pb | As | S |  | Sample | Type | Na | S | Si | Mg
  - R12:  |  | ppb | ppb | ppb | ppb | ppb | ppb | ppb |  |  |  | ppm | ppm | ppm | ppm
  - R13: N23-1956 | 1 | 16806 | 342425 | 68435 | 3802 | 34169 | 16643 | 1583.12 |  | N23-1956 | 1 | 7876 | 0.391 | < -2.899 | 24620
  - R14:  | 2 | 18087 | 343627 | 72009 | 3898 | 37125 | 18358 | 1657.74 |  |  | 2 | 7942 | 0.427 | < -2.897 | 24938
  - R15:  | 3 | 21273 | 342316 | 73559 | 4008 | 37572 | 19202 | 1702.65 |  |  | 3 | 7915 | 0.441 | < -3.015 | 24886

### `sonuc-N23-1959-TGA01-d45b.xlsx`

- Sheet `1959.tgd`: max_row=117623, max_column=10, nonempty_rows_scanned=24998, numeric_cells_scanned=124898, likely_curve_data=True
  - R1: Module | STA
  - R2: Channel | GAA0748000002
  - R3: Data Name | 1959.tgd
  - R4: Measurement Time | 7/21/2023 2:27:10 PM
  - R5: Sample Name | 1959
  - R6: Sample Weight | 9.953 | mg
- Sheet `Chart`: max_row=1, max_column=1, nonempty_rows_scanned=0, numeric_cells_scanned=0, likely_curve_data=False

### `sonuc-N23-1956-ICP01-775e (3).xlsx`

- Sheet `Sayfa1`: max_row=49, max_column=19, nonempty_rows_scanned=39, numeric_cells_scanned=335, likely_curve_data=False
  - R10: NOT: SEYRELTME FAKTÖRÜ 100'DÜR VE TÜM SONUÇLARIN SEYRELTME FAKTÖRÜ İLE (100 İLE) ÇARPILMASI GEREKMEKTEDİR. PPM VE PPB Bİ
  - R11: Sample | Type | Cr | Cu | Zn | Cd | Pb | As | S |  | Sample | Type | Na | S | Si | Mg
  - R12:  |  | ppb | ppb | ppb | ppb | ppb | ppb | ppb |  |  |  | ppm | ppm | ppm | ppm
  - R13: N23-1956 | 1 | 16806 | 342425 | 68435 | 3802 | 34169 | 16643 | 1583.12 |  | N23-1956 | 1 | 7876 | 0.391 | < -2.899 | 24620
  - R14:  | 2 | 18087 | 343627 | 72009 | 3898 | 37125 | 18358 | 1657.74 |  |  | 2 | 7942 | 0.427 | < -2.897 | 24938
  - R15:  | 3 | 21273 | 342316 | 73559 | 4008 | 37572 | 19202 | 1702.65 |  |  | 3 | 7915 | 0.441 | < -3.015 | 24886

### `sonuc-N23-1958-TGA01-2a19.xlsx`

- Sheet `1958.tgd`: max_row=117622, max_column=10, nonempty_rows_scanned=24998, numeric_cells_scanned=124898, likely_curve_data=True
  - R1: Module | STA
  - R2: Channel | GAA0748000002
  - R3: Data Name | 1958.tgd
  - R4: Measurement Time | 7/20/2023 2:26:53 PM
  - R5: Sample Name | 1958
  - R6: Sample Weight | 10.692 | mg
- Sheet `Chart`: max_row=1, max_column=1, nonempty_rows_scanned=0, numeric_cells_scanned=0, likely_curve_data=False

### `sonuc-N23-1958-TGA01-6b9d (1).xlsx`

- Sheet `1958.tgd`: max_row=39622, max_column=10, nonempty_rows_scanned=24998, numeric_cells_scanned=124898, likely_curve_data=True
  - R1: Module | STA
  - R2: Channel | GAA0748000002
  - R3: Data Name | 1958.tgd
  - R4: Measurement Time | 7/5/2023 3:20:23 PM
  - R5: Sample Name | 1958
  - R6: Sample Weight | 14.43 | mg
- Sheet `Chart`: max_row=1, max_column=1, nonempty_rows_scanned=0, numeric_cells_scanned=0, likely_curve_data=False

### `sonuc-N23-1959-TGA01-46a5.xlsx`

- Sheet `1959.tgd`: max_row=39623, max_column=10, nonempty_rows_scanned=24998, numeric_cells_scanned=124898, likely_curve_data=True
  - R1: Module | STA
  - R2: Channel | GAA0748000002
  - R3: Data Name | 1959.tgd
  - R4: Measurement Time | 7/7/2023 12:22:49 PM
  - R5: Sample Name | 1959
  - R6: Sample Weight | 11.752 | mg
- Sheet `Chart`: max_row=1, max_column=1, nonempty_rows_scanned=0, numeric_cells_scanned=0, likely_curve_data=False

### `sonuc-N23-1956-EA01-6516 (2).xlsx`

- Sheet `Element%`: max_row=114, max_column=7, nonempty_rows_scanned=6, numeric_cells_scanned=16, likely_curve_data=False
  - R2:  | Autorun: (Element%)
  - R7:  | Pos | Sample Name | (N) % | (C) % | (H) %
  - R8:  | 1 | N23_1956 | 0.916 | 36.454 | 5.926
  - R9:  | 2 | N23_1957 | 1.048 | 40.19 | 5.235
  - R10:  | 3 | N23_1958 | 0.51 | 27.218 | 5.174
  - R11:  | 4 | N23_1959 | 0.607 | 29.967 | 4.783

## FTIR Raw Spectrum Evidence

- `kfu-1956.dpt` from `sonuc-N23-1957-FT01-ed19`: 3530 numeric rows; column distribution {2: 3530}; sha256 `30a6cea1b592...`
- `kfu-1956.dpt` from `sonuc-N23-1957-FT01-ed19 (1)`: 3530 numeric rows; column distribution {2: 3530}; sha256 `30a6cea1b592...`

## Archive Evidence

- `sonuc-N23-1957-FT01-ed19.zip`: 2 entries; first entries: kfu-1956.dpt, kfu-1956.pdf
- `sonuc-N23-1959-FT01-d124 (1).zip`: 2 entries; first entries: alko_1958.dpt, alko_1958.pdf
- `sonuc-N23-2225-FT01-4aa5.zip`: 2 entries; first entries: talko-1959.dpt, talko-1959.pdf

## Manuscript Statistical-Language Scan

- Tables detected in DOCX: 15
- Captions detected: 8
- Statistical/replicate language hits: `{'variation': 5, 'replicate': 4, 'p-value': 1}`

Representative hits:
- Paragraph 18 [variation]: This residue is not a marginal laboratory material. In 2024, the Official Gazette of the Republic of Turkey announced a tender for approximately 50,000 t (± 10%) of poppy pulp [13]. The available tender documentation and field observation used in this study do not establish a dedicated valorization route for PP; instead, the material is visibly stored near the factory area (Figure 1). The combination of large seasonal quantity, high initial moisture and limited documented utilization options cre
- Paragraph 34 [replicate]: The torrefaction temperature was selected through preliminary screening experiments between 250 and 300 °C for 60 min. Treatments below 250 °C did not produce meaningful changes in the targeted material properties, whereas 300 °C produced the highest fixed carbon value in the screening set (Table 1). Because replicate variability, mass yield, HHV and mechanical-quality screening were not available for all temperatures, this condition should be interpreted as a selected screening endpoint rather 
- Paragraph 38 [variation]: Moisture, ash, volatile matter and fixed carbon were determined according to the relevant solid-biofuel standards. Moisture was measured by oven drying, ash by incineration at 550 ± 10 °C, volatile matter by heating a covered crucible under the specified standard conditions, and fixed carbon by difference from the measured proximate fractions [17-22]. Higher heating value (HHV) was measured using an IKA C200 bomb calorimeter. Because net calorific value (NCV) as received was not separately calcu
- Paragraph 39 [p-value]: Data treatment was descriptive. The available dataset supports directional and magnitude comparisons between PP and T-PP, but raw replicate-level variance was not available for all measured properties. Therefore, no p-values, confidence intervals or inferential significance tests are reported; differences are interpreted only as measured changes and practical-quality boundaries.
- Paragraph 39 [replicate]: Data treatment was descriptive. The available dataset supports directional and magnitude comparisons between PP and T-PP, but raw replicate-level variance was not available for all measured properties. Therefore, no p-values, confidence intervals or inferential significance tests are reported; differences are interpreted only as measured changes and practical-quality boundaries.
- Paragraph 43 [variation]: Ash content was determined according to ISO 18122:2022 [19]. Samples of 1 ± 0.2 g were dried at 105 ± 2 °C and then incinerated at 550 ± 10 °C until complete combustion. Ash percentage was calculated from the remaining residue mass [20].
- Paragraph 47 [variation]: Volatile matter was determined according to ISO 18123:2023 [21]. At least 1 g of sample was placed in a covered ceramic crucible, isolated from ambient air, and heated at 900 ± 10 °C for 7 min [22].
- Paragraph 93 [replicate]: The physical data show a second trade-off created by torrefaction. Length decreased from 18.72 to 17.12 mm, diameter from 6.46 to 6.36 mm, and single pellet weight from 0.79 to 0.64 g, reflecting shrinkage and mass loss during thermal treatment. More importantly for practical handling, mechanical durability decreased from 92.98% to 87.14% and bulk density from 633 to 543 kg m⁻³. The descriptive differences in Table 7 therefore have applied meaning: torrefaction produced chemical upgrading but we
- Paragraph 102 [replicate]: The present work is a characterization and pathway-screening study rather than a final application trial. It establishes, within the available descriptive dataset, how torrefaction changes fuel quality, ash concentration, combustion indicators and nutrient composition, but it does not include blending trials, de-ashing pretreatments, ash-fusion tests, long-term combustion tests, plant-growth trials, soil incubation, leaching assays or residual-alkaloid safety analysis. It also does not report ra
- Table 14 row 2 [variation]: 1 | Diameter | mm | ISO 17829:2015 | 6 ± 1 - 8 ± 1 | 6 ± 1 - 8 ± 1 | 6 ± 1 - 8 ± 1 | 6.46 | 6.36

## Audit Conclusion

The recovered Drive files materially improve evidence availability: they provide raw/processed instrument outputs for TGA, FTIR, ICP/XRF/EA-style composition and photos. However, this audit did not find a complete replicate design table, treatment-level replicate matrix, sample-randomization sheet, or explicit `n`, SD/SE, ANOVA or p-value support in the raw files.

Therefore, the current manuscript should remain statistically bounded: no p-values, no significance claims, no inferential comparisons, and no replicate-derived uncertainty claims unless a later file explicitly maps replicate runs to each manuscript treatment.

## Safe Automatic-Edit Implication

- Keep descriptive comparisons only.
- Add/keep a transparent data-availability statement that raw/processed instrument output files are available in the recovered local raw-data folder.
- Do not reintroduce statistical significance language.
- If manuscript text still says or implies replicate-level inference, change it to single-study descriptive evidence.


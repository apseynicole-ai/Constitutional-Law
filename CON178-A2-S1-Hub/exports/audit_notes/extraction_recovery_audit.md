# Extraction Recovery Audit

## 1. Purpose

This audit checks failed or empty Markdown conversions so no examinable CON178 A2 material is accidentally lost.

The audit does not clean, summarise, merge, rename, delete, overwrite raw files, or build the HTML hub. Existing failed Markdown files remain in place. Recovery attempts were written only to `CON178-A2-S1-Hub/sources_md/_extraction_recovery/`.

## 2. Failed / Empty Markdown Review

| Markdown file | Current line count | Current usable? | Matching raw source found? | Raw source path | Recovery attempted | Recovery output | Recovery status | Action needed |
| --- | ---: | --- | --- | --- | --- | --- | --- | --- |
| `sources_md/01_theme_1_intro/an_introduction_to_law_textbook_scan_1.md` | 0 | No | Yes | `./An Introduction to Law Textbook Scan (1).pdf` | MarkItDown retry; pdfminer fallback | `an_introduction_to_law_textbook_scan_1_markitdown.md`; `an_introduction_to_law_textbook_scan_1_pdfminer.md` | NEEDS OCR | MarkItDown produced 0 bytes; pdfminer produced only 3 bytes. Treat as likely image/scan or otherwise non-extractable without OCR. |
| `sources_md/01_theme_1_intro/section_2_2_constitutional_law_in_context.md` | 0 | No | Yes | `./Section 2.2 Constitutional Law in Context.pdf` | MarkItDown retry; pdfminer fallback | `section_2_2_constitutional_law_in_context_markitdown.md`; `section_2_2_constitutional_law_in_context_pdfminer.md` | NEEDS OCR | MarkItDown produced 0 bytes; pdfminer produced only 14 bytes. Important Theme 1 constitutionalism source must not be treated as converted. |
| `sources_md/01_theme_1_intro/understanding_south_africa.md` | 0 | No | Yes | `./Understanding South Africa.pdf` | MarkItDown retry; pdfminer fallback | `understanding_south_africa_markitdown.md`; `understanding_south_africa_pdfminer.md` | NEEDS OCR | MarkItDown produced 0 bytes; pdfminer produced only 13 bytes. Needs OCR or manual reconstruction. |
| `sources_md/02_theme_2_history/currie_and_de_waal_pages_46_51.md` | 0 | No | Yes | `./Currie and De Waal pages 46-51.pdf` | MarkItDown retry; pdfminer fallback | `currie_and_de_waal_pages_46_51_markitdown.md`; `currie_and_de_waal_pages_46_51_pdfminer.md` | NEEDS OCR | MarkItDown produced 0 bytes; pdfminer produced only 7 bytes. Needs OCR or manual reconstruction. |
| `sources_md/02_theme_2_history/reservation_of_separate_amenities_act_49_of_1953.md` | 0 | No | Yes | `./Reservation-of-Separate-Amenities-Act-49-of-1953.pdf` | MarkItDown retry; pdfminer fallback | `reservation_of_separate_amenities_act_49_of_1953_markitdown.md`; `reservation_of_separate_amenities_act_49_of_1953_pdfminer.md` | NEEDS OCR | MarkItDown produced 0 bytes; pdfminer produced only 3 bytes. Needs OCR or manual reconstruction. |
| `sources_md/03_theme_3_negotiated_revolution/de_vos_freedman_pg_15_31.md` | 0 | No | Yes | `./De Vos  Freedman pg 15-31.pdf` | MarkItDown retry; pdfminer fallback | `de_vos_freedman_pg_15_31_markitdown.md`; `de_vos_freedman_pg_15_31_pdfminer.md` | NEEDS OCR | MarkItDown produced 0 bytes; pdfminer produced only 17 bytes. Critical Theme 3 reading must be recovered before hub building. |
| `sources_md/04_theme_4_core_principles/currie_de_waal_pg_10_21.md` | 0 | No | Yes | `./Currie  De Waal pg 10-21.pdf` | MarkItDown retry; pdfminer fallback | `currie_de_waal_pg_10_21_markitdown.md`; `currie_de_waal_pg_10_21_pdfminer.md` | NEEDS OCR | MarkItDown produced 0 bytes; pdfminer produced only 13 bytes. Needs OCR or manual reconstruction. |
| `sources_md/04_theme_4_core_principles/de_vos_freedman_pages_453_455.md` | 0 | No | Yes | `./De Vos Freedman pages 453-455.pdf` | MarkItDown retry; pdfminer fallback | `de_vos_freedman_pages_453_455_markitdown.md`; `de_vos_freedman_pages_453_455_pdfminer.md` | NEEDS OCR | MarkItDown produced 0 bytes; pdfminer produced only 3 bytes. Important Theme 4 prescribed reading must be recovered. |
| `sources_md/04_theme_4_core_principles/economic_freedom_fighters_v_speaker_national_assembly_2016.md` | 0 | Partly, but unsafe as-is | Yes | `./ECONOMIC_FREEDOM_FIGHTERS_v_SPEAKER,_NATIONAL_ASSEMBLY_AND_OTHERS_2016_(3)_SA_580_(CC).pdf` | MarkItDown retry; pdfminer fallback | `economic_freedom_fighters_v_speaker_national_assembly_2016_markitdown.md`; `economic_freedom_fighters_v_speaker_national_assembly_2016_pdfminer.md` | PARTIALLY RECOVERED | Both recovery outputs contain about 65 KB of legal text, but as a single-line blob with poor spacing. Needs formatting recovery before replacing failed Markdown. |

Extractor availability noted during audit:

- `pdftotext`: not available in the current shell path.
- `pypdf`: not available in `.venv`.
- PyMuPDF / `fitz`: not available in `.venv`.
- `pdfminer`: available in `.venv` and used as the Python fallback extraction method.

## 3. Lecture Source Search Results

| Required lecture/source | Found? | Path if found | Action needed | Priority |
| --- | --- | --- | --- | --- |
| Theme 1 lecture 3 | No | Not found | User should provide Theme 1 lecture 3 slides/notes if examinable. | CRITICAL |
| Theme 3 lectures 10-13 | No | Not found | User should provide Theme 3 lecture slides/notes for lectures 10-13. | CRITICAL |
| Theme 2 lecture 9 | No | Not found | User should provide Theme 2 lecture 9 if it bridges into Theme 3. | HIGH |
| Theme 4 lecture 14 | No | Not found | User should provide if examinable. | HIGH |
| Theme 4 lecture 15 | No | Not found | User should provide if examinable. | HIGH |
| Theme 4 lecture 16 | No | Not found | User should provide if examinable. | HIGH |
| Theme 4 lecture 17 | No | Not found | User should provide if examinable. | HIGH |
| Theme 4 lecture 18 | No | Not found | User should provide if examinable. | HIGH |
| Theme 4 lecture 19 | No | Not found | User should provide if examinable. | HIGH |
| Theme 4 lecture 20 | No | Not found | User should provide if examinable. | HIGH |
| Theme 4 lecture 23 | No | Not found | User should provide if examinable. | HIGH |
| Theme 4 lecture 21 | Yes | `./CON178-A2-S1-Hub/sources_raw/04_theme_4_core_principles/Theme 4 lecture 21.pdf` | Already converted; later cleaning/verification needed. | MEDIUM |
| Theme 4 lecture 22 | Yes | `./CON178-A2-S1-Hub/sources_raw/04_theme_4_core_principles/Theme 4 lecture 22.pdf` | Already converted; later cleaning/verification needed. | MEDIUM |
| Theme 4 info | Yes | `./CON178-A2-S1-Hub/sources_raw/04_theme_4_core_principles/THEME 4 INFO.txt` | Already converted; later cleaning/verification needed. | MEDIUM |

## 4. Critical Before Hub Build

- Do not build the HTML hub while any failed Markdown source is treated as complete.
- Recover or OCR Theme 1 sources: `An Introduction to Law Textbook Scan (1).pdf`, `Section 2.2 Constitutional Law in Context.pdf`, and `Understanding South Africa.pdf`.
- Recover or OCR Theme 3 source: `De Vos  Freedman pg 15-31.pdf`.
- Recover or OCR Theme 4 prescribed readings: `Currie  De Waal pg 10-21.pdf` and `De Vos Freedman pages 453-455.pdf`.
- Recover or OCR Theme 2 sources: `Currie and De Waal pages 46-51.pdf` and `Reservation-of-Separate-Amenities-Act-49-of-1953.pdf`.
- Repair the EFF full judgment extraction into usable Markdown before relying on it as the full judgment source.
- Ask the user for missing lecture files, especially Theme 1 lecture 3, Theme 3 lectures 10-13, Theme 2 lecture 9, and Theme 4 lectures 14-20 and 23.

## 5. Safe Next Step

Recommended next steps:

- C. perform OCR/manual reconstruction for image scans.
- B. ask user for missing PDFs/slides.
- A. replace failed Markdown with recovered text only for the EFF full judgment after formatting recovery.

Do not continue to clean only the already-good Markdown if the goal is a complete A2 hub. Cleaning good Markdown can happen in parallel later, but Theme 1 and Theme 3 recovery gaps must remain visible and unresolved sources must not be silently skipped.

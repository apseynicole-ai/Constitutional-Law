# Theme Source Markdown Conversion Report

## 1. Summary

This batch converted available CON178 A2 S1 source files into theme-organised Markdown without cleaning, summarising, merging, deleting, moving or overwriting raw sources.

Files attempted / created per theme:

| Theme | Markdown outputs created | Usable non-empty outputs | Empty extraction outputs |
| --- | ---: | ---: | ---: |
| Admin / scope | 4 | 4 | 0 |
| Theme 1 | 7 | 4 | 3 |
| Theme 2 | 6 | 4 | 2 |
| Theme 3 | 10 | 9 | 1 |
| Theme 4 | 7 | 4 | 3 |
| Tutorials / A1 feedback | 2 | 2 | 0 |

Existing Markdown not newly converted in this batch remains in:

- `CON178-A2-S1-Hub/sources_md/05_cases/`
- `CON178-A2-S1-Hub/sources_md/08_student_essay_notes_model_answers/`

## 2. Conversion Table

| Raw file | Source location | Theme | Markdown output | Conversion status | Notes |
| --- | --- | --- | --- | --- | --- |
| `Intro To Con LawCourse outline 178.pdf` | repo root | Admin / scope | `sources_md/00_admin_scope/intro_to_con_law_course_outline_178.md` | Converted successfully | Root file should later be copied into `sources_raw/00_admin_scope/`. |
| `Con  law A2.txt` | repo root | Admin / scope | `sources_md/00_admin_scope/con_law_a2_root.md` | Converted successfully | Root file should later be copied into `sources_raw/00_admin_scope/`. |
| `Con  law A2 (1).txt` | repo root | Admin / scope | `sources_md/00_admin_scope/con_law_a2_1_root.md` | Converted successfully | Duplicate-looking scope file preserved as separate source. |
| `Con law a2 scope.txt` | `sources_raw/00_admin_scope/` | Admin / scope | `sources_md/00_admin_scope/con_law_a2_scope.md` | Converted successfully | Confirms A2 scope material in raw hub workflow. |
| `An Introduction to Law Textbook Scan (1).pdf` | repo root | Theme 1 | `sources_md/01_theme_1_intro/an_introduction_to_law_textbook_scan_1.md` | Empty extraction | MarkItDown created a zero-byte Markdown file; likely needs OCR/alternate extraction. |
| `Introduction to the law of South Africa (Van der Merwe, C. G. Du Plessis, J. E.) (z-library.sk, 1lib.sk, z-lib.sk).pdf` | repo root | Theme 1 | `sources_md/01_theme_1_intro/introduction_to_the_law_of_south_africa_van_der_merwe_du_plessis.md` | Converted successfully | Long non-empty extraction. Exact prescribed-source match still needs confirmation. |
| `Section 2.2 Constitutional Law in Context.pdf` | repo root | Theme 1 | `sources_md/01_theme_1_intro/section_2_2_constitutional_law_in_context.md` | Empty extraction | Important De Vos/Freedman constitutionalism source; needs OCR/alternate extraction. |
| `Understanding South Africa.pdf` | repo root | Theme 1 | `sources_md/01_theme_1_intro/understanding_south_africa.md` | Empty extraction | Important Theme 1 reading; needs OCR/alternate extraction. |
| `Visual Redress and the Law - Slade.pdf` | repo root | Theme 1 | `sources_md/01_theme_1_intro/visual_redress_and_the_law_slade.md` | Converted successfully | Non-empty extraction. |
| `City of Tshwane Metropolitan Municipality v Afriforum 2016 (1).pdf` | repo root | Theme 1 | `sources_md/01_theme_1_intro/city_of_tshwane_metropolitan_municipality_v_afriforum_2016.md` | Converted successfully | Case source converted. |
| `EEF v Speaker 2016.pdf` | repo root | Theme 1 | `sources_md/01_theme_1_intro/eef_v_speaker_2016.md` | Converted successfully | Duplicate-looking EFF source preserved separately from full judgment conversion. |
| `The South Africa Act 1909.pdf` | repo root | Theme 2 | `sources_md/02_theme_2_history/the_south_africa_act_1909.md` | Converted successfully | Foundational history source. |
| `Currie and De Waal pages 46-51.pdf` | repo root | Theme 2 | `sources_md/02_theme_2_history/currie_and_de_waal_pages_46_51.md` | Empty extraction | Needs OCR/alternate extraction. |
| `Woolman and Swanepoel chapter-2.pdf` | repo root | Theme 2 | `sources_md/02_theme_2_history/woolman_and_swanepoel_chapter_2.md` | Converted successfully | Duplicate-looking source preserved separately. |
| `Woolman and Swanepoel chapter.pdf` | repo root | Theme 2 | `sources_md/02_theme_2_history/woolman_and_swanepoel_chapter.md` | Converted successfully | Duplicate-looking source preserved separately. |
| `Rivonia Trial 50 years on - Peoples Law Journal.pdf` | repo root | Theme 2 | `sources_md/02_theme_2_history/rivonia_trial_50_years_on_peoples_law_journal.md` | Converted successfully | Non-empty extraction. |
| `Reservation-of-Separate-Amenities-Act-49-of-1953.pdf` | repo root | Theme 2 | `sources_md/02_theme_2_history/reservation_of_separate_amenities_act_49_of_1953.md` | Empty extraction | Needs OCR/alternate extraction. |
| `Theme_3_Case_and_Legislation_Doc_Intro_to_Con_Law (1).docx` | repo root | Theme 3 | `sources_md/03_theme_3_negotiated_revolution/theme_3_case_and_legislation_doc_intro_to_con_law_1.md` | Converted successfully | Root DOCX should later be copied into `sources_raw/03_theme_3_negotiated_revolution/`. |
| `Constitutional Principles - Interim Constitution Act 200 of 1993.pdf` | repo root | Theme 3 | `sources_md/03_theme_3_negotiated_revolution/constitutional_principles_interim_constitution_act_200_of_1993.md` | Converted successfully | Constitutional Principles source converted. |
| `Constitutional Guidelines for a Democratic South Africa.pdf` | repo root | Theme 3 | `sources_md/03_theme_3_negotiated_revolution/constitutional_guidelines_for_a_democratic_south_africa.md` | Converted successfully | Guidelines source converted. |
| `Full Interim Constitution.pdf` | repo root | Theme 3 | `sources_md/03_theme_3_negotiated_revolution/full_interim_constitution.md` | Converted successfully | Interim Constitution converted. |
| `First Certification judgment.pdf` | repo root | Theme 3 | `sources_md/03_theme_3_negotiated_revolution/first_certification_judgment.md` | Converted successfully | Case source converted. |
| `Mureinik A bridge to where.pdf` | repo root | Theme 3 | `sources_md/03_theme_3_negotiated_revolution/mureinik_a_bridge_to_where.md` | Converted successfully | Transformative constitutionalism bridge reading converted. |
| `Transformative constitutionalism CJ Pius Langa.pdf` | `sources_raw/03_theme_3_negotiated_revolution/` | Theme 3 | `sources_md/03_theme_3_negotiated_revolution/transformative_constitutionalism_cj_pius_langa.md` | Converted successfully | Langa source converted. |
| `ZA_HarareDeclaration-21Aug_1989.pdf` | repo root | Theme 3 | `sources_md/03_theme_3_negotiated_revolution/za_harare_declaration_21_aug_1989.md` | Converted successfully | Root file should later be copied into `sources_raw/03_theme_3_negotiated_revolution/`. |
| `De Vos  Freedman pg 15-31.pdf` | repo root | Theme 3 | `sources_md/03_theme_3_negotiated_revolution/de_vos_freedman_pg_15_31.md` | Empty extraction | Important Theme 3 reading; needs OCR/alternate extraction. |
| `South African Treaty Examples.pdf` | repo root | Theme 3 | `sources_md/03_theme_3_negotiated_revolution/south_african_treaty_examples.md` | Converted successfully | Converted as available CON178-related root source; theme relevance needs confirmation. |
| `Constitution (1).pdf` | repo root | Theme 4 | `sources_md/04_theme_4_core_principles/constitution_1996.md` | Converted successfully | Constitution source converted. |
| `THEME 4 INFO.txt` | `sources_raw/04_theme_4_core_principles/` | Theme 4 | `sources_md/04_theme_4_core_principles/theme_4_info.md` | Converted successfully | Theme 4 notes converted. |
| `Theme 4 lecture 21.pdf` | `sources_raw/04_theme_4_core_principles/` | Theme 4 | `sources_md/04_theme_4_core_principles/theme_4_lecture_21.md` | Converted successfully | Separation-of-powers lecture converted. |
| `Theme 4 lecture 22.pdf` | `sources_raw/04_theme_4_core_principles/` | Theme 4 | `sources_md/04_theme_4_core_principles/theme_4_lecture_22.md` | Converted successfully | Separation-of-powers lecture converted. |
| `Currie  De Waal pg 10-21.pdf` | repo root | Theme 4 | `sources_md/04_theme_4_core_principles/currie_de_waal_pg_10_21.md` | Empty extraction | Needs OCR/alternate extraction. |
| `De Vos Freedman pages 453-455.pdf` | repo root | Theme 4 | `sources_md/04_theme_4_core_principles/de_vos_freedman_pages_453_455.md` | Empty extraction | Needs OCR/alternate extraction. |
| `ECONOMIC_FREEDOM_FIGHTERS_v_SPEAKER,_NATIONAL_ASSEMBLY_AND_OTHERS_2016_(3)_SA_580_(CC).pdf` | repo root | Theme 4 | `sources_md/04_theme_4_core_principles/economic_freedom_fighters_v_speaker_national_assembly_2016.md` | Empty extraction | Full judgment source needs OCR/alternate extraction. |
| `CON LAW TUTORIALS.txt` | `sources_raw/06_tutorials_a1_feedback/` | Tutorials / A1 feedback | `sources_md/06_tutorials_a1_feedback/con_law_tutorials.md` | Converted successfully | Tutorial source converted. |
| `Con law a1s1 feedback transcripts.txt` | `sources_raw/06_tutorials_a1_feedback/` | Tutorials / A1 feedback | `sources_md/06_tutorials_a1_feedback/con_law_a1s1_feedback_transcripts.md` | Converted successfully | Feedback transcript converted. |

## 3. Missing or Unconverted Theme 1 Items

- Theme 1 lecture slides/notes are not found in the current repo/source listing.
- Theme 1 lecture 3 is not found.
- `An Introduction to Law Textbook Scan (1).pdf` produced empty Markdown and needs OCR/alternate extraction.
- `Section 2.2 Constitutional Law in Context.pdf` produced empty Markdown and needs OCR/alternate extraction.
- `Understanding South Africa.pdf` produced empty Markdown and needs OCR/alternate extraction.
- Exact Kleyn prescribed pages are not found by filename.
- Exact Humbly, Kotze and Du Plessis prescribed sections are not confirmed by filename.
- Chapter 1 of The New Constitutional and Administrative Law is not clearly found by filename.
- Dedicated Preamble/Ubuntu lecture notes are not found by filename.

## 4. Missing or Unconverted Theme 3 Items

- Theme 3 lecture slides/notes for lectures 10-13 are not found by filename.
- Theme 2 lecture 9 bridge material is not found by filename.
- `De Vos  Freedman pg 15-31.pdf` produced empty Markdown and needs OCR/alternate extraction.
- Sarkin article is not found by filename.
- Klug article is not found by filename.
- We Made the Constitution notes/transcripts are not found by filename.
- Dedicated CODESA/MPNF lecture slides are not found by filename, although the Theme 3 DOCX may contain some coverage.

## 5. Overall Remaining Gaps Before Hub-Building

- Do not build the hub yet: Theme 1 and Theme 3 still need either missing-source uploads or confirmed OCR/alternate extraction for empty Markdown outputs.
- Resolve empty Markdown extraction files before cleaning/merging, especially the De Vos/Freedman and Currie/De Waal prescribed readings.
- Provide or locate lecture slides for Theme 1, Theme 2, Theme 3 and missing Theme 4 lectures.
- Provide or locate Theme 4 lectures 14-20 and 23 if they are examinable.
- Confirm whether guest separation-of-powers material is fully captured in Theme 4 lecture 21/22 or exists as a separate file.
- Provide or locate Sarkin, Klug, Kleyn, exact study guide, and any remaining prescribed pages not already in the repo.
- Root-level source files converted in this batch should later be copied into the appropriate `sources_raw/` folders before final source cleaning.

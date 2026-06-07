# CON178 A2 S1 Theme Markdown Coverage Audit

## 1. Purpose

This audit checks whether Theme 1, Theme 2, Theme 3 and Theme 4 source material has been converted to Markdown before any cleaning, merging or HTML hub-building happens.

The purpose is to prevent examinable information from being lost. The A2 scope is comprehensive, so overlapping sources, duplicate-looking sources, root-level files, raw hub files, student notes, tutorials and case documents must all be preserved until a later cleaning and merging stage decides how to organise them.

## 2. Current Markdown Coverage

| Theme | Required major content | Raw sources found | Markdown files found | Coverage status | Missing or unconverted items | Priority |
| --- | --- | --- | --- | --- | --- | --- |
| Admin / scope | Course outline, A2 scope, assessment scope, study guide | `Intro To Con LawCourse outline 178.pdf`; root `Con  law A2.txt`; root `Con  law A2 (1).txt`; `sources_raw/00_admin_scope/Con law a2 scope.txt` | 4 admin Markdown files | COMPLETE ENOUGH FOR NEXT STEP | Semester 1 study guide not found; exact A2 logistics/source announcements still need confirmation | CRITICAL |
| Theme 1: Introduction to Constitutional Law | Lecture slides/notes, what is law, what is a constitution, constitutionalism, public/private law, Preamble, ubuntu, EFF, City of Tshwane, Understanding South Africa, Slade, prescribed readings | Root files found for City of Tshwane, EFF, Understanding South Africa, Slade, Section 2.2, introduction-to-law textbook scans | 7 Theme 1 Markdown outputs, but 3 are empty extractions | PARTIAL | Theme 1 lecture slides/notes not found; lecture 3 not found; some scanned/textbook PDFs converted to empty Markdown and need OCR or alternative extraction | CRITICAL |
| Theme 2: Constitutional History | Lectures 5-9, South Africa Act 1909, Union Constitution, parliamentary supremacy, apartheid, Freedom Charter, Sharpeville, Rivonia, 1961/1983 Constitutions, Currie/De Waal, Woolman/Swanepoel | Root files found for South Africa Act 1909, Currie/De Waal pages 46-51, Woolman/Swanepoel, Rivonia, Reservation of Separate Amenities Act | 6 Theme 2 Markdown outputs, but 2 are empty extractions; student Theme 2 meganotes also exist | PARTIAL | Theme 2 lectures 5-9 not found; Harris I, Harris II, Collins, Freedom Charter, Sharpeville, 1961 Constitution and 1983 Constitution not found by filename | HIGH |
| Theme 3: Negotiated Constitutional Revolution | Lectures 10-13, negotiated revolution, CODESA, MPNF, two-stage transition, Interim Constitution, Constitutional Principles, First Certification Judgment, Mureinik, Langa, Harare Declaration, De Vos/Freedman, Sarkin, Klug | Root/raw files found for Theme 3 DOCX, Constitutional Principles, Constitutional Guidelines, Full Interim Constitution, First Certification, Mureinik, Langa, Harare Declaration, De Vos/Freedman pg 15-31, South African Treaty Examples | 10 Theme 3 Markdown outputs, but 1 is empty extraction | PARTIAL | Theme 3 lecture slides 10-13 not found by filename; Sarkin not found; Klug not found; We Made the Constitution notes/transcripts not found; De Vos/Freedman pg 15-31 output is empty and needs OCR/alternate extraction | CRITICAL |
| Theme 4: Core Constitutional Principles | Lectures 14-23, guest separation of powers, constitutional supremacy, value-based constitutionalism, rights application, democracy, rule of law, separation of powers, EFF, Makwanyane, prescribed De Vos/Currie | Raw files found for Theme 4 info, lecture 21, lecture 22, Constitution, Currie/De Waal pg 10-21, De Vos/Freedman pages 453-455, EFF full judgment, student Theme 4 notes, Makwanyane case Markdown | 7 Theme 4 Markdown outputs, 4 student-note Markdown files, and Makwanyane Markdown; 3 Theme 4 raw-source conversions are empty | PARTIAL | Theme 4 lectures 14-20 and 23 not found in repo; guest separation-of-powers material not separately found; EFF full judgment, Currie and De Vos/Freedman extracted empty and need OCR/alternate extraction | CRITICAL |
| Cases | EFF, City of Tshwane, First Certification, Makwanyane, other cases in lectures/tutorials | Raw/source files found for EFF, City of Tshwane, First Certification; Makwanyane derived Markdown exists; student case bank exists | Multiple case-related Markdown files across themes and `05_cases` | PARTIAL | Other lecture/tutorial cases need confirmation; some case PDFs may need OCR if empty | HIGH |
| Tutorials / A1 feedback | Tutorials, A1 feedback, repeated concepts, answer frameworks, common mistakes | `CON LAW TUTORIALS.txt`; `Con law a1s1 feedback transcripts.txt`; student notes | 2 tutorial/A1 feedback Markdown files plus student notes | COMPLETE ENOUGH FOR NEXT STEP | A1 paper/questions/memo not found unless embedded in current tutorial or feedback files | HIGH |

## 3. Theme 1 Required Coverage

Checked items:

- Theme 1 lecture slides/notes, especially lecture 3: not found by filename in current repo/source listing.
- What is law?: likely covered by `Introduction to the law of South Africa...` and/or `An Introduction to Law Textbook Scan (1).pdf`, but the latter converted to empty Markdown.
- What is a constitution?: likely covered by introductory textbook/course material, but lecture-specific material is not found.
- Constitutionalism: raw/Markdown coverage exists via `Section 2.2 Constitutional Law in Context.pdf`, but that output is empty and needs OCR/alternate extraction.
- Public law/private law: likely covered by introductory law source, but needs confirmation during cleaning.
- Preamble: no dedicated Preamble file found; may be in Constitution or lecture materials.
- Ubuntu: likely appears in case/material sources, but no dedicated Theme 1 lecture notes found.
- City of Tshwane Metropolitan Municipality v Afriforum: raw PDF found and converted to `city_of_tshwane_metropolitan_municipality_v_afriforum_2016.md`.
- Economic Freedom Fighters v Speaker: `EEF v Speaker 2016.pdf` found and converted to `eef_v_speaker_2016.md`.
- Understanding South Africa: raw PDF found but converted to empty Markdown; needs OCR/alternate extraction.
- Visual Redress and the Law - Slade: raw PDF found and converted to `visual_redress_and_the_law_slade.md`.
- Chapter 1, The New Constitutional and Administrative Law: no exact filename found; possible overlap with Currie/De Waal root PDFs needs confirmation.
- Kleyn prescribed pages if present: no clearly named Kleyn source found.
- Humbly, Kotze and Du Plessis prescribed sections if present: no exact author/title match found; `Introduction to the law of South Africa...` exists but needs confirmation.
- De Vos and Freedman section 2.2 if present: `Section 2.2 Constitutional Law in Context.pdf` found but Markdown extraction is empty.

Theme 1 status: PARTIAL. There is now some Markdown coverage for EFF, City of Tshwane, Slade and an introductory law source, but important lecture/prescribed materials are missing or extracted empty.

## 4. Theme 2 Required Coverage

Checked items:

- Theme 2 lecture slides/notes, lectures 5-9: not found by filename.
- South Africa Act 1909: found and converted.
- Union Constitution: likely overlaps with South Africa Act 1909 but needs confirmation.
- Parliamentary supremacy: likely covered in history readings but not separately identifiable by filename.
- Harris I: not found by filename.
- Harris II: not found by filename.
- Collins: not found by filename.
- Apartheid legislation: `Reservation-of-Separate-Amenities-Act-49-of-1953.pdf` found but Markdown extraction is empty.
- Petty apartheid: no dedicated source found; may appear in readings.
- Grand apartheid: no dedicated source found; may appear in readings.
- Freedom Charter: not found by filename.
- Sharpeville: not found by filename.
- Rivonia Trial: `Rivonia Trial 50 years on - Peoples Law Journal.pdf` found and converted.
- 1961 Constitution: not found by filename.
- 1983 Constitution: not found by filename.
- Currie and De Waal pages 46-51: raw PDF found but Markdown extraction is empty.
- Woolman and Swanepoel readings: both root PDFs found and converted.
- Reservation of Separate Amenities Act: found but Markdown extraction is empty.
- Rivonia People's Law Journal: found and converted.

Theme 2 status: PARTIAL. Core readings exist, but lecture notes and several named historical/case sources are still missing or not extracted.

## 5. Theme 3 Required Coverage

Checked items:

- Theme 3 lecture slides/notes, lectures 10-13: no exact lecture-slide PDF/PPTX filenames found.
- Theme 2 lecture 9 if it bridges into Theme 3: not found by filename.
- Negotiated constitutional revolution: likely covered by Theme 3 DOCX and constitutional materials.
- CODESA: likely covered in Theme 3 DOCX or notes; needs confirmation during cleaning.
- MPNF: likely covered in Theme 3 DOCX or notes; needs confirmation during cleaning.
- Two-stage transition: likely covered in Theme 3 DOCX or notes; needs confirmation during cleaning.
- Interim Constitution: `Full Interim Constitution.pdf` found and converted.
- Chapter 5 sections 68-74 of the Interim Constitution: source likely in Full Interim Constitution, now converted.
- Section 71 of the Interim Constitution: source likely in Full Interim Constitution, now converted.
- Schedule 4 Constitutional Principles: `Constitutional Principles - Interim Constitution Act 200 of 1993.pdf` found and converted.
- 34 Constitutional Principles: found via Constitutional Principles source.
- Constitutional Guidelines for a Democratic South Africa: found and converted.
- Harare Declaration: `ZA_HarareDeclaration-21Aug_1989.pdf` found and converted.
- First Certification Judgment paragraphs 1-47: found and converted.
- Mureinik, A Bridge to Where?: found and converted.
- Langa, Transformative Constitutionalism: found in `sources_raw/03_theme_3_negotiated_revolution/` and converted.
- De Vos and Freedman pages 15-39 / paras 1.3-1.4 if present: `De Vos  Freedman pg 15-31.pdf` found, but Markdown extraction is empty.
- De Vos and Freedman pages 26-31 / para 1.4 if present: likely in the same De Vos/Freedman file, but empty extraction prevents use.
- Sarkin article if present: not found by filename.
- Klug article if present: not found by filename.
- We Made the Constitution notes/transcripts if present: not found by filename.

Theme 3 status: PARTIAL. Many major Theme 3 raw sources have Markdown conversions now, but lecture slides/notes, Sarkin, Klug and usable De Vos/Freedman extraction remain gaps.

## 6. Theme 4 Required Coverage

Checked items:

- Theme 4 lecture 14: not found by filename.
- Theme 4 lecture 15: not found in the repo/source listing.
- Theme 4 lecture 16, if it exists: not found in the repo/source listing.
- Theme 4 lecture 17: not found by filename.
- Theme 4 lecture 18: not found by filename.
- Theme 4 lecture 19: not found by filename.
- Theme 4 lecture 20: not found by filename.
- Theme 4 lecture 21: found in `sources_raw/04_theme_4_core_principles/` and converted.
- Theme 4 lecture 22: found in `sources_raw/04_theme_4_core_principles/` and converted.
- Theme 4 lecture 23: not found by filename.
- Guest separation of powers material: not separately found by filename; may overlap with lectures 21/22 and Theme 4 info.
- Value-based constitutionalism: covered in student Theme 4 notes and likely Theme 4 info.
- Horizontal application: covered in student Theme 4 notes; check raw-source coverage during cleaning.
- Vertical application: covered in student Theme 4 notes; check raw-source coverage during cleaning.
- Democracy: covered in student Theme 4 notes; check raw-source coverage during cleaning.
- Separation of powers: covered in Theme 4 lecture 21/22 and student notes.
- Rule of law: covered in student Theme 4 notes and likely Theme 4 info.
- EFF full judgment: root PDF found but Markdown extraction is empty.
- S v Makwanyane: derived Markdown exists in `sources_md/05_cases/`; student case bank also covers it.
- Bill of Rights sections 8, 36 and 39: Constitution source found and converted; student notes also cover these.
- De Vos and Freedman Theme 4 prescribed sections if present: `De Vos Freedman pages 453-455.pdf` found but Markdown extraction is empty.
- Currie and De Waal pages 10-21 if present: found but Markdown extraction is empty.

Theme 4 status: PARTIAL. Strong student-note and lecture 21/22 coverage exists, but earlier/later lecture files and some prescribed PDFs still need user-provided sources or OCR/alternate extraction.

## 7. Immediate Risk Warning

The hub must not be built until Theme 1 and Theme 3 have at least raw-source Markdown conversions or a clear missing-source list. The A2 scope is comprehensive and no theme may be skipped.

Current risk after this batch: Theme 1 and Theme 3 now have Markdown conversion attempts, but several Theme 1 and Theme 3 sources are missing or produced empty Markdown. Those gaps must be resolved or explicitly carried forward before any cleaning, merging or hub-building task begins.

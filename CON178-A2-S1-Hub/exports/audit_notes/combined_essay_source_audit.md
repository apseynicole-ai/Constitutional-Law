# Combined Essay Source Audit

## 1. Purpose

This audit checks whether the combined essay source is complete and safe enough to use as the source base for the CON178 A2 S1 HTML study hub. It does not summarise, rewrite, or replace the combined source. Its purpose is to confirm integrity, theme coverage, warning preservation, and build-readiness before any HTML hub-building begins.

## 2. Combined Source Integrity Check

| Check | Result | Status | Notes |
| --- | --- | --- | --- |
| Combined source exists | `CON178-A2-S1-Hub/exports/combined_sources/con178_a2_s1_combined_essay_source.md` exists | PASS | Created and pushed in commit `34c70d0`. |
| Line count | 98,051 lines | PASS | Matches the previously reported combined source size. |
| Source boundary count | 52 `# Source:` boundaries | PASS | Matches the 52 cleaned Markdown files included. |
| Warning markers preserved | `CLEANING WARNING` markers and common mistake/warning markers found | PASS WITH WARNING | Extraction warnings remain visible and must not be treated as completed source content. |
| Cleaned source count included | 52 cleaned Markdown source files | PASS | All cleaned Markdown files are represented by source boundaries. |
| `sources_md` unchanged | No changes detected in this task | PASS | Combined source uses cleaned exports only. |
| Raw sources unchanged | No changes detected in this task | PASS | No raw sources were edited, moved, renamed, or deleted. |

## 3. Theme Coverage Audit

| Theme | Coverage status | Evidence found | Remaining concerns | Hub readiness |
| --- | --- | --- | --- | --- |
| Theme 1: Introduction / constitutional context | STRONG | Search hits show constitution, constitutionalism, Preamble, state institutions, public/private law context, City of Tshwane/Afriforum, constitutional supremacy, and separation of powers. | Some textbook scans failed extraction, including `an_introduction_to_law_textbook_scan_1.md`, `section_2_2_constitutional_law_in_context.md`, and `understanding_south_africa.md`. Their content is mitigated by lecture, tutorial, case, and other Theme 1 sources, but remains unresolved for final exam-pack improvement. | READY WITH WARNINGS |
| Theme 2: Historical development / apartheid legal order | STRONG | Search hits show South Africa Act, parliamentary sovereignty, Harris, Collins, apartheid, petty/grand apartheid, Separate Representation, Reservation of Separate Amenities, Sharpeville, Rivonia, 1961 Constitution, and 1983 Constitution. | `currie_and_de_waal_pages_46_51.md` and `reservation_of_separate_amenities_act_49_of_1953.md` failed extraction. Theme 2 remains mitigated by lectures, tutorial questions, Rivonia material, Woolman/Swanepoel, and student Theme 2 notes. | READY WITH WARNINGS |
| Theme 3: Negotiated constitutional revolution | STRONG | Search hits show CODESA, MPNF, Interim Constitution, Constitutional Principles, Constitutional Assembly, First Certification, Second Certification, Mureinik, bridge, Final Constitution, and Government of National Unity. | `de_vos_freedman_pg_15_31.md` failed extraction. Theme 3 remains supported by lectures 10-13, First Certification, Interim Constitution, Constitutional Principles, Mureinik, Langa, Harare Declaration, and student/model-answer sources. | READY WITH WARNINGS |
| Theme 4: Core constitutional principles and doctrines | STRONG | Search hits show constitutional supremacy, rule of law, value-based constitutionalism, transformative constitutionalism, Bill of Rights, horizontal/vertical application, section 36 limitation, Makwanyane, EFF, Public Protector, democracy, separation of powers, and legality. | `currie_de_waal_pg_10_21.md` and `de_vos_freedman_pages_453_455.md` failed extraction. EFF needs formatting review. Theme 4 lecture 20 may contain template contamination. Curated Theme 4 essay-bank final v2 has not yet been added. | READY WITH WARNINGS |

## 4. High-Risk Source Mitigation Table

| Source | Risk type | Why it matters | Mitigation | Build impact | Priority |
| --- | --- | --- | --- | --- | --- |
| `an_introduction_to_law_textbook_scan_1.md` | OCR/manual reconstruction needed | Could contain foundational Theme 1 textbook definitions. | Theme 1 lecture 3, tutorials, City of Tshwane, EFF, Visual Redress, and other sources cover core Theme 1 concepts. | DOES NOT BLOCK HUB BUT FLAG | HIGH |
| `section_2_2_constitutional_law_in_context.md` | OCR/manual reconstruction needed | De Vos/Freedman constitutionalism section may provide prescribed doctrinal depth. | Constitutionalism appears in lecture and tutorial materials; keep unresolved for later OCR. | DOES NOT BLOCK HUB BUT FLAG | HIGH |
| `understanding_south_africa.md` | OCR/manual reconstruction needed | Prescribed contextual reading may deepen historical/social context. | Theme 1 and Theme 2 context is covered through other readings, cases, lectures, and student notes. | DOES NOT BLOCK HUB BUT FLAG | HIGH |
| `currie_and_de_waal_pages_46_51.md` | OCR/manual reconstruction needed | Theme 2 constitutional history reading. | Theme 2 coverage is supported by lecture/tutorial material, Woolman/Swanepoel, Rivonia material, and student notes. | DOES NOT BLOCK HUB BUT FLAG | HIGH |
| `reservation_of_separate_amenities_act_49_of_1953.md` | OCR/manual reconstruction needed | Important apartheid statute for petty apartheid and segregation. | Theme 2 lectures, tutorials, apartheid summaries, and student notes discuss apartheid legislation and Reservation of Separate Amenities. | DOES NOT BLOCK HUB BUT FLAG | HIGH |
| `de_vos_freedman_pg_15_31.md` | OCR/manual reconstruction needed | Theme 3 prescribed context on constitutional transition. | Theme 3 lectures, Certification, Interim Constitution, Mureinik, Langa, and student notes cover transition architecture. | DOES NOT BLOCK HUB BUT FLAG | HIGH |
| `currie_de_waal_pg_10_21.md` | OCR/manual reconstruction needed | Theme 4 foundational doctrinal reading. | Theme 4 lectures 15-22, Constitution 1996, Theme 4 Info, and student Theme 4 notes cover core doctrines. | DOES NOT BLOCK HUB BUT FLAG | HIGH |
| `de_vos_freedman_pages_453_455.md` | OCR/manual reconstruction needed | Theme 4 prescribed/textbook detail. | Theme 4 limitation, Bill of Rights, Makwanyane, and value-based constitutionalism are supported by lectures and case notes. | DOES NOT BLOCK HUB BUT FLAG | HIGH |
| `economic_freedom_fighters_v_speaker_national_assembly_2016.md` | Single-line blob / manual formatting review | EFF is a key case for Public Protector, accountability, separation of powers, remedial action, and constitutional obligations. | Content is present and mechanically reflowed, but should be formatted before final case-bank display. Other Theme 1/4 EFF sources also exist. | DOES NOT BLOCK HUB BUT FLAG | HIGH |
| `theme_4_lecture_20.md` | Possible template contamination / manual review | Contains democracy and Bill of Rights application material but may also include unrelated slide-template content. | Preserve content, but separate relevant Theme 4 material during essay-bank/hub curation. | DOES NOT BLOCK HUB BUT FLAG | MEDIUM |
| `case_law_introduction_to_constitutional_law_178.md` | Heavy structural cleaning / manual review | Contains case-law notes and model-answer style material. | Preserved with warning; review structure before integration into case/event boxes. | NEEDS MANUAL REVIEW BUT NOT BLOCKING | MEDIUM |
| `s_v_bhulwana.md` | Base64 placeholders removed / duplicate-looking material | Useful case-specific source for reverse onus, presumption of innocence, limitation, and constitutional criminal procedure. | Legal text preserved with warning; review before using in polished case bank. | NEEDS MANUAL REVIEW BUT NOT BLOCKING | MEDIUM |
| `theme_4_final_boss.md` | Backlink/footnote artefacts and structural review | High-value Theme 4 essay/model-answer source. | Preserve as curated-style source material; review artefacts before final essay-bank integration. | NEEDS MANUAL REVIEW BUT NOT BLOCKING | HIGH |

## 5. Essay Bank / Hub Build Readiness

The combined source is ready to support Theme 3 and Theme 4 essay-bank auditing and curation, but it should not be used alone to generate the final HTML hub.

* Theme 3 essay banks: READY WITH WARNINGS. Theme 3 coverage is strong, but curated Theme 3 essay-bank content must be added and audited.
* Theme 4 essay banks: READY WITH WARNINGS. Theme 4 source coverage is strong, but audited Theme 4 final-v2 essay-bank content must be added as curated content.
* A2 hub HTML build: NOT READY. The combined source is adequate as a base, but curated essay-bank files are missing.
* Future DOCX/PDF export: NOT READY. Export should wait until curated essay banks and final hub structure are reviewed.

The hub may proceed only if all critical gaps are present or clearly mitigated. The source base is mitigated enough for curated essay-bank integration, but not enough for immediate final HTML build.

## 6. Curated Essay Bank Integration Requirement

The final HTML hub must use curated essay-bank files rather than generating essay banks only from raw combined sources.

The essay banks must remain mostly in essay-answer paragraph format, but they should be visually structured with headings, subheadings, colour-coded boxes, authority chips, case/event boxes, exam tips, warning boxes, memory triggers, and 5/10/15-mark versions.

Curated essay-bank files should be treated as controlling where they exist, because they represent later human/Codex audit and edit cycles. The combined source should support and cross-check them, not replace them.

## 7. Decision

### Ready for HTML hub build?

NO.

### Conditions before hub build

* `combined_essay_source_audit.md` must approve the source base, which it does only with warnings.
* `theme_3_essay_banks_final.md` must be added to `CON178-A2-S1-Hub/exports/essay_banks/`.
* `theme_4_essay_banks_final_v2.md` must be added to `CON178-A2-S1-Hub/exports/essay_banks/`.
* The curated essay-bank files must be reviewed for obvious accuracy, structure, authority, and exam-answer issues.
* High-risk OCR/manual reconstruction gaps must remain visibly flagged in the hub or be repaired before a final exam pack.

### Recommended next step

B. Add curated Theme 3 and Theme 4 essay-bank Markdown files, then audit them.

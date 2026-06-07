# Theme 1 and Theme 2 HTML Upgrade Log

## 1. Purpose

This patch upgrades A1-tested but still examinable Theme 1 and Theme 2 material in the CON178 A2 S1 HTML hub. The upgrade is aimed at MCQ, short-answer and short-paragraph foundation questions because the A2 scope covers the full Semester 1 Constitutional Law content.

## 2. Inputs Used

Inputs checked and used:

* `CON178-A2-S1-Hub/exports/combined_sources/con178_a2_s1_combined_essay_source.md`
* `CON178-A2-S1-Hub/exports/cleaned_sources/01_theme_1_intro/`
* `CON178-A2-S1-Hub/exports/cleaned_sources/02_theme_2_history/`
* `CON178-A2-S1-Hub/exports/audit_notes/`

Reliable Theme 1/2 source folders were used where available. Older OCR/manual reconstruction warnings remain for selected Theme 1 and Theme 2 scans and were not removed or treated as complete.

## 3. Theme 1 Additions

Added a full section titled `Theme 1: Introduction to Constitutional Law — Short Question and MCQ Foundation`.

Subsections added:

* What law is.
* Why law exists.
* Law and society.
* Rule of law and social contract.
* Ubuntu and law.
* Where constitutional law fits.
* What constitutional law is.
* What a constitution is.
* What a constitution does.
* Constitutionalism.
* Separation of powers introductory box.
* Types of constitutions comparison table.
* Preamble and constitutional purpose.
* City of Tshwane v Afriforum case/event bridge box.
* Theme 1 short-answer bank with 15 model answers.
* Theme 1 MCQ bank with 15 revealable answers/explanations.

## 4. Theme 2 Additions

Added a full section titled `Theme 2: Constitutional History — Short Question, MCQ and Timeline Foundation`.

Subsections added:

* Why constitutional history matters.
* Five official constitutions.
* Pre-1910 history.
* European colonial history.
* Why pre-1910 history matters.
* South Africa Act 1909 / 1910 Union Constitution.
* Parliamentary supremacy.
* Creation of ANC and land laws.
* Apartheid legislation table.
* Constitutional crisis and parliamentary supremacy.
* Resistance and constitutional vision.
* Theme 2 timeline from pre-colonial governance to the 1996 Final Constitution.
* Theme 2 short-answer bank with 20 model answers.
* Theme 2 MCQ bank with 20 revealable answers/explanations.

## 5. Risky Phrase Fixes

* `no higher law` was replaced or qualified.
* `no higher Constitution` was replaced or qualified.
* The South African parliamentary sovereignty nuance was added where `classical Westminster` appears: South African parliamentary sovereignty was not fully Diceyan because limited manner-and-form requirements existed under the South Africa Act 1909.

## 6. Theme 4 Subsidiarity Fix

Constitutional subsidiarity was added in:

* Theme 4 Essay Bank 4, as a critical study box.
* Common mistakes master list.
* Constitutional provisions and statutory references bank.

The warning explains that where legislation gives effect to a constitutional right, a litigant generally may not bypass that legislation and rely directly on the constitutional right unless the litigant challenges the constitutionality of the legislation itself. PEPUDA and the LRA are flagged as common examples.

## 7. Case/Provision Bank Expansion

Expanded case/event bank entries include:

* City of Tshwane v Afriforum.
* Harris I.
* Harris II.
* Collins.
* Freedom Charter.
* Sharpeville.
* Rivonia.
* First Certification Judgment.
* Second Certification Judgment.
* S v Makwanyane.
* EFF v Speaker.
* Carmichele.
* Daniels.
* S v Bhulwana.

Expanded provision/statutory references include:

* South Africa Act 1909.
* Constitution of the Republic of South Africa Act 200 of 1993.
* Interim Constitution sections 68, 71 and 73.
* Schedule 4 Constitutional Principles.
* 1996 Constitution Preamble.
* Sections 1, 2, 7, 8, 9, 36, 39, 74, 83, 165, 167, 172, 181 and 182.
* Reservation of Separate Amenities Act 49 of 1953.
* Separate Representation of Voters Act 1951.
* High Court of Parliament Act 35 of 1952.
* General Law Amendment Act 76 of 1962.
* Suppression of Communism Act 44 of 1950.
* Citation of Constitutional Laws Act 5 of 2005.

## 8. Self-Test Expansion

Expanded the optional self-test to include:

* 20 Theme 1 MCQs.
* 25 Theme 2 MCQs.
* 20 mixed Theme 3/4 MCQs.
* 15 short-answer prompts.

The existing localStorage MCQ scoring remains in place through the existing `scoreMcq` function.

## 9. Remaining Warnings

Older OCR/manual reconstruction warnings remain. Manual-review warnings remain for EFF, Theme 4 lecture 20, case-law notes, S v Bhulwana and Theme 4 Final Boss. These warnings were not removed or hidden.

## 10. Verification

Verification checks performed:

* Final HTML exists: YES.
* Final HTML line count after patch: 4,700.
* Theme 1 markers found: `Theme 1: Introduction to Constitutional Law`, `What law is`, `Ubuntu`, `constitutionalism`, `City of Tshwane`, `Preamble`.
* Theme 2 markers found: `Theme 2: Constitutional History`, `South Africa Act 1909`, `parliamentary supremacy`, `Harris I`, `Harris II`, `Collins`, `petty apartheid`, `grand apartheid`, `Sharpeville`, `Rivonia`.
* Subsidiarity markers found: `subsidiarity`, `PEPUDA`, `LRA`.
* Risky phrase check: `no higher law` and `no higher Constitution` no longer appear.
* `classical Westminster` still appears only with the South African/Diceyan nuance.
* Automation markers preserved: `localStorage`, `Prepare Whole Hub + Save as PDF`, `resetProgress`, `scoreMcq`, `errorLog`.

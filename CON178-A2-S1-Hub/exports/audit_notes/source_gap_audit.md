# CON178 A2 S1 Source Gap Audit

## 1. Audit Purpose

This audit checks whether the repo currently contains all source material needed for the CON178 A2 S1 study hub before any conversion, cleaning, merging, or HTML building happens.

The audit is limited to the current repo/source state. It does not convert files, move files, delete files, install tools, or build the hub. Its purpose is to identify what is already present, what is only a placeholder, what is present but not yet organised into the hub workflow, and what must still be provided before source conversion begins.

## 2. Current Repo State

* Current branch: `feat/con178-a2-s1-source-inventory`
* Working tree clean before audit file creation: yes
* Hub HTML exists: yes, `CON178-A2-S1-Hub/con178_a2_s1_study_hub.html`
* Hub HTML is empty or has content: effectively empty; file size is 1 byte, consistent with a placeholder newline only
* `sources_raw` exists: yes, `CON178-A2-S1-Hub/sources_raw/`
* `sources_md` exists: yes, `CON178-A2-S1-Hub/sources_md/`
* Actual PDF/PPTX/DOCX/ZIP/TXT source files currently present: yes, multiple PDF/TXT/DOCX source files are present at the repo root
* Actual source files currently present inside `CON178-A2-S1-Hub/sources_raw/`: no
* Actual source files currently present inside `CON178-A2-S1-Hub/sources_md/`: no
* Only `.gitkeep`/placeholder files are present inside the hub source and export workflow folders, apart from audit notes and the placeholder HTML

Current hub files found:

```text
CON178-A2-S1-Hub/.gitignore
CON178-A2-S1-Hub/README.md
CON178-A2-S1-Hub/con178_a2_s1_study_hub.html
CON178-A2-S1-Hub/exports/audit_notes/.gitkeep
CON178-A2-S1-Hub/exports/audit_notes/source_inventory_plan.md
CON178-A2-S1-Hub/exports/cleaned_sources/.gitkeep
CON178-A2-S1-Hub/exports/combined_sources/.gitkeep
CON178-A2-S1-Hub/sources_md/.gitkeep
CON178-A2-S1-Hub/sources_raw/.gitkeep
CON178-A2-S1-Hub/tools/.gitkeep
```

Actual source-like files currently found at the repo root:

```text
An Introduction to Law Textbook Scan (1).pdf
City of Tshwane Metropolitan Municipality v Afriforum 2016 (1).pdf
Con  law A2 (1).txt
Con  law A2.txt
Constitution (1).pdf
Constitutional Guidelines for a Democratic South Africa.pdf
Constitutional Principles - Interim Constitution Act 200 of 1993.pdf
Currie  De Waal pg 10-21.pdf
Currie and De Waal pages 46-51.pdf
De Vos  Freedman pg 15-31.pdf
De Vos Freedman pages 453-455.pdf
ECONOMIC_FREEDOM_FIGHTERS_v_SPEAKER,_NATIONAL_ASSEMBLY_AND_OTHERS_2016_(3)_SA_580_(CC).pdf
EEF v Speaker 2016.pdf
First Certification judgment.pdf
Full Interim Constitution.pdf
Intro To Con LawCourse outline 178.pdf
Introduction to the law of South Africa (Van der Merwe, C. G. Du Plessis, J. E.) (z-library.sk, 1lib.sk, z-lib.sk).pdf
Mureinik A bridge to where.pdf
Reservation-of-Separate-Amenities-Act-49-of-1953.pdf
Rivonia Trial 50 years on - Peoples Law Journal.pdf
Section 2.2 Constitutional Law in Context.pdf
South African Treaty Examples.pdf
The South Africa Act 1909.pdf
Theme_3_Case_and_Legislation_Doc_Intro_to_Con_Law (1).docx
Understanding South Africa.pdf
Visual Redress and the Law - Slade.pdf
Woolman and Swanepoel chapter-2.pdf
Woolman and Swanepoel chapter.pdf
ZA_HarareDeclaration-21Aug_1989.pdf
```

## 3. Required Source Map Based on Course Framework and Semester 1 Study Guide

### A. Admin / Scope Sources

Required:

* Course outline 178 (1).pdf
* Introduction to Constitutional Law STUDY GUIDE SEM 1 2026.pdf
* A2 S1 assessment scope transcript or lecturer announcement
* Any additional lecturer announcements about scope
* Any assessment logistics or structure notes

### B. Theme 1: Introduction to Constitutional Law

Required:

* Theme 1 lecture slides/notes, including lectures 2-4 if available
* Kleyn et al Beginner's Guide pages 1-4; 156-159
* Humbly, Kotze and Du Plessis, Introduction to Law and Legal Skills in South Africa sections 1.1-1.4
* De Vos and Freedman South African Constitutional Law in Context 2nd ed section 2.2 Constitutionalism
* Economic Freedom Fighters v Speaker of the National Assembly 2016 3 SA 580 (CC), paras 1-14
* City of Tshwane Metropolitan Municipality v Afriforum 2016, paras 1-19
* Know your Constitution Handbook 2026 pages 1-13
* Du Plessis & Plaut Understanding South Africa pages 5-25
* Slade, Law and Visual Redress pages 195-217
* Any class notes or lecturer comments on the Preamble, Ubuntu, constitutionalism, public/private law, and state institutions

### C. Theme 2: Constitutional History

Required:

* Theme 2 lecture slides/notes, lectures 5-10
* Kleyn et al Beginner's Guide pages 51-52; 159-164
* De Vos and Freedman South African Constitutional Law in Context section 1.2
* Woolman and Swanepoel Constitutional History prescribed portions:
  * para (h) pages 17-19 of PDF
  * para (iv) pages 23-24 of PDF
  * para 2.3 pages 26-36 of PDF
* 50 Years on Remembering Rivonia, People's Law Journal pages 13-15; 16-17; 42-53
* Humbly, Kotze and Du Plessis sections 2.1-2.2
* Currie and De Waal New Constitutional and Administrative Law pages 40-57
* Any sources on South Africa Act 1909, Union Constitution, parliamentary supremacy, apartheid legislation, petty/grand apartheid, Freedom Charter, Sharpeville, Soweto, Rivonia, 1961 Constitution, and 1983 Constitution

### D. Theme 3: Negotiated Constitutional Revolution

Required:

* Theme 3 lecture slides/notes, lectures 11-17
* Kleyn et al Beginner's Guide pages 51-52; 156-167; 180
* De Vos and Freedman sections 1.3, 1.4 and 2.2
* Constitutional Guidelines for a Democratic South Africa, as reproduced in 1989 5 SAJHR 129-132
* First Certification Judgment, paragraphs 1-47
* Sarkin, The drafting of South Africa's Final Constitution from a Human-Rights Perspective, pages 67-87
* Klug, Towards a sociology of constitutional transformation, pages 1373-1393
* Chapter 5, sections 68-74, of the Interim Constitution of 1993
* Section 71 of the Interim Constitution of 1993
* Schedule 4 Constitutional Principles of the Interim Constitution
* Mureinik, A bridge to where?
* Constitutional Guidelines Discussion Document
* Harare Declaration 21 August 1989
* Langa, Transformative constitutionalism
* Any notes on CODESA, MPNF, two-stage transition, 34 principles, Constitutional Assembly, certification, and transformative constitutionalism

### E. Theme 4: Core Constitutional Principles / Doctrines

Required:

* Theme 4 lecture slides/notes, lectures 18-24
* Guest lecture material on separation of powers
* Constitution of the Republic of South Africa, 1996, sections 1, 2, 8, 9, 10, 36, 39, 172
* De Vos and Freedman sections 2.1, 2.2, 2.3.1-2.3.2, 2.4, 2.5, 10.3.3.3
* S v Makwanyane 1995 3 SA 391 (CC), as discussed in De Vos and Freedman table 11.1 para 11.6
* Currie and De Waal pages 40-57 and 72-89
* Any class notes on constitutional supremacy, foundational values, rights limitation, horizontal application, rule of law, democracy, and separation of powers

### F. Case Bank Sources

Required:

* EFF v Speaker
* City of Tshwane v Afriforum
* First Certification Judgment
* S v Makwanyane
* Any other cases mentioned in lectures, tutorials, A1, or feedback

### G. Assessment / Exam Training Sources

Required:

* A1S1 paper/questions
* A1 feedback/memo/marked scripts if available
* Tutorial 1 questions
* Tutorial 2 questions
* Tutorial 3 questions
* Tutorial 4 questions
* Tutorial feedback/memos if available
* Writing Guide / referencing guide
* Any lecturer comments about A2 structure, question types, or common mistakes

## 4. Audit Table

| Source / Requirement | Required for | Current repo status | Evidence from repo | Action needed | Priority |
| --- | --- | --- | --- | --- | --- |
| Hub source workflow folders | All conversion and hub-building workflow | PLACEHOLDER ONLY | `CON178-A2-S1-Hub/sources_raw/.gitkeep`, `CON178-A2-S1-Hub/sources_md/.gitkeep` | Copy available source files into `sources_raw/` before conversion begins | CRITICAL |
| Hub HTML | Final hub shell | PLACEHOLDER ONLY | `CON178-A2-S1-Hub/con178_a2_s1_study_hub.html`, 1 byte | Leave untouched until source conversion/cleaning is complete | LOW |
| Course outline 178 (1).pdf | Admin / scope | FOUND BUT UNCATEGORISED | Root file `Intro To Con LawCourse outline 178.pdf` appears to be the course outline, but exact requested filename is not present | Confirm equivalence, then copy into `sources_raw/` later | CRITICAL |
| Introduction to Constitutional Law STUDY GUIDE SEM 1 2026.pdf | Admin / scope | NOT FOUND IN REPO | No matching study guide filename in repo listing | User should provide study guide | CRITICAL |
| A2 S1 assessment scope transcript or lecturer announcement | Admin / scope and A2 boundaries | FOUND BUT UNCATEGORISED | Root files `Con  law A2.txt` and `Con  law A2 (1).txt` may be A2 scope text, but content not reviewed in this audit | Confirm these are the A2 S1 scope transcript/announcement, then copy into `sources_raw/` later | CRITICAL |
| Additional lecturer announcements about scope | Admin / scope | NOT FOUND IN REPO | No announcement/email/WhatsApp-style source identified by filename | User should provide any announcements | HIGH |
| Assessment logistics or structure notes | Admin / exam prep | NOT FOUND IN REPO | No logistics or structure note identified by filename | User should provide if available | HIGH |
| Theme 1 lecture slides/notes, lectures 2-4 | Theme 1 | NOT FOUND IN REPO | No Theme 1 slides/notes filename found | User should provide Theme 1 lecture material | CRITICAL |
| Kleyn et al Beginner's Guide pages 1-4; 156-159 | Theme 1 | NEEDS CONFIRMATION | Root file `An Introduction to Law Textbook Scan (1).pdf` may be a textbook scan, but no filename confirms Kleyn pages | Confirm source identity and page coverage | HIGH |
| Humbly, Kotze and Du Plessis sections 1.1-1.4 | Theme 1 | FOUND BUT UNCATEGORISED | Root file `Introduction to the law of South Africa (Van der Merwe, C. G. Du Plessis, J. E.) (z-library.sk, 1lib.sk, z-lib.sk).pdf` is present, but requested author combination differs | Confirm whether this satisfies the required reading | HIGH |
| De Vos and Freedman section 2.2 Constitutionalism | Theme 1 | FOUND BUT UNCATEGORISED | Root file `Section 2.2 Constitutional Law in Context.pdf` | Copy into `sources_raw/` later and confirm section scope | HIGH |
| EFF v Speaker paras 1-14 | Theme 1 / case bank | FOUND BUT UNCATEGORISED | Root files `ECONOMIC_FREEDOM_FIGHTERS_v_SPEAKER,_NATIONAL_ASSEMBLY_AND_OTHERS_2016_(3)_SA_580_(CC).pdf` and `EEF v Speaker 2016.pdf` | Confirm preferred file and prescribed paragraphs | HIGH |
| City of Tshwane v Afriforum paras 1-19 | Theme 1 / case bank | FOUND BUT UNCATEGORISED | Root file `City of Tshwane Metropolitan Municipality v Afriforum 2016 (1).pdf` | Confirm prescribed paragraphs | HIGH |
| Know your Constitution Handbook 2026 pages 1-13 | Theme 1 | NOT FOUND IN REPO | No matching handbook filename found | User should provide handbook | HIGH |
| Du Plessis & Plaut Understanding South Africa pages 5-25 | Theme 1 | FOUND BUT UNCATEGORISED | Root file `Understanding South Africa.pdf` | Confirm page coverage | HIGH |
| Slade, Law and Visual Redress pages 195-217 | Theme 1 | FOUND BUT UNCATEGORISED | Root file `Visual Redress and the Law - Slade.pdf` | Confirm page coverage | HIGH |
| Class notes on Preamble, Ubuntu, constitutionalism, public/private law, and state institutions | Theme 1 | NEEDS CONFIRMATION | No clear class-notes file by filename; possible overlap with `Con  law A2.txt` unknown | User should identify/provide class notes | HIGH |
| Theme 2 lecture slides/notes, lectures 5-10 | Theme 2 | NOT FOUND IN REPO | No Theme 2 slides/notes filename found | User should provide Theme 2 lecture material | CRITICAL |
| Kleyn et al Beginner's Guide pages 51-52; 159-164 | Theme 2 | NEEDS CONFIRMATION | Root file `An Introduction to Law Textbook Scan (1).pdf` may be relevant, but filename does not confirm | Confirm source identity and page coverage | HIGH |
| De Vos and Freedman section 1.2 | Theme 2 | FOUND BUT UNCATEGORISED | Root file `De Vos  Freedman pg 15-31.pdf` may correspond to early constitutional context; exact section not confirmed by filename | Confirm section coverage | HIGH |
| Woolman and Swanepoel prescribed portions | Theme 2 | FOUND BUT UNCATEGORISED | Root files `Woolman and Swanepoel chapter.pdf` and `Woolman and Swanepoel chapter-2.pdf` | Confirm prescribed pages/paragraphs | HIGH |
| 50 Years on Remembering Rivonia, People's Law Journal pages 13-15; 16-17; 42-53 | Theme 2 | FOUND BUT UNCATEGORISED | Root file `Rivonia Trial 50 years on - Peoples Law Journal.pdf` | Confirm page coverage | HIGH |
| Humbly, Kotze and Du Plessis sections 2.1-2.2 | Theme 2 | NEEDS CONFIRMATION | Root file `Introduction to the law of South Africa (Van der Merwe, C. G. Du Plessis, J. E.) (z-library.sk, 1lib.sk, z-lib.sk).pdf`; exact requested source not confirmed | Confirm whether source matches required reading | HIGH |
| Currie and De Waal pages 40-57 | Theme 2 | FOUND BUT UNCATEGORISED | Root files `Currie  De Waal pg 10-21.pdf` and `Currie and De Waal pages 46-51.pdf`; full pages 40-57 not confirmed | User should provide missing page range if needed | HIGH |
| South Africa Act 1909 | Theme 2 | FOUND BUT UNCATEGORISED | Root file `The South Africa Act 1909.pdf` | Copy into `sources_raw/` later | MEDIUM |
| Union Constitution | Theme 2 | NEEDS CONFIRMATION | May overlap with `The South Africa Act 1909.pdf`, but no separate Union Constitution file found | Confirm whether South Africa Act file is sufficient | MEDIUM |
| Parliamentary supremacy | Theme 2 | NEEDS CONFIRMATION | No dedicated filename; may appear in readings | Confirm during source review | HIGH |
| Apartheid legislation | Theme 2 | FOUND BUT UNCATEGORISED | Root file `Reservation-of-Separate-Amenities-Act-49-of-1953.pdf` | Add any other required apartheid legislation if prescribed | MEDIUM |
| Freedom Charter | Theme 2 | NOT FOUND IN REPO | No Freedom Charter filename found | User should provide if prescribed or used in class | MEDIUM |
| Sharpeville | Theme 2 | NOT FOUND IN REPO | No Sharpeville source filename found | User should provide class notes/source if required | MEDIUM |
| Soweto | Theme 2 | NOT FOUND IN REPO | No Soweto source filename found | User should provide class notes/source if required | MEDIUM |
| 1961 Constitution | Theme 2 | NOT FOUND IN REPO | No 1961 Constitution filename found | User should provide if required | MEDIUM |
| 1983 Constitution | Theme 2 | NOT FOUND IN REPO | No 1983 Constitution filename found | User should provide if required | MEDIUM |
| Theme 3 lecture slides/notes, lectures 11-17 | Theme 3 | FOUND BUT UNCATEGORISED | Root file `Theme_3_Case_and_Legislation_Doc_Intro_to_Con_Law (1).docx`; no lecture slides filename found | Confirm whether this is the Theme 3 class pack and whether lecture slides are still missing | CRITICAL |
| De Vos and Freedman sections 1.3, 1.4 and 2.2 | Theme 3 | FOUND BUT UNCATEGORISED | Root files `De Vos  Freedman pg 15-31.pdf`, `De Vos Freedman pages 453-455.pdf`, and `Section 2.2 Constitutional Law in Context.pdf` | Confirm exact sections covered | HIGH |
| Constitutional Guidelines for a Democratic South Africa | Theme 3 | FOUND BUT UNCATEGORISED | Root file `Constitutional Guidelines for a Democratic South Africa.pdf` | Confirm whether it is the 1989 5 SAJHR reproduction | HIGH |
| First Certification Judgment paras 1-47 | Theme 3 / case bank | FOUND BUT UNCATEGORISED | Root file `First Certification judgment.pdf` | Confirm prescribed paragraphs | HIGH |
| Sarkin, drafting Final Constitution pages 67-87 | Theme 3 | NOT FOUND IN REPO | No Sarkin filename found | User should provide source | HIGH |
| Klug, sociology of constitutional transformation pages 1373-1393 | Theme 3 | NOT FOUND IN REPO | No Klug filename found | User should provide source | HIGH |
| Interim Constitution chapter 5 sections 68-74 | Theme 3 | FOUND BUT UNCATEGORISED | Root files `Full Interim Constitution.pdf` and `Constitutional Principles - Interim Constitution Act 200 of 1993.pdf` | Confirm sections and copy into `sources_raw/` later | HIGH |
| Interim Constitution section 71 | Theme 3 | FOUND BUT UNCATEGORISED | Root file `Full Interim Constitution.pdf` | Confirm exact coverage | HIGH |
| Schedule 4 Constitutional Principles | Theme 3 | FOUND BUT UNCATEGORISED | Root file `Constitutional Principles - Interim Constitution Act 200 of 1993.pdf` | Confirm exact schedule/principle text | HIGH |
| Mureinik, A bridge to where? | Theme 3 | FOUND BUT UNCATEGORISED | Root file `Mureinik A bridge to where.pdf` | Copy into `sources_raw/` later | HIGH |
| Constitutional Guidelines Discussion Document | Theme 3 | NEEDS CONFIRMATION | Root file `Constitutional Guidelines for a Democratic South Africa.pdf`; discussion document not separately identified | Confirm whether separate document is required | MEDIUM |
| Harare Declaration 21 August 1989 | Theme 3 | FOUND BUT UNCATEGORISED | Root file `ZA_HarareDeclaration-21Aug_1989.pdf` | Copy into `sources_raw/` later | MEDIUM |
| Langa, Transformative constitutionalism | Theme 3 | NOT FOUND IN REPO | No Langa filename found | User should provide source | HIGH |
| Notes on CODESA, MPNF, two-stage transition, 34 principles, Constitutional Assembly, certification, and transformative constitutionalism | Theme 3 | NEEDS CONFIRMATION | No dedicated notes file by filename; may overlap with Theme 3 DOCX | Confirm content during review or user should provide notes | HIGH |
| Theme 4 lecture slides/notes, lectures 18-24 | Theme 4 | NOT FOUND IN REPO | No Theme 4 slides/notes filename found | User should provide Theme 4 lecture material | CRITICAL |
| Guest lecture material on separation of powers | Theme 4 | NOT FOUND IN REPO | No guest lecture or separation of powers filename found | User should provide material | CRITICAL |
| Constitution of the Republic of South Africa, 1996 sections 1, 2, 8, 9, 10, 36, 39, 172 | Theme 4 / provisions | FOUND BUT UNCATEGORISED | Root file `Constitution (1).pdf` | Confirm it is the 1996 Constitution and includes current text | HIGH |
| De Vos and Freedman sections 2.1, 2.2, 2.3.1-2.3.2, 2.4, 2.5, 10.3.3.3 | Theme 4 | NEEDS CONFIRMATION | Some De Vos/Freedman files are present, but not all requested sections are confirmed by filename | User should provide missing sections if not covered | HIGH |
| S v Makwanyane 1995 3 SA 391 (CC) | Theme 4 / case bank | NOT FOUND IN REPO | No Makwanyane filename found | User should provide prescribed extract, notes, or judgment | CRITICAL |
| Currie and De Waal pages 40-57 and 72-89 | Theme 4 | NEEDS CONFIRMATION | Root files cover `pg 10-21` and `pages 46-51`; no pages 72-89 file found | User should provide missing page range | HIGH |
| Class notes on constitutional supremacy, foundational values, rights limitation, horizontal application, rule of law, democracy, and separation of powers | Theme 4 | NOT FOUND IN REPO | No Theme 4 class notes filename found | User should provide class notes | CRITICAL |
| Other cases mentioned in lectures, tutorials, A1, or feedback | Case bank | NEEDS CONFIRMATION | Only EFF, City of Tshwane, and First Certification are clearly identifiable by filename | Source review and user input needed | HIGH |
| A1S1 paper/questions | Assessment / exam training | NOT FOUND IN REPO | No A1 paper/question filename found | User should provide | CRITICAL |
| A1 feedback/memo/marked scripts | Assessment / exam training | NOT FOUND IN REPO | No A1 feedback/memo filename found | User should provide if available | HIGH |
| Tutorial 1 questions | Assessment / exam training | NOT FOUND IN REPO | No tutorial question filename found | User should provide | HIGH |
| Tutorial 2 questions | Assessment / exam training | NOT FOUND IN REPO | No tutorial question filename found | User should provide | HIGH |
| Tutorial 3 questions | Assessment / exam training | NOT FOUND IN REPO | No tutorial question filename found | User should provide | HIGH |
| Tutorial 4 questions | Assessment / exam training | NOT FOUND IN REPO | No tutorial question filename found | User should provide | HIGH |
| Tutorial feedback/memos | Assessment / exam training | NOT FOUND IN REPO | No tutorial feedback/memo filename found | User should provide if available | HIGH |
| Writing Guide / referencing guide | Assessment / exam training | NOT FOUND IN REPO | No writing or referencing guide filename found | User should provide if relevant | MEDIUM |
| Lecturer comments about A2 structure, question types, or common mistakes | Assessment / exam training | NEEDS CONFIRMATION | Possible overlap with `Con  law A2.txt`, but not confirmed by filename | Confirm A2 transcript contents or provide notes | HIGH |

## 5. Immediate Critical Gaps

The following should be resolved before conversion begins:

* The hub source folders are placeholder-only; no actual source files are in `CON178-A2-S1-Hub/sources_raw/` yet.
* The Semester 1 study guide is not found in the repo listing.
* Theme 1 lecture slides/notes are not found in the repo listing.
* Theme 2 lecture slides/notes are not found in the repo listing.
* Theme 4 lecture slides/notes are not found in the repo listing.
* Guest lecture separation of powers material is not found in the repo listing.
* S v Makwanyane source material is not found in the repo listing.
* A1S1 paper/questions are not found in the repo listing.
* Tutorial 1-4 questions and tutorial feedback/memos are not found in the repo listing.
* Several prescribed readings need confirmation because filenames do not prove the required sections/pages are present.

## 6. Recommended Next Step

Recommended next step: C. both.

The repo already contains many actual source files at the root, but they are found but uncategorised for the hub workflow. These should be copied into `CON178-A2-S1-Hub/sources_raw/` in a later, deliberate source-staging step.

At the same time, the user should provide or confirm the critical missing sources before conversion begins, especially the Semester 1 study guide, Theme 1/2/4 lecture materials, guest lecture separation of powers material, S v Makwanyane, A1 materials, tutorial materials, and any lecturer comments about A2 scope or common mistakes.

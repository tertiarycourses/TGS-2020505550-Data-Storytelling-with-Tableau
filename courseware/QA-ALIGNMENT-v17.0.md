# Courseware QA and Alignment Report — v17.0

Course: **Data Storytelling with Tableau**  
Course code: **TGS-2020505550**  
QA date: **15 August 2026**

## Release decision

**PASS — ready for learner delivery and controlled publication.**

The v17 package preserves the accredited and legacy v16 subject coverage while aligning the slide deck, Learner Guide, Lesson Plan, ten labs, and both assessment instruments to one topic sequence.

## A. Slide deck

- PASS — 135 slides across five topics and ten progressive labs.
- PASS — legacy v16 coverage retained for story purpose, audience, narrative, chart choice, dashboards, stories, presentation, SME review, calculated fields, parameters, and actions.
- PASS — concept-led presentation: no `Step 1`, `Step 2`, `click the`, or `go to the` procedural language detected.
- PASS — 15 editable native PowerPoint charts, supported by an original image-generated cover visual.
- PASS — LMS access, trainer profiles, assessment flow, practice-exam portal, assessment covers, and course version are included.
- PASS — all 135 rendered slides visually inspected; no clipping, overflow, or unintended overlap detected.

## B. Learner Guide and Lesson Plan

- PASS — Learner Guide contains the detailed procedures that are intentionally omitted from the slide deck.
- PASS — all ten labs include goals, prerequisites, numbered actions, acceptance tests, and evidence requirements.
- PASS — the Quick Tableau Reference table is kept together on page 18 with no orphaned continuation row.
- PASS — Lesson Plan uses the actual slide map generated from the final deck and covers both delivery days, breaks, labs, formative checks, and assessment.
- PASS — current rendered pagination: Learner Guide 18 pages; Lesson Plan 7 pages.

## C. Lab package

- PASS — each lab has an individual folder containing a README, realistic synthetic Excel workbook, starter `.twb`, and packaged sample `.twbx`.
- PASS — all ten starter workbooks are readable XML and all ten packaged workbooks pass ZIP-integrity checks.
- PASS — Excel data sheets provide substantial practice volume: 576, 520, 1,200, 468, 1,800, 180, 1,600, 120, 160, and 2,600 primary records respectively, plus supporting target, factor, and master-data sheets where required.
- PASS — no confidential or personal operational data is included; the data is synthetic training data.

## D. Assessment

- PASS — Written Assessment contains five open-ended questions mapped one-to-one to K1–K5 and retains the approved 60-minute duration.
- PASS — Practical Performance contains five connected Tableau tasks covering A1–A6 and retains the approved 90-minute duration.
- PASS — candidate papers provide adequate writing/screenshot space; the final practical task has a full-page evidence box.
- PASS — question papers and answer keys pass the structural assessment verifier and strict OOXML validation.
- PASS — answer keys remain trainer-only and are excluded from the public GitHub release and learner-facing LMS links.
- PASS — direct Drive permission audit removed inherited `anyoneWithLink` access from both answer keys; anonymous requests receive an access page, while both candidate papers serve the DOCX file.

## E. Cross-artifact traceability

| Criterion | Assessment evidence | Slides | Practice evidence |
|---|---|---:|---|
| K1 | WA Question 1 | 18–39 | Labs 1–2 |
| K2 | WA Question 2 | 40–61 | Labs 3–4 |
| K3 | WA Question 3 | 62–83 | Labs 5–6 |
| K4 | WA Question 4 | 85–106 | Labs 7–8 |
| K5 | WA Question 5 | 107–128 | Labs 9–10 |
| A1 | PP Task 1 | 18–39, 126–127 | Labs 1–2 and 10 |
| A2 | PP Task 2 | 40–61, 126–127 | Labs 3–4 and 10 |
| A3 | PP Task 3 | 62–83, 126–127 | Labs 5–6 and 10 |
| A4, A6 | PP Task 4 | 85–106, 126–127 | Labs 7–8 and 10 |
| A5 | PP Task 5 | 107–128 | Labs 9–10 |

## F. Technical validation

- PASS — strict OOXML validation: PPTX, Learner Guide, Lesson Plan, WA paper/key, and PP paper/key.
- PASS — PDF structural verification: WA paper 7 pages, WA key 6 pages, PP paper 8 pages, PP key 7 pages.
- PASS — slide-map references in the Lesson Plan match the final generated deck.
- PASS — public-release boundary excludes `.env`, assessment answer keys, references, QA renders, and build tooling.
- PASS — Drive contains the current v17 artifacts and all 41 lab files; the live TMS readback verifies the four courseware URLs, two candidate-paper URLs, and Labs folder URL.

The detailed source-to-content mapping is recorded in `SOURCE-COVERAGE-v17.0.md`.

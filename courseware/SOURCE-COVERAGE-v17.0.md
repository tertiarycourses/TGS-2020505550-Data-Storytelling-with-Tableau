# Source and Coverage Register — v17.0

Course: Data Storytelling with Tableau (`TGS-2020505550`)

## Authoritative baselines

- Legacy deck: `reference/WSQ - Dr. Alfred Ang - Data Storytelling with Tableau - v16.pptx` (158 slides).
- Accredited mapping: `course_application/Competency Mapping(DataStorytelling)-revised-3.docx`.
- Accredited design and timings: `course_application/Course Proposal_Tertiary_Infotech_CA-WSQ-2020-011212-v2.docx` and `Assessment Plan_data_storytelling_CRS-Q-0041644-ICT_v1.0.docx`.
- Live TMS assessment: 5 WA questions (K1–K5), 60 minutes; 5 PP tasks (A1–A6), 90 minutes.
- Current course page: five learning outcomes, five topics, 2-day delivery.
- Current Tableau Help: stories, calculations, actions, story best practices, and accessible dashboards.

## Legacy-to-current coverage

| Legacy v16 coverage | v17 deck / LG / labs | Assessment |
|---|---|---|
| Story purpose, audience, narrative, storyboard, Tableau workflow | Topic 1; Labs 1–2 | WA Q1 (K1); PP Task 1 (A1) |
| Bar, line, pie, scatter/bubble, heatmap/treemap, stacked bar, trends and outliers | Topic 2; Labs 3–4 | WA Q2 (K2); PP Task 2 (A2) |
| Dashboards, layout, filters, highlighting, tooltips, story workspace and story types | Topic 3; Labs 5–6 | WA Q3 (K3); PP Task 3 (A3) |
| Presenting stories, start-big/drill-down/outlier/trend patterns, stakeholder questions and SME review | Topic 4; Labs 7–8 | WA Q4 (K4); PP Task 4 (A4, A6) |
| Calculated fields, parameters, filter/highlight/URL/parameter/set actions and dynamic stories | Topic 5; Labs 9–10 | WA Q5 (K5); PP Task 5 (A5) |

## Alignment controls

- `course_data.py` defines course metadata, outcomes, topics and TSC criteria.
- `data_domain1.py` through `data_domain5.py` define all ten labs and detailed procedures.
- `build_slides.py` uses concept-led visual components, editable native PowerPoint charts, lab outcomes and acceptance criteria; no click-by-click lab procedures.
- `build_learner_guide.py` renders the detailed procedures from the same lab definitions.
- `build_lesson_plan.py` reads `slide_map.json` produced by the actual deck.
- `assessment_content.py` maps K1–K5 and A1–A6 to the same topic and lab sequence.

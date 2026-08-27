# Corporate Laws & Practices Study Assistant

Single-page ICAB Professional Level study interface for Bangladesh corporate law and related regulatory practice.

## Current build

The site follows the ICAB Professional Level Corporate Laws & Practices structure reflected in the 2023 syllabus and ICAB 2024 workbook:

1. Companies Act, 1994 and Secretarial Practices — 25%
2. Laws relating to the Securities and Exchange — 25%
3. Financial Reporting Act, 2015 and FRC Auditor & Audit Firm Enrolment Rules, 2022 — 10%
4. Bank Company Act, 1991 — 15%
5. Finance Company Act, 2023 — 5%
6. Insurance Act, 2010 — 10%
7. Bangladesh Labour Act, 2006 and Labour Rules, 2015 — 10%
8. Foreign Exchange Guidelines — supporting topic under LO7

Older Financial Institutions Act, 1993 material is retained as a reference dataset because it appears in earlier syllabus formulations and remains relevant to cross-references, but it is not presented as a separate current weighted module in the main navigation.

## Learning flow

Fixed Act column → Learning Objectives → continuous syllabus topics → same-page study cards.

No artificial Part 1 / Part 2 / Part 3 navigation is used.

Each topic uses Box 1 for the legal/regulatory reference with English and Bangla study text, Box 2 for easy explanation, Box 3 for a Bangladesh practical example, and a Professional Level exam focus.

## Visual design

Soft concentration-friendly colours separate the source, explanation, example and exam areas without distracting imagery. The Act and topic columns remain fixed on desktop and collapse on smaller screens.

## Source update architecture

The repository contains an official source registry and a GitHub Actions monitor. The monitor checks the ICAB syllabus, Bangladesh Laws, BSEC securities-law repository, Bangladesh Bank legal/regulatory sources, Insurance Act, Labour Act and Foreign Exchange Guidelines weekly.

When a monitored source changes, the workflow records a fingerprint and opens a review issue. It does not rewrite legal study content automatically. Human verification is required before an amendment or regulatory change enters the study material.

Update cycle: detect → review official source → identify affected topics/sections → update data → re-check English/Bangla/examples/exam anchors → update verification date → commit.

## Primary sources

ICAB: https://www.icab.org.bd/

Bangladesh Laws: https://bdlaws.minlaw.gov.bd/

BSEC: https://sec.gov.bd/home/laws

Bangladesh Bank laws: https://www.bb.org.bd/en/index.php/about/lawsnacts

Bangladesh Bank guidelines: https://www.bb.org.bd/en/index.php/about/guidelist

## Important legal-use note

This is a study aid, not a substitute for the current statute, Gazette, rule, notification, circular or regulatory direction. The official source always controls. Numerical thresholds, deadlines and regulatory requirements that can change through later instruments should be checked against the latest official source before being memorised or relied upon professionally.

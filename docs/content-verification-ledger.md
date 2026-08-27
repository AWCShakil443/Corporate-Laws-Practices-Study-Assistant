# Content Verification Ledger

Last reviewed: 27 August 2026

This ledger is the quality-control layer for the study assistant. A topic is marked Verified only when the legal reference can be traced to an official Act, Rule, notification or regulator source. A topic marked Regulatory check must be read with the latest circulars or directions. A topic marked Needs exact-section verification must not present a generic reference as if it were an exact statutory citation.

## Verification standard

1. ICAB syllabus/workbook establishes the learning objective and topic scope.
2. The authentic Act, Rule, Gazette or regulator source establishes the legal provision.
3. The study text paraphrases the source and does not claim to reproduce the statute unless explicitly labelled as a quotation.
4. Bangla explanations are study translations, not substitutes for the authentic Bangla enactment.
5. Numerical limits, deadlines, ratios, fees and regulatory thresholds are amendment-sensitive.
6. Where the current source is not sufficiently available for exact verification, the interface should show a verification note instead of inventing a section number.

## Current module status

| Module | Status | QA note |
|---|---|---|
| Companies Act, 1994 | Verified dataset | Continue section-by-section cross-check and amendment tagging |
| Securities & Exchange | Verified regulatory framework | Rules and notifications are amendment-sensitive |
| Bank Company Act, 1991 | Verified core section mapping | Bangladesh Bank directions may change operational requirements |
| Finance Company Act, 2023 | Core module built | Cross-check numerical and regulatory requirements against current Bangladesh Bank instruments |
| Financial Reporting Act, 2015 + FRC Rules, 2022 | Partially verified | Replace generic references with exact sections/rules before final exam-ready label |
| Insurance Act, 2010 | Core syllabus coverage built | Exact section mapping and current IDRA rules require final pass |
| Bangladesh Labour Act, 2006 + Rules, 2015 | Core syllabus coverage built | Exact section/rule mapping and amendment status require final pass |
| Foreign Exchange Guidelines | Supporting LO7 module | Always read GFET with subsequent FE Circulars/Circular Letters |

## High-priority exact-reference checks

### Financial Reporting Act, 2015

* Replace broad references such as Sections 4–24 with individual section anchors where the syllabus topic requires a particular provision.
* Verify the precise definition of Public Interest Entity against the current Act and applicable FRC instruments.
* Map auditor and audit-firm enrolment requirements separately to the FRC Auditor & Audit Firm Enlistment Rules, 2022.
* Verify every offence, penalty and enforcement reference before displaying a section number.

### Insurance Act, 2010

* Map registration and licensing to exact sections.
* Map capital, deposits, solvency, investment and management requirements to exact sections or rules.
* Map accounts, audit and actuarial requirements to exact sections.
* Map policyholder/claims, reinsurance, agents and surveyors to exact sections or rules where included by the ICAB syllabus.
* Keep IDRA regulations and circulars separate from the Act itself.

### Bangladesh Labour Act, 2006 + Rules, 2015

* Keep the confirmed section 100, 102 and 108 anchors.
* Map leave, wages, deductions, accident compensation, profit participation, provident fund and disciplinary procedure to exact sections.
* Where Labour Rules, 2015 supplies the operational procedure, cite the Rule separately rather than attributing it to the Act.
* Recheck amendment status before quoting numerical limits or deadlines.

## Source hierarchy

Primary: Bangladesh Laws, official Gazette, BSEC, Bangladesh Bank, FRC, IDRA, Ministry of Labour and Employment, ICAB syllabus/manual.

Secondary sources may be used for discovery or cross-checking only. They must not override the primary source.

## Update policy

The GitHub Actions monitor may detect a changed source, but it must not automatically rewrite legal content. A human verification pass is required because a changed web page can represent an amendment, consolidation, formatting change, replacement document or unrelated update.

## Exam-ready definition

A module is exam-ready only after every topic has an exact source reference where one exists, a clear distinction between Act/Rule/notification/circular, English study text, Bangla study text, easy explanation, Bangladesh practical example, Professional Level exam focus, amendment-sensitive warning where appropriate, and an official source link.

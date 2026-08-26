# Corporate Laws & Practices Study Assistant

Single-page ICAB Professional Level study interface for Bangladesh corporate law.

## Current build

The Companies Act, 1994 module is deliberately split into three legal-verification parts:

1. Part 1: Topics 1–8
2. Part 2: Topics 9–16
3. Part 3: Topics 17–24

Part 1 currently contains the first curated study set. Parts 2 and 3 are visible in the interface but are gated until their section references and current legal status are verified. This prevents invented or stale statutory information from appearing as fact.

## Learning flow

Fixed Act column → Part selector → Learning Objectives → Topic → same-page study cards.

Each verified topic uses:

- Box 1: legal reference with English and Bangla study text
- Box 2: easy explanation
- Box 3: Bangladesh practical example
- Professional Level exam focus
- Official source link

## Why the three-part approach

The ICAB workbook identifies 24 Companies Act and Secretarial Practices topics. The official Bangladesh Laws text remains authoritative. The study assistant therefore does not silently substitute memory or old notes when a section has not been verified.

## Update architecture

The repository now includes GitHub Actions source monitoring for:

- Bangladesh Laws: Companies Act, 1994
- ICAB latest syllabus page

The monitor runs weekly and can also be triggered manually. If a source changes, it creates a review issue. It does not automatically rewrite the study material. This is intentional because an automated HTML change does not necessarily mean that the legal meaning changed.

The intended update cycle is:

1. Detect source change.
2. Review the changed Act/syllabus.
3. Identify affected sections/topics.
4. Update the relevant part file.
5. Re-verify English/Bangla content and examples.
6. Commit the reviewed update.
7. Record the new verification date.

This architecture can later be extended to BSEC, Bangladesh Bank, FRC, Insurance Development and Regulatory Authority and Labour sources as each module is built.

## Primary legal and syllabus sources

- Companies Act 1994: https://bdlaws.minlaw.gov.bd/act-788.html
- ICAB latest syllabus: https://www.icab.org.bd/page/icab-latest-syllabus
- ICAB study manuals: https://www.icab.org.bd/page/study-manuals
- BSEC securities laws: https://sec.gov.bd/home/lbook

## Important

This is a study aid, not a substitute for the current statute, Gazette, rule, notification or regulatory direction. The official source always controls. Where the current source has not yet been verified for a topic, the interface intentionally shows a verification gate instead of fabricated statutory wording.

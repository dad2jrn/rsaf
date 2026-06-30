# NEXT-STEPS.md

**Last updated:** 2026-06-30
**Branch:** main

---

## Completed Since Last Update

### New Chapters Created

| File | Description |
|---|---|
| docs/20-Plaintiff-Theory-Identification.md | Seven enforcement theories with full evidentiary analysis for each. Core framing shift: "present legal right to enforce" replaces "ownership only." |
| docs/21-Inference-Classification.md | Six inference categories (Proven Fact, Supported Documentary Inference, Legal Inference, Competing Explanation, Open Legal Question, Speculation), hierarchy diagram, five common analytical errors. |
| docs/22-Routine-Securitization-Practice.md | Research chapter on the open question of whether routine securitization practice creates an evidentiary inference of specific transfer. Four possible inferences identified but not adopted. Competing legal positions analyzed. Research required listed. |
| OPEN-LEGAL-QUESTIONS.md | Register of open legal questions. Three entries: OLQ-001 (routine securitization inference), OLQ-002 (servicer standing to sue in own name), OLQ-003 (Delaware ABSFA effect on Virginia analysis). |

### Updated Chapters

| File | Change |
|---|---|
| docs/05-Legal-Methodology.md | Added "Identify Plaintiff's Enforcement Theory" step to analysis pipeline. New § 5.13 on theory identification (preceding account-level proof analysis). Added inference classification cross-reference (§ 5.9). Added routine securitization open-question cross-reference (§ 5.18). Sections renumbered 5.13–5.24. |
| docs/08-Program-vs-Account-Level-Evidence.md | Reframed program-level evidence as "plaintiff's own transfer framework." Strengthened § 8.3 and § 8.6. Added cross-reference to Chapter 22 and OPEN-LEGAL-QUESTIONS.md in § 8.7. |
| docs/19-Research-Methodology.md | Fixed chapter header (18→19). Added § 18.11 "Researching Unresolved Legal Questions" — covering factual vs. legal uncertainty, how to identify open questions, documentation standards, primary-authority priority, competing interpretations, confidence assessments, and what not to do with open questions. |

### Prior Session (v0.3.0) — Also Completed

- Chapters 12, 13, 06, 02 updated for standing-vs-merits framing.
- Chapter 11 expanded from stub to full chapter.
- Chapter 00 expanded with chapter map and usage guide.
- Bank of America playbook (README.md + transfer-path.md) created.
- Capital One playbook (README.md + transfer-path.md) created.
- All four templates rewritten.
- .project/DECISIONS.md and .project/ROADMAP.md populated.
- CHANGELOG.md updated to v0.3.0.

---

## Open Legal Questions

Three questions are currently documented in OPEN-LEGAL-QUESTIONS.md and remain unresolved:

**OLQ-001 — Routine Securitization Inference (High Priority)**

Whether Virginia law, Delaware law, or applicable federal evidence law recognizes a rebuttable evidentiary inference that a specific credit-card receivable was transferred because the issuing bank routinely transferred eligible receivables pursuant to a publicly disclosed securitization program.

Current RSAF position: No. Structural evidence alone does not establish the specific transfer. This is a default pending research, not a concluded position.

Research needed: Virginia Rule of Evidence 2:406 case law, Fourth Circuit opinions, bankruptcy court opinions on transfer documentation sufficiency, ASC 860 implications, FDIC guidance, SEC Regulation AB scope.

**OLQ-002 — Servicer Standing to Sue in Own Name (Medium Priority)**

Whether a servicer that does not own the receivable has standing to sue in Virginia in its own name without joining the trust or owner.

Research needed: Virginia Rule 3:17 (real party in interest) case law; servicer-authority provisions in governing agreements.

**OLQ-003 — Delaware ABSFA Effect on Virginia Litigation (Low Priority)**

Whether Delaware's ABSFA true-sale classification affects the chain-of-title analysis in Virginia consumer collection litigation.

Research needed: Virginia choice-of-law case law; Restatement (Second) Conflict of Laws as applied in Virginia.

---

## Remaining Research Tasks

### For Active Case Analysis

The following items require primary source research before they can be stated as confirmed positions in any court-facing document:

1. Virginia Rule of Evidence 2:406 — scope, predicate requirements, and application in commercial contexts. This directly governs OLQ-001.

2. Virginia Rule 3:17 (real party in interest) case law in the collection context. This governs OLQ-002.

3. Fourth Circuit opinions on transfer documentation sufficiency in consumer receivable portfolios. These are the most likely source of binding or strongly persuasive authority on OLQ-001.

4. Bankruptcy court opinions addressing securitization transfer documentation — particularly in the Fourth Circuit and other circuits. Bankruptcy trustees frequently litigate transfer completeness; there may be substantial relevant precedent.

5. ASC 860 — what the derecognition accounting standard implies about the completeness and documentation of securitization transfers.

6. Virginia Rule 2:803(6) — business records exception — in the context of acquired records (records produced by one entity, authenticated by a custodian of a successor entity). The chain of custody is frequently contested in collection litigation.

### For Bank Playbooks

- Chase (JPMorgan Chase Bank, N.A.): No playbook exists. High litigation volume; should be prioritized after Bank of America and Capital One are verified.
- Citi (Citibank, N.A. / Citibank South Dakota, N.A.): No playbook exists. Active securitization programs.
- Synchrony Bank: No playbook exists.
- Discover Bank: No playbook exists.
- Wells Fargo Bank, N.A.: No playbook exists.
- American Express National Bank: No playbook exists.

---

## Recommended Implementation Order

### Immediate — Research Completion (Before Framework Expands Further)

The open legal questions (OLQ-001 through OLQ-003) should be researched before additional chapters are written that depend on their resolution. Building analytical chapters on top of an unresolved question risks propagating an assumed answer through multiple files.

Specific priority:

1. **Research Virginia Rule 2:406.** This is the key provision for OLQ-001. Find Virginia case law applying it and confirm whether its scope reaches the commercial/securitization context. Update OPEN-LEGAL-QUESTIONS.md with findings.

2. **Research Fourth Circuit securitization sufficiency opinions.** These will either provide persuasive authority supporting OLQ-001 Position B or persuasive authority supporting Position A.

3. **Update Chapter 22 and OPEN-LEGAL-QUESTIONS.md** with whatever the research finds. Do not update to adopt a position that the research has not established.

### Near-Term — Framework Additions

**Sample analysis chapter (new docs/23-*.md).** A worked example using hypothetical facts — showing the complete RSAF pipeline from claim identification through burden assessment — would make the framework substantially more usable. It should demonstrate: pipeline execution, required proof matrix, evidentiary gap analysis, inference classification applied to real document types, and burden assessment formulation.

**Chase playbook (banks/chase/).** JPMorgan Chase Bank, N.A. has one of the highest volumes of consumer collection actions. The securitization structure runs through Chase Issuance Trust with WF Bank, N.A. (formerly Wilmington Trust) as owner trustee. EDGAR research is needed to confirm the current governing agreements.

**Cross-reference audit.** A systematic pass through all chapters to verify that cross-references are current and that chapters added since the framework was last audited (Chapters 20, 21, 22, and OPEN-LEGAL-QUESTIONS.md) are referenced where appropriate in earlier chapters.

### Medium-Term — Framework Refinement

**Rules of Evidence — jurisdiction-specific depth.** Chapter 17 covers general principles. Virginia-specific and Delaware-specific sections would improve precision.

**Chapter 04 (Judicial Communication) — expansion.** Currently brief. Could be expanded to include examples of how to present the judge's summary in different procedural postures and how to handle the theory-identification step in a motion brief.

**Chapter 02 (Guiding Principles) and Chapter 03 (Writing Standards) — expansion.** Methodologically sound but brief. Both could be doubled without losing quality.

---

## Current Framework State

### Completed Chapters

| # | File | Status |
|---|---|---|
| 00 | Introduction | Complete |
| 01 | Constitution | Complete (protected) |
| 02 | Guiding Principles | Complete |
| 03 | Writing Standards | Complete |
| 04 | Judicial Communication | Brief but functional |
| 05 | Legal Methodology | Complete — pipeline + theory identification |
| 06 | Burden of Proof | Complete |
| 07 | Evidence Hierarchy | Complete |
| 08 | Program vs. Account-Level Evidence | Complete |
| 09 | Securitization Primer | Complete |
| 10 | Receivable Life Cycle | Complete |
| 11 | Document Standards | Complete |
| 12 | Citation Integrity | Complete |
| 13 | Virginia Law | Complete |
| 14 | Delaware Law | Complete |
| 15 | Federal Law | Complete |
| 16 | Documentary Chain of Title | Complete |
| 17 | Rules of Evidence | Complete |
| 18 | Authorities | Complete |
| 19 | Research Methodology | Complete |
| 20 | Plaintiff Theory Identification | Complete |
| 21 | Inference Classification | Complete |
| 22 | Routine Securitization Practice | Complete — research chapter, no concluded position |

### Files Requiring Research Before Use in Court

Any chapter that references or depends on OLQ-001 should be treated as subject to revision once the open question is resolved. This includes:

- docs/05-Legal-Methodology.md (§ 5.18 reference to OLQ-001)
- docs/08-Program-vs-Account-Level-Evidence.md (§ 8.7 reference to OLQ-001)
- docs/21-Inference-Classification.md (§ 21.10 reference to Ch 22 and OLQ-001)
- docs/22-Routine-Securitization-Practice.md (the entire chapter)
- OPEN-LEGAL-QUESTIONS.md (OLQ-001 entry)

### Bank Playbooks

| Bank | README | Transfer Path | Status |
|---|---|---|---|
| Bank of America | ✓ | ✓ | Research framework — not verified |
| Capital One | ✓ | ✓ | Research framework — not verified |
| Chase | — | — | Not started |
| Citi | — | — | Not started |
| Synchrony | — | — | Not started |
| Discover | — | — | Not started |
| Wells Fargo | — | — | Not started |
| American Express | — | — | Not started |

---

## Critical Constraint

RSAF is not a conclusion-delivery system. It is an evidence-evaluation framework. Work product that states conclusions without evidentiary foundation is not RSAF-compliant regardless of how it is labeled.

The open legal questions are open because the law has not resolved them. The correct RSAF posture is to identify the question, state the competing positions, hold the default that requires more evidence rather than less, and update the framework when authority is found. That is the methodology. Do not try to prove RSAF correct. Try to discover whether RSAF is correct.

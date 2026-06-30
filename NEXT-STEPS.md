# NEXT-STEPS.md

**Session:** Foundation expansion — 2026-06-29
**Branch:** foundation

---

## Completed This Session

### Legal Methodology Revision (docs/05-Legal-Methodology.md)

Applied eleven editorial directives: added Required Proof Matrix, Evidence Classification Matrix, Evidence Weight, Alternate Explanations, Competing Theories, Analytical Boundaries, and The Judge's Question sections. Added Methodology Summary with conceptual sequence diagram. Updated pipeline to reflect new steps. Fixed burden language, generalized bank-specific examples. Sections renumbered 5.1–5.23.

### Expanded Foundational Chapters

| File | Previous State | Current State |
|---|---|---|
| 06-Burden-of-Proof.md | 40 lines, basic rule | 190 lines — claim-by-claim analysis, procedural stages, gap formulation |
| 07-Evidence-Hierarchy.md | 67 lines, table only | 260 lines — four evidence functions, authentication, acquired records, weight table, admissibility analysis |
| 08-Program-vs-Account-Level-Evidence.md | 57 lines, basic | 220 lines — distinction explained, inference limits, error catalog |
| 09-Securitization-Primer.md | 65 lines, thin | 230 lines — participants, transfer path, true sale, removal, two ownership theories, judge's summary |
| 10-Receivable-Life-Cycle.md | 45 lines, outline | 250 lines — eleven stages, stage-specific questions and documents, retention and reacquisition analysis |
| 13-Virginia-Law.md | Stub only | Substantive chapter — court structure, pleading, evidence rules, UCC Article 9, research targets |
| 14-Delaware-Law.md | Stub only | Substantive chapter — choice of law, UCC Article 9, ABSFA, contract interpretation |
| 15-Federal-Law.md | Stub only | Substantive chapter — FDCPA, FAA, NBA preemption, Regulation AB, FDIC guidance |

### New Chapters Created

- **docs/16-Documentary-Chain-of-Title.md** — New chapter explaining the structural vs. account-specific chain distinction, link-by-link evaluation, complete vs. incomplete chains, and RSAF's chain-of-title analytical process.
- **docs/17-Rules-of-Evidence.md** — New chapter covering authentication, business records exception, acquired records, hearsay analysis, affidavit limitations, electronic records, and evidentiary checklist.

### Project Files

- **.project/TERMINOLOGY.md** — Populated with canonical definitions for all key RSAF terms.
- **CHANGELOG.md** — Updated to reflect version 0.2.0 changes.

---

## Files Changed This Session

```
docs/05-Legal-Methodology.md    (revised)
docs/06-Burden-of-Proof.md      (expanded)
docs/07-Evidence-Hierarchy.md   (expanded)
docs/08-Program-vs-Account-Level-Evidence.md  (expanded)
docs/09-Securitization-Primer.md (expanded)
docs/10-Receivable-Life-Cycle.md (expanded)
docs/13-Virginia-Law.md         (expanded from stub)
docs/14-Delaware-Law.md         (expanded from stub)
docs/15-Federal-Law.md          (expanded from stub)
docs/16-Documentary-Chain-of-Title.md  (created)
docs/17-Rules-of-Evidence.md    (created)
.project/TERMINOLOGY.md         (created)
CHANGELOG.md                    (updated)
```

---

## Recommended Next Tasks

### High Priority — Framework Completion

**1. Add a Research Methodology chapter (docs/18-Research-Methodology.md)**

The existing 12-Citation-Integrity.md covers citation discipline but does not address the methodology for finding, verifying, and applying authority. A dedicated chapter should cover the authority hierarchy applied in practice, how to distinguish binding from persuasive authority in multi-jurisdictional cases, the use of PACER, Westlaw, and public SEC filings, and how to document research for a court-facing document.

**2. Improve chapter 00-Introduction.md**

Currently brief. Should be expanded to serve as the entry point for both human readers (judges, attorneys) and AI systems. Should include a brief orientation to the structure of the framework and how to use it.

**3. Add cross-references between chapters**

Several chapters reference related content (e.g., Chapter 05 references "Chapter 07") but these references are sparse. A systematic cross-reference pass would make the framework more navigable and reduce redundancy.

**4. Build out bank-specific playbooks**

The bank playbooks (Chase, Citi, Amex, Capital One, Discover, Synchrony, Wells Fargo) exist only as stubs. Chase has one transfer-path diagram. These should be expanded after the common framework stabilizes.

Priority for first expansion: Chase (most active volume, has existing structure) and Citi (extensive securitization programs).

### Medium Priority — Framework Refinement

**5. Review chapters 02, 03, 04 for expansion**

Guiding Principles (02), Writing Standards (03), and Judicial Communication (04) are brief. They are methodologically sound but could each be doubled in depth without losing quality. Particularly, chapter 04 could add more examples of how to present the judge's summary in different procedural postures.

**6. Populate .project/ROADMAP.md**

The roadmap file is empty. A brief roadmap documenting the planned chapter order and completion status would help track progress across sessions.

**7. Populate .project/DECISIONS.md**

Document major architectural decisions already made — the program-level vs. account-level distinction, the decision to separate the life cycle from chain of title, the decision not to include specific case law in substantive chapters without verification. These decisions are not otherwise recorded.

**8. Add a Sample Analysis chapter or template**

A worked example — using hypothetical, not fabricated, facts — demonstrating how RSAF's methodology applies from start to finish would greatly improve the framework's usability. The example should show the pipeline, the required proof matrix, the evidentiary gap analysis, and the burden assessment, all in sequence.

### Lower Priority

**9. Rules of Evidence — jurisdiction-specific expansions**

Chapter 17 covers general principles. Jurisdiction-specific expansions (Virginia, Delaware, federal arbitration) would improve precision. These should be added as subsections of the existing chapter rather than separate files.

**10. Templates**

The existing templates (answer, discovery, motion to compel arbitration, debt verification) should be reviewed for consistency with the expanded framework. The answer template in particular should reflect RSAF's standing and burden principles.

---

## Questions Requiring Human Legal Review

The following items were verified by primary source research on 2026-06-30 and updated in the relevant chapters.

**1. Green v. Portfolio Recovery Associates — RESOLVED**

Full citation: Mazie Green v. Portfolio Recovery Associates, LLC, No. 0144-22-3, 80 Va.App. 119, 897 S.E.2d 275 (Va. Ct. App. 2024) (en banc). The en banc court reversed the original panel and affirmed the circuit court's judgment for PRA. Chapter 12 has been corrected. Chapter 13 research table has been updated. The case confirms chain-of-title scrutiny in Virginia but does not establish that PRA-type evidence is insufficient. Read the full en banc opinion before citing.

**2. Virginia Rules of Evidence Rule 2:803(6) — CONFIRMED**

The rule exists and governs the business records exception. The implementing statute is Va. Code § 8.01-390.3. Chapter 13 references are confirmed accurate.

**3. Delaware ABSFA — RESOLVED**

Codified at 6 Del. C. Chapter 27A, §§ 2701A et seq. Chapter 14 updated with correct citation.

**4. FDIC Safe Harbor Rule — RESOLVED**

Codified at 12 C.F.R. § 360.6. Current version finalized March 2020 (effective May 4, 2020), amended by technical correction April 2021. Chapter 15 updated.

**5. Virginia limitations periods — RESOLVED**

Va. Code § 8.01-246(2): Five years for written signed contracts. Va. Code § 8.01-246(4): Three years for other contracts. For credit-card debt, the five-year period applies where a signed agreement exists. Chapter 13 updated.

---

## Architectural Concerns

**The "16-Documentary-Chain-of-Title.md" file number may conflict with future chapters.**

The existing files skip from 15 (Federal Law) to the new 16 (Documentary Chain of Title) and 17 (Rules of Evidence). The original HANDOFF.md priority list did not specify file numbering for later chapters. If future chapters are added for Research Methodology (#12 in the HANDOFF list), they should continue with 18, 19, etc. to maintain sequential numbering.

**Chapter 12 (Citation-Integrity) overlaps with the planned Research Methodology chapter.**

Consider whether to expand Chapter 12 into a full Research Methodology chapter or create Chapter 18 as a dedicated Research Methodology chapter that builds on Chapter 12's foundation without replacing it.

---

## Suggested Future Commits

```
docs: add research methodology chapter
docs: expand introduction chapter
docs: cross-reference all chapters
docs: expand Chase bank playbook
docs: expand Citi bank playbook
docs: expand guiding principles, writing standards, judicial communication
docs: add sample analysis chapter
docs: populate project roadmap and decisions log
docs: review and update templates for consistency
```

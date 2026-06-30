# NEXT-STEPS.md

**Last updated:** 2026-06-30
**Branch:** main

---

## Repository Integrity and Methodology Update — Completed (v0.7.0)

The following work was completed in the current development cycle. The framework is now at v0.7.0.

**Version normalization:**
All documents updated to reflect v0.6.0 as the prior release baseline. README.md, PROJECT.md, docs/00-Introduction.md, NEXT-STEPS.md, and .project/ROADMAP.md updated. Bank stub READMEs updated.

**Chapter 19 section-numbering fix:**
All sections in docs/19-Research-Methodology.md were incorrectly labeled 18.X. Corrected to 19.X throughout (19.1 through 19.11.8). Cross-reference in OPEN-LEGAL-QUESTIONS.md updated from "Section 19.X" to "Section 19.11."

**MASTER-INSTRUCTIONS.md revised:**
New 12-step analysis pipeline replacing the prior 11-step version. Added: enforcement theory identification (steps 4–5); expanded evidence classification (steps 6–7); inference classification (step 8); proof-gap identification (step 10); bank-neutral operating rules; complete quality-control checklist.

**AGENTS.md revised:**
Added: present legal right to enforce definition with all possible bases; bank-neutral language requirements with required conditional forms; inference classification framework; expanded evidence classification with all categories; updated drafting rule to include theory identification; bank-neutral quality gate.

**Bank-neutral language improvements:**
PROJECT.md Golden Rule updated to remove ownership-only framing. README.md central question updated to clarify enforcement bases beyond ownership. Scope sections updated. Conditional language requirements added to AGENTS.md.

**OLQ-001 placeholder fixed:**
OPEN-LEGAL-QUESTIONS.md updated to replace "Section 19.X" placeholder with "Section 19.11."

**docs/00-Introduction.md updated:**
Version updated to v0.6.0. Scope updated for bank-neutral language. Usage guide expanded to 12 steps reflecting the revised analysis pipeline.

---

## OLQ-001 Research Pass — Completed (v0.6.0)

**Judge's Checklists added to all applicable chapters:**
Chapters 02, 05, 06, 07, 08, 09, 10, 11, 12, 13, 14, 15, 16, 17, 19, 20, 21, 22.

**Glossary.md created:**
Plain-language definitions for judges and attorneys.

**Introduction updated (v0.4.0):**
Chapter map includes Chapters 20–22. Usage guide includes theory identification and inference classification.

**OLQ-001 research:**
Va. Code § 8.01-397.1, *Kimberlin*, FDIC Safe Harbor (12 C.F.R. § 360.6), ASC 860, Regulation AB, *Green v. PRA* reviewed. OLQ-001 remains unresolved.

---

## Recommended Next Work

The following is ordered by impact on the quality and usability of RSAF. Work that is merely incomplete is not recommended here unless it materially increases quality.

### 1. Continue Research on OLQ-001 (Routine Securitization Inference) — High Priority

An initial research pass has been completed. Va. Code § 8.01-397.1 (Rule 2:406) confirmed; *Kimberlin v. PM Transport, Inc.* (264 Va. 261, 2002) identified as leading Virginia authority; FDIC Safe Harbor (12 C.F.R. § 360.6) reviewed and found to cut against the routine practice inference; ASC 860 and Regulation AB reviewed. No court opinion identified applying the routine practice doctrine to securitization transfer inference in consumer collection litigation — for or against.

OLQ-001 remains unresolved. The conservative default is unchanged. Chapter 22, OPEN-LEGAL-QUESTIONS.md, and Chapter 08 have been updated to reflect findings.

**Next research step:** Search Virginia circuit court and bankruptcy court opinions for any application of Va. Code § 8.01-397.1 to commercial or financial organizations. Search bankruptcy courts in the Fourth Circuit for proof-of-claim opinions addressing transfer documentation sufficiency for securitized consumer debt. Search Fourth Circuit civil opinions for any treatment of pool-level assignment documentation and specific-account standing. Consider PACER search for bankruptcy court opinions on securitized credit card debt ownership disputes.

### 2. Chase Bank Playbook — Medium Priority

Chase (JPMorgan Chase Bank, N.A.) has high litigation volume. A research stub exists at banks/chase/README.md; a substantive, EDGAR-verified playbook does not. The securitization structure appears to run through Chase Issuance Trust, but governing agreements, participant entities, and transfer-path details must be confirmed from EDGAR before the stub can be elevated. Build to the same standard as the Bank of America and Capital One playbooks.

### 3. Sample Analysis Chapter — Medium Priority

A worked example using hypothetical (not fabricated) facts demonstrating the complete RSAF pipeline from claim identification through burden assessment would substantially increase usability for pro se litigants and attorneys unfamiliar with RSAF. It should demonstrate:

- Theory identification (Chapter 20)
- Evidence classification (Chapter 07 and 08)
- Inference classification (Chapter 21)
- Chain-of-title analysis (Chapter 16)
- Burden assessment (Chapter 06)

This chapter should not contain any invented legal citations, invented case names, or invented statute numbers.

### 4. Cross-Reference Audit — Low-Medium Priority

A systematic pass through all chapters to verify that every significant dependency is cross-referenced. Particular attention to:

- Chapters 07 and 08 (structural/transaction evidence — now cross-referenced but check completeness)
- Chapters 09 and 10 (securitization primer and lifecycle — now cross-referenced but check completeness)
- Chapter 20 (theory identification) — does it cross-reference Chapter 05 where the theory-identification step sits in the pipeline?
- Chapter 21 (inference classification) — does it cross-reference Chapter 07 (evidence hierarchy)?

### 5. Additional Bank Playbooks — Lower Priority

After Chase, the priority order is: Citi, Synchrony, Discover, Wells Fargo, American Express. Each requires EDGAR research before a substantive playbook can be drafted. Do not draft stubs — build substantively or not at all.

---

## What Not to Prioritize

**Do not add additional substantive legal chapters** unless a specific, unresolved analytical gap is identified that cannot be addressed by updating an existing chapter. The framework's value is in depth and usability, not breadth.

**Do not expand bank playbooks beyond what has been EDGAR-verified.** Bank playbooks are research frameworks. They should not contain conclusions about specific transfers that have not been documented.

**Do not add chapters on topics that are already adequately covered by cross-referencing existing chapters.** If the same concept is adequately explained in one chapter and cross-referenced from another, a third chapter is not needed.

---

## Framework Health Summary

| Metric | Status |
|---|---|
| Current version | 0.7.0 |
| Complete chapters | 22 (00–22) |
| Judge's Checklists | Added to all analytical chapters |
| Glossary | Created |
| Open legal questions | 3 documented (OLQ-001 through OLQ-003) |
| Bank playbooks — substantive | Bank of America, Capital One |
| Bank playbooks — research stub | Chase, Citi, Synchrony, Discover, Wells Fargo, American Express |
| Templates | 4 (answer, discovery, motion to compel arbitration, debt verification) |
| Outstanding research | OLQ-001 (initial pass complete; follow-up research needed) — high priority |
| Unresolved architectural issue | None |

---

## Critical Constraint (Unchanged)

RSAF is an evidence-evaluation framework, not a conclusion-delivery system. Work product that states conclusions without evidentiary foundation is not RSAF-compliant regardless of how it is labeled.

The open legal questions are open because the law has not resolved them. The correct RSAF posture is to identify the question, state the competing positions, hold the default that requires more evidence rather than less, and update the framework when authority is found.

Do not try to prove RSAF correct. Try to discover whether RSAF is correct.

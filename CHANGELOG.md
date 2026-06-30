# Changelog

## 0.7.0 — Repository Integrity and Methodology Update (2026-06-30)

### Version Normalization

Reconciled version references across all repository documents. README.md updated from 0.1.0 to 0.6.0. PROJECT.md scope section updated from "RSAF v0.1 focuses on" to current-scope language. docs/00-Introduction.md updated from v0.4.0 to v0.6.0. NEXT-STEPS.md updated from "framework is now at v0.4.0" to v0.6.0. .project/ROADMAP.md current version updated from 0.2.0 to 0.7.0 with added version history entries for 0.3.0 through 0.7.0. Bank stub READMEs (Chase, Citi, Discover, Synchrony, Wells Fargo, American Express) updated to remove v0.1.0 version tags.

### Chapter 19 Section-Numbering Correction

All section headings in docs/19-Research-Methodology.md were incorrectly labeled "18.X." Corrected to "19.X" throughout: §§ 19.1–19.11.8. The chapter header had been updated from "18" to "19" in a prior commit but section numbers were not renumbered at that time.

### Placeholder Cross-Reference Fixed

OPEN-LEGAL-QUESTIONS.md, line 5: "Section 19.X" replaced with "Section 19.11" — the actual section number of the unresolved-legal-questions protocol in Chapter 19.

### MASTER-INSTRUCTIONS.md — Revised

Rewritten with a 12-step analysis pipeline:

1. Identify procedural posture and requested outcome.
2. Identify governing law and choice-of-law provisions.
3. Identify the plaintiff and each relevant entity.
4. Identify the plaintiff's asserted present legal right to enforce.
5. Identify possible enforcement theories supported by the record.
6. Inventory and classify all evidence by source and evidentiary function.
7. Separate account-level evidence from program-level evidence.
8. Classify each proposition as proven fact, inference, open question, alternative explanation, or speculation.
9. Determine required documents and testimony.
10. Identify proof gaps, inconsistencies, and missing links.
11. Research controlling authority before reaching conclusions.
12. Draft narrowly tailored work product reflecting the evidentiary record.

Added: enforcement theory identification section; "present legal right to enforce" definition with all possible bases; full evidence classification (account-level, program-level, testimonial/procedural); quality-control checklist; bank-neutral operating rules.

### AGENTS.md — Revised

Added: "present legal right to enforce" definition with all possible bases (ownership, assignment, servicing authority, agency, statutory rights, and others); bank-neutral language section with required conditional forms and prohibited assumptions; inference classification framework (six categories); expanded evidence classification (account-level, program-level, testimonial/procedural); updated drafting rule to include enforcement theory identification; bank-neutral quality gate item.

Updated title: "analyzing standing and ownership" → "analyzing whether a plaintiff has established its present legal right to enforce."

### Bank-Neutral Language Improvements

- **PROJECT.md** — Golden Rule updated from "proven ownership" framing to "present legal right to enforce" framing. Scope section revised to remove "version 0.1" language and add explicit bank-neutral statement.
- **README.md** — Scope updated to add bank-neutral statement. Central question section expanded to clarify enforcement bases beyond ownership.
- **docs/00-Introduction.md** — Scope section updated from "Version 0.2 focuses on" to current-scope language with explicit bank-neutral statement. Usage guide expanded from 11 to 12 steps.
- **AGENTS.md** — Non-Negotiable Rules 9 and 10 added for securitization-assumption prohibition and bank-specificity prohibition.

### Bank Playbook Repositioning

All six research-stub playbooks (Chase, Citi, Discover, Synchrony, Wells Fargo, American Express) revised to:

- Remove version numbers (stubs are not releases).
- Add explicit purpose statement: each playbook is a research framework, not an advocacy file, and does not presume any outcome.
- Add "Playbook Structure When Complete" section listing all required documentation categories.
- Update generic transfer-path diagram with a note that the diagram is a template pending verified research.
- Add per-bank research notes identifying bank-specific complexity (Citi originating-entity distinction, American Express charge-card/credit-card distinction, Synchrony retail-card complexity).

### NEXT-STEPS.md — Updated

Added v0.7.0 integrity update to completed work section. Framework Health Summary updated to show version 0.7.0.

---

## 0.6.0 — OLQ-001 Research Pass (2026-06-30)

### Research Conducted

**OLQ-001 — Routine Securitization Inference:** Initial research pass completed. Sources reviewed: Va. Code § 8.01-397.1 (Rule 2:406), *Kimberlin v. PM Transport, Inc.* (264 Va. 261, 2002), Federal Rule of Evidence 406, 12 C.F.R. § 360.6 (FDIC Safe Harbor), ASC 860, 17 C.F.R. Part 229 (Regulation AB), *Green v. Portfolio Recovery Associates* (80 Va.App. 119, 2024, en banc). OLQ-001 remains unresolved — no court has been identified applying routine practice evidence to securitization transfer inference in consumer collection litigation. Research added new support for Position A via the FDIC safe harbor regulatory requirement.

### Updated Files

- **docs/22-Routine-Securitization-Practice.md** — §22.4.1 updated with confirmed statutory text of Va. Code § 8.01-397.1 and *Kimberlin* analysis. New §22.4.4 added: FDIC regulatory framework (12 C.F.R. § 360.6) and its evidentiary implications for the routine practice argument. §22.7 Position 1 strengthened with FDIC safe harbor support. §22.8 converted from "research required" to "research status" with findings organized into authorities reviewed (§22.8.1), authorities still needed (§22.8.2), and updated RSAF position (§22.8.3).
- **OPEN-LEGAL-QUESTIONS.md** — OLQ-001 entry substantially updated: "Authorities Reviewed" expanded with confirmed research findings; "Authorities Still Needed" narrowed to what genuinely remains open; "Current RSAF Position" updated to incorporate FDIC safe harbor finding; confidence and next research step updated.
- **docs/08-Program-vs-Account-Level-Evidence.md** — §8.6 updated to note that the "plaintiff's own framework" extends to regulatory obligations: 12 C.F.R. § 360.6 required the bank to separately identify transferred assets in its databases.

### RSAF Position Unchanged

The conservative default is unchanged: program-level evidence alone does not establish that a specific receivable was transferred. The research strengthens this default by identifying the FDIC regulatory counterpoint but does not resolve OLQ-001.

---

## 0.5.0 — Usability Pass 1 (2026-06-30)

### New Resources

- **Glossary.md** — Plain-language definitions for judges, attorneys, and pro se litigants. Distinguishes commonly confused terms: servicer vs. owner, standing vs. ownership, legal title vs. beneficial ownership, assignee vs. holder, present legal right to enforce vs. historical ownership. Includes "Common Confusions" table.

### Judge's Checklists

Added Judge's Checklist sections to all applicable analytical chapters: 02, 05, 06, 07, 08, 09, 10, 11, 12, 13, 14, 15, 16, 17, 19, 20, 21, 22. Each checklist is calibrated to the specific chapter's subject matter and written for a judge reading ten minutes before a hearing.

### Visual and Structural Improvements

- **docs/06-Burden-of-Proof.md** — Added burden flow diagram (§ 6.1A) showing how the standing and failure-of-proof framings split procedurally, where each is raised, and why both must be preserved.
- **docs/22-Routine-Securitization-Practice.md** — Converted the four possible legal inferences (A–D) from prose to a structured comparison table. Added note on cumulative nature of the inferences.
- **docs/07-Evidence-Hierarchy.md** — Added cross-reference to Chapter 08 as the definitive treatment of the structural/transaction evidence distinction.
- **docs/09-Securitization-Primer.md** — Added cross-references to Chapters 08, 10, and 16.

### Updated Resources

- **docs/00-Introduction.md** — Updated to v0.4.0. Chapter map now includes Chapters 20–22 in a new "Advanced Analysis" section. Glossary.md and OPEN-LEGAL-QUESTIONS.md added to the resource table. Usage guide expanded to 11 steps, now including theory identification (step 2) and inference classification (step 6).
- **OPEN-LEGAL-QUESTIONS.md** — Each OLQ entry (OLQ-001, OLQ-002, OLQ-003) now includes a "Next Research Step" field specifying the immediate action required to advance the research.
- **NEXT-STEPS.md** — Reprioritized. Research on OLQ-001 (routine securitization inference) is the highest-priority remaining work. Recommendations now include rationale for each item and explicit guidance on what not to prioritize.

---

## 0.4.0 — Theory Identification and Open Questions (2026-06-30)

### New Chapters

- **docs/20-Plaintiff-Theory-Identification.md** — Seven enforcement theories with full evidentiary analysis structure for each. Core framing shift throughout: "present legal right to enforce" rather than "ownership only." §20.5 explains how theory identification flows into all subsequent analytical steps.
- **docs/21-Inference-Classification.md** — Six inference categories (Proven Fact, Supported Documentary Inference, Legal Inference, Competing Explanation, Open Legal Question, Speculation) with hierarchy diagram, securitization examples, common mistakes, and five common analytical errors.
- **docs/22-Routine-Securitization-Practice.md** — Research chapter on whether documented routine securitization practice creates an evidentiary inference of specific transfer. Identifies four possible inferences (not adopted). Analyzes four competing legal positions. Lists research required before RSAF can adopt a position. Includes Open Legal Question section with verbatim current RSAF position.
- **OPEN-LEGAL-QUESTIONS.md** — New register for open legal questions material to RSAF analysis. Three entries: OLQ-001 (routine securitization inference — high priority), OLQ-002 (servicer standing to sue in own name — medium priority), OLQ-003 (Delaware ABSFA effect on Virginia analysis — low priority).

### Updated Chapters

- **docs/05-Legal-Methodology.md** — Added "Identify Plaintiff's Enforcement Theory" step to analysis pipeline (between "Map the receivable transfer path" and "Identify required account-level proof"). New §5.13 explaining why theory identification must precede evidentiary sufficiency evaluation. Added inference classification cross-reference to §5.9. Added routine securitization open-question cross-reference to §5.18. Sections renumbered 5.13–5.24.
- **docs/08-Program-vs-Account-Level-Evidence.md** — Reframed program-level evidence as "plaintiff's own transfer framework." Strengthened §8.3 to identify what the framework establishes about required documentation. Revised §8.6 to make the "plaintiff's own framework" point explicit. Added cross-reference to Chapter 22 and OPEN-LEGAL-QUESTIONS.md in §8.7.
- **docs/19-Research-Methodology.md** — Fixed chapter header (was labeled 18). Added §18.11 "Researching Unresolved Legal Questions" covering: factual vs. legal uncertainty distinction; how to identify open questions; documentation standards (with cross-reference to OPEN-LEGAL-QUESTIONS.md); primary-authority research priority; documenting competing interpretations; confidence assessments (High/Medium/Low/Indeterminate); preserving unresolved questions through analysis; what RSAF must not do with open questions.
- **NEXT-STEPS.md** — Updated to reflect current framework state. Includes: completed chapters table (22 chapters), open legal questions summary, remaining research tasks, recommended implementation order, bank playbook status table, critical constraint statement.

---

## 0.3.0 — Active Case Preparation (2026-06-30)

### Citation and Framing Corrections

- **docs/12-Citation-Integrity.md** — Expanded *Green v. Portfolio Recovery Associates* analysis. Added: standing-vs-merits framing distinction; en banc majority treated ownership as a merits/sufficiency element, not a threshold standing gate; pure standing challenges may fail at summary judgment; correct framing is failure to prove ownership at trial; both framings must be preserved. Added guidance on where substantive chain-of-title analysis lives (dissent and vacated panel opinion are persuasive only). Added binding Virginia authority sources for chain-of-title requirements.
- **docs/13-Virginia-Law.md** — Added standing-vs-merits procedural lesson to § 13.4. Pure standing challenge defeated at summary judgment if factual dispute exists. Failure-of-proof challenge requires plaintiff to prove ownership with competent evidence at trial. Both framings should be preserved; neither should be waived.

### Expanded Framework Chapters

- **docs/00-Introduction.md** — Expanded to include § 0.8 chapter map (all 19 chapters organized by function), § 0.9 bank playbook status index, and § 0.10 nine-step usage guide for new matters. Version updated to 0.2.0.
- **docs/02-Guiding-Principles.md** — Added § 2.8 (Preserve the Standing Argument and the Merits Argument) and § 2.9 (The Servicer Is Not the Owner).
- **docs/06-Burden-of-Proof.md** — Added § 6.2 standing/merits distinction. Pure standing challenge may fail at summary judgment if plaintiff shows factual dispute. Failure-of-proof challenge requires plaintiff to prove ownership at trial. RSAF practice rule: preserve both framings. Cross-references to Chapters 12 and 18.
- **docs/11-Document-Standards.md** — Expanded from stub to full chapter covering: answer and affirmative defenses (structure, relevant defenses, no kitchen-sink rule); demurrer (Virginia practice note, grounds, structure); summary judgment and opposition (standing/merits dual framing, evidence requirements); discovery requests (interrogatories, RFPs, RFAs, bank-specific considerations); arbitration submissions (arbitrator education note); formatting table; and verification requirements.

### New Bank Playbooks

- **banks/bank-of-america/README.md** — New substantive playbook. Covers: institutional background (BANA / FIA Card Services / MBNA predecessor chain); securitization participants and roles (BANA, BA Credit Card Funding LLC, BA Master Credit Card Trust II, BA Credit Card Trust, BNY Mellon); governing agreements (RPA, PSA, Indenture, Trust Agreement); RSAF structural questions; link-by-link account-level proof requirements (5 links); predecessor entity complications; arbitration; EDGAR research checklist; applicable law table; research status tracker.
- **banks/bank-of-america/transfer-path.md** — New document. Full structural transfer diagram with governing agreement annotations at each node; link-by-link evidence checklist; predecessor entity timeline (MBNA → FIA Card Services → BANA); six common deficiency patterns; research checklist.
- **banks/capital-one/README.md** — Expanded from stub to substantive playbook. Covers: COBUSA vs. CONA originating entity distinction; securitization participants (CO Funding LLC as Virginia LLC, COMT master trust, COMET issuance trust, BNY Mellon); governing agreements including PSA §§ 6.01/6.02 removal provisions; RSAF structural questions; link-by-link account-level proof requirements; Capital One arbitration practice (AAA); servicer-is-not-owner analysis; EDGAR research checklist; Virginia UCC § 8.9A perfection note; research status tracker.
- **banks/capital-one/transfer-path.md** — New document. Full structural transfer diagram; COMT/COMET distinction explained; link-by-link evidence checklist; Virginia LLC perfection analysis; seven common deficiency patterns including COMT/COMET confusion and wrong-originating-entity errors; research checklist.

### Project Infrastructure

- **.project/DECISIONS.md** — Populated with eight architectural decisions (D-001 through D-008): program/account distinction as central filter; standing/merits parallel framing requirement; no fabricated case law in substantive chapters; chapter numbering by function; bank playbooks as research frameworks only; structural vs. account-specific chain distinction; Virginia as primary forum; gap-analysis terminus rule.
- **.project/ROADMAP.md** — Populated with v0.2.0 completion checklist, v0.3.0 template priorities, v0.4.0 bank playbook expansion order, v1.0.0 production targets, and known gaps.

### Strengthened Templates

- **templates/answer-and-affirmative-defenses.md** — Rewritten. Now includes seven substantive affirmative defenses with RSAF-specific language: (1) lack of standing / present right to enforce; (2) failure of proof on ownership element; (3) failure to state a claim / demurrer; (4) statute of limitations (Va. Code § 8.01-246(2) and (4)); (5) compulsory arbitration; (6) lack of privity / not the real party in interest; (7) failure to satisfy business records foundation. Virginia GDC and Circuit Court procedural notes. Adaptation checklist.
- **templates/discovery-requests.md** — Rewritten. Now includes 28 requests for production (chain of title, securitization program documents, Bank of America specific, Capital One specific, servicing and account records, authentication and foundation), 8 interrogatories, and 7 requests for admission. Bank-specific request blocks labeled for easy removal. AAA arbitration note. Adaptation notes.
- **templates/motion-to-compel-arbitration.md** — Rewritten. Now includes full argument structure (FAA § 2, validity of agreement, scope, no waiver, stay or dismiss), statement of facts template with exact-quote requirement for arbitration clause, filing checklist, Capital One and Bank of America specific notes.

---

## 0.2.0 — Framework Expansion (2026-06-29)

### New Chapters

- **docs/16-Documentary-Chain-of-Title.md** — New chapter explaining the structural chain vs. account-specific chain, link-by-link evaluation criteria, common deficiencies, and RSAF's chain-of-title analytical process.
- **docs/17-Rules-of-Evidence.md** — New chapter covering authentication, business records exception, acquired records, hearsay analysis, affidavit foundation, and RSAF's evidentiary checklist.

### Expanded Chapters

- **docs/05-Legal-Methodology.md** — Added Required Proof Matrix, Evidence Classification Matrix, Evidence Weight section, Alternate Explanations section, Competing Theories section, Analytical Boundaries section, The Judge's Question section, and Methodology Summary. Updated pipeline, fixed burden language, generalized bank-specific examples. Sections renumbered 5.1–5.23.
- **docs/06-Burden-of-Proof.md** — Expanded to cover claim-by-claim burden analysis (breach of contract, account stated, unjust enrichment, open account), standing element detail, defendant's role, no-negative-proof rule, gap analysis formulation, and procedural-stage analysis.
- **docs/07-Evidence-Hierarchy.md** — Expanded to cover four evidence functions, ownership evidence foundation requirements, servicing evidence limitations, balance evidence, structural evidence, authentication requirements, acquired records, evidence weight table (expanded), admissibility vs. weight distinction, document-by-document analysis, and the Required Proof Matrix.
- **docs/08-Program-vs-Account-Level-Evidence.md** — Expanded to cover the core distinction, detailed examples of each category, the RSAF rule, proper use of program documents as the evidentiary framework, the inference principle and its limits, and a catalog of common analytical errors.
- **docs/09-Securitization-Primer.md** — Substantially expanded to cover the account-receivable distinction, why banks securitize, each participant's role (originator, transferor, trust, servicer, trustee, investors), the typical transfer path diagram, true sale, servicing mechanics, charge-off and removal procedures, the two ownership theories, and a judge's summary.
- **docs/10-Receivable-Life-Cycle.md** — Expanded to eleven life-cycle stages with stage-specific documents, RSAF questions, and standing relevance for each stage. Expanded retention and reacquisition theory analysis.
- **docs/13-Virginia-Law.md** — Expanded from a stub to a substantive chapter covering Virginia court structure, pleading standards, standing, business records (Rule 2:803(6)), UCC Article 9 (§ 8.9A-109, § 8.9A-406), contract claims, limitations periods, and a research target table.
- **docs/14-Delaware-Law.md** — Expanded from a stub to a substantive chapter covering choice-of-law analysis, Delaware UCC Article 9 (6 Del. C. § 9-109, § 9-406), Delaware ABSFA, Delaware contract interpretation, and choice-of-law limits.
- **docs/15-Federal-Law.md** — Expanded from a stub to a substantive chapter covering FDCPA (15 U.S.C. § 1692 et seq.), FAA (9 U.S.C. § 2), National Bank Act preemption, SEC Regulation AB, FDIC guidance, CFPB rules, and a research target table.

### Project Files

- **.project/TERMINOLOGY.md** — Populated with canonical definitions for all key RSAF terms.

---

## 0.1.0 — Initial Framework Scaffold

- Added RSAF project charter.
- Added AGENTS.md contributor instructions.
- Added foundation chapters.
- Added initial templates.
- Added bank playbook stubs.
- Added research folders.
- Added diagram and prompt library.

# RSAF Architectural Decisions

This document records major design decisions made during RSAF development. Each entry states the decision, the alternatives considered, and the rationale.

---

## D-001: Program-Level vs. Account-Level Evidence as the Central Distinction

**Decision:** RSAF organizes its evidentiary analysis around the distinction between program-level evidence (documents establishing how a securitization program is structured) and account-level evidence (documents establishing what happened to a specific receivable). This is the primary analytical filter applied before any chain-of-title evaluation.

**Alternatives considered:** Organizing analysis by document type (e.g., bills of sale, prospectuses, affidavits); organizing by legal issue (standing, merits, damages).

**Rationale:** The program-level / account-level distinction is the most common source of analytical error in consumer credit-card collection cases. Courts and litigants frequently treat program documents as though they prove account-specific facts. Centering the framework on this distinction prevents that error at the classification stage, before the legal analysis begins.

---

## D-002: Standing vs. Merits as Distinct but Parallel Framings

**Decision:** RSAF advances both the standing challenge and the failure-of-proof-on-the-merits challenge, and requires both framings to be preserved. RSAF does not force the analysis into a single frame.

**Rationale:** Green v. Portfolio Recovery Associates, Record No. 0144-22-3 (Va. Ct. App. Dec. 17, 2024) (en banc), decided the procedural framing question: Virginia courts may treat ownership as a merits element rather than a threshold standing gate. The en banc court affirmed judgment for PRA — the plaintiff won. The holding is confined to that procedural point and does not address what documentation is legally sufficient to prove ownership.

The court did not decide whether generic bills of sale without account-specific schedules satisfy the chain-of-title evidentiary standard. It did not address the routine securitization inference or establish any evidentiary threshold for tracing a specific receivable through a securitization structure. RSAF's account-specific documentation requirements are analytically independent of Green v. PRA — the case simply did not reach those questions.

A pure standing framing may fail at summary judgment even on thin evidence if a factual dispute exists. A merits failure-of-proof framing is not defeated by a factual dispute — it requires the plaintiff to prove ownership with competent evidence at trial. Preserving both framings prevents waiver of either argument.

---

## D-003: No Case Law in Substantive Chapters Without Verification

**Decision:** RSAF chapters do not assert specific case holdings in their narrative text unless those holdings have been verified against a primary source. Chapters instead identify research targets and flag what needs to be verified.

**Rationale:** Fabricated or mischaracterized case citations are the most dangerous error a legal framework can produce. A court-facing document that cites a case for the wrong proposition, or cites a nonexistent case, destroys credibility and can harm the matter. Verified citations are collected in Chapter 18 (Authorities) and Chapter 12 (Citation Integrity). Substantive chapters reference those chapters rather than asserting their own case-law propositions.

**Key precedent for this decision:** During development, Green v. PRA was initially mischaracterized in Chapter 12. The error was caught by web search. The case was characterized as authority for the insufficiency of certain evidence; in fact, the en banc court affirmed the plaintiff's judgment. The correction led to the standing-vs-merits insight (D-002) and confirmed the need for the no-fabrication rule.

---

## D-004: Chapter Numbering Is Functional, Not Sequential by Priority

**Decision:** Chapters 00–19 are numbered by functional order (foundation, analysis, legal framework, research), not by implementation priority or importance.

**Rationale:** Implementation priority varies by case type and user need. A practitioner handling a Capital One arbitration may start at Chapter 15 (Federal Law — FAA) and the Capital One bank playbook, not at Chapter 00. Numbering by function makes the chapter map predictable. Cross-references use chapter numbers, not relative terms.

---

## D-005: Bank Playbooks Are Research Frameworks, Not Completed Analyses

**Decision:** Bank playbooks describe the expected securitization structure, identify the governing agreements, and provide evidence checklists — but they explicitly require EDGAR research before use. No playbook asserts a specific factual conclusion about what a particular bank did or did not do with a particular account.

**Rationale:** The securitization structure for each bank may vary by series vintage, may have been amended, and may differ from what the EDGAR search summary suggests. Asserting structural facts as established without verifying the operative governing document would create the same fabrication risk that D-003 addresses for case law. The playbooks are research starting points, not endpoints.

---

## D-006: Structural Chain vs. Account-Specific Chain in Chapter 16

**Decision:** Chapter 16 (Documentary Chain of Title) separates the structural chain (what the governing agreements describe as the transfer path) from the account-specific chain (the documentary record of what actually happened to the defendant's receivable). These are treated as distinct evidentiary objects with different sources and different proof requirements.

**Rationale:** The most common evidentiary error in securitization chain-of-title analysis is treating the structural chain as proof of the account-specific chain. A PSA that describes how receivables are transferred into a trust does not prove that the defendant's receivable was transferred. Separating these two concepts at the definitional level prevents the error at the analysis stage.

---

## D-007: Virginia as Primary Forum; Delaware and Federal as Supplemental

**Decision:** RSAF is designed for Virginia proceedings as the primary forum. Delaware law is addressed because many cardmember agreements select Delaware law. Federal law is addressed because FDCPA, FAA, National Bank Act, and Regulation AB recur across cases. Other states are not addressed in Version 0.2.

**Rationale:** Scope limitation is necessary to maintain quality. A framework that tries to cover all jurisdictions ends up being accurate about none of them. Virginia GDC and Circuit Court are the likely initial forums for active cases. Delaware and federal law appear in Virginia cases due to choice-of-law clauses and federal preemption.

---

## D-008: Terminus for Evidentiary Gap Analysis

**Decision:** RSAF states evidentiary gaps (what is missing and why it is required) but does not reach the factual conclusion that the transfer did not occur or that the plaintiff does not own the receivable. Factual conclusions are for the court.

**Rationale:** RSAF is a litigation support framework, not a factfinder. Stating that "the plaintiff has not produced account-specific documentation for Link 3" is an accurate description of the evidentiary record. Stating that "therefore the plaintiff does not own the receivable" is a factual conclusion that requires a judicial determination. The second statement can be wrong and, if asserted in a court-facing document, creates credibility problems if the plaintiff later produces the missing document. RSAF states the record; the advocate makes the argument; the court decides.

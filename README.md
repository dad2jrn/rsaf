# Receivable Standing Analysis Framework (RSAF)

> **An evidence-first methodology for evaluating whether a plaintiff has established its present legal right to enforce a consumer credit-card receivable.**

**Current Version:** 0.7.0

---

## Purpose

The Receivable Standing Analysis Framework (RSAF) is an evidence-first legal methodology for evaluating whether a plaintiff has established its present legal right to enforce a consumer credit-card receivable.

RSAF does not presume that a plaintiff possesses standing, nor does it presume the absence of standing. Instead, it evaluates the plaintiff's proof against the governing law, the plaintiff's own governing agreements, applicable public disclosures, and the evidentiary record before the court.

The framework was developed to provide a disciplined, transparent, and repeatable methodology for analyzing standing in consumer credit-card litigation involving modern securitization structures.

---

# Guiding Philosophy

RSAF is built upon a simple proposition:

> Courts decide cases on evidence—not assumptions.

Every conclusion produced by RSAF must be traceable to competent evidence, governing contractual documents, applicable statutes, controlling case law, or clearly identified analytical inferences.

RSAF never invents facts.

RSAF never invents legal authority.

RSAF never shifts the burden of proof.

RSAF never fills evidentiary gaps through speculation.

---

# Scope

RSAF currently covers:

- Consumer credit-card collection litigation
- Virginia procedural law
- Delaware substantive law where selected by the governing Cardmember Agreement
- Applicable federal law (FDCPA, FAA, National Bank Act, Regulation AB, FDIC Safe Harbor)
- Credit-card securitization programs, where applicable
- Arbitration and judicial proceedings

RSAF is designed to work regardless of which bank originated the account, which trust structure applies, or which transfer path is relevant. Bank-specific playbooks supplement the framework when verified EDGAR research is available; the core methodology operates without them.

The framework is bank-neutral — it does not assume any particular originator, trust structure, or transfer path — but it is currently jurisdiction-scoped to Virginia procedure and Delaware or federal substantive law. Future versions may expand into additional jurisdictions and other classes of consumer receivables.

---

# What RSAF Is

RSAF is:

- an evidence-first legal methodology;
- a litigation analysis framework;
- a legal research methodology;
- a documentary evidence evaluation framework;
- an AI-assisted drafting system built upon verifiable authority.

RSAF is intended to assist attorneys, pro se litigants, researchers, educators, and legal professionals in evaluating whether a plaintiff has produced sufficient evidence to establish its present legal right to enforce a specific consumer receivable.

---

# What RSAF Is Not

RSAF is not:

- legal advice;
- a substitute for independent legal judgment;
- a guarantee of any litigation outcome;
- a collection of boilerplate motions;
- a framework designed to avoid legitimate debts.

RSAF exists to evaluate whether the evidentiary record satisfies the plaintiff's burden under the governing law.

---

# The Central Question

Every RSAF analysis ultimately seeks to answer one question:

> **Has the plaintiff produced competent, admissible, account-specific evidence sufficient to establish its present legal right to enforce the receivable it seeks to collect?**

"Present legal right to enforce" is not synonymous with ownership. A plaintiff may establish that right through ownership, assignment, reassignment, servicing authority, agency authority, or other legally recognized bases, depending on the governing agreements, applicable statutes, and the evidentiary record. RSAF identifies which basis the plaintiff asserts and evaluates the evidence required to establish it.

Every chapter within RSAF exists to assist in answering the central question.

---

# Core Principles

RSAF is built upon the following foundational principles:

1. Evidence precedes argument.
2. The plaintiff bears the burden of proving every required element of its claim.
3. Standing must be established through competent evidence.
4. Documentary evidence carries greater weight than unsupported assertions.
5. Publicly filed governing agreements define the plaintiff's securitization framework.
6. Account-specific evidence establishes what occurred with the defendant's receivable.
7. Governing law controls every legal conclusion.
8. Every material conclusion must identify its evidentiary basis.
9. Every legal proposition must identify its supporting authority.
10. Every document produced by RSAF must be suitable for filing in a court of law.

---

# Repository Organization

```text
docs/
    Foundational chapters (00–22)
banks/
    PLAYBOOK-SCHEMA.md — required structure for all bank playbooks
    [bank]/README.md  — substantive draft or research stub
    [bank]/transfer-path.md — transfer-path diagram and evidence checklist
research/
    Primary legal authorities
templates/
    Litigation document templates
diagrams/
    Reference illustrations
```

---

# Methodology Overview

Every RSAF analysis follows the same twelve-step sequence. The sequence is not optional; skipping a step risks reaching a legal conclusion before the evidentiary foundation exists.

```text
1.  Identify procedural posture and requested outcome
            ↓
2.  Identify governing law and choice-of-law provisions
            ↓
3.  Identify the plaintiff and each relevant entity
            ↓
4.  Identify the plaintiff's asserted present legal right to enforce
            ↓
5.  Identify the possible enforcement theories supported by the record
            ↓
6.  Inventory all evidence and classify it by source and evidentiary function
            ↓
7.  Separate account-level evidence from program-level evidence
            ↓
8.  Classify each proposition as proven fact, reasonable inference,
    unresolved legal question, alternative explanation, or speculation
            ↓
9.  Determine the documents and testimony necessary to prove
    the plaintiff's asserted theory
            ↓
10. Identify proof gaps, inconsistencies, missing links,
    and unresolved factual predicates
            ↓
11. Research controlling authority before reaching legal conclusions
            ↓
12. Draft a narrowly tailored litigation analysis or work product
    that accurately reflects the evidentiary record
```

Step 7 applies the central evidentiary distinction: **program-level evidence** (prospectuses, PSAs, TSAs, SEC filings) establishes the plaintiff's own transfer framework and defines what account-level proof should exist. **Account-level evidence** (executed assignments, bills of sale with account schedules, removal notices, reassignment instruments) proves what actually occurred with the specific receivable at issue. Neither category substitutes for the other. See Chapter 08 for the complete treatment.

---

# Writing Standards

RSAF writes for a skeptical trial judge.

Accordingly, every document should:

- teach before arguing;
- explain before concluding;
- distinguish fact from inference;
- distinguish binding authority from persuasive authority;
- avoid rhetorical exaggeration;
- avoid AI-generated writing patterns;
- avoid unnecessary legal jargon;
- remain concise without sacrificing precision.

---

# Research Standards

RSAF relies upon primary authority whenever reasonably available.

Preferred order of authority:

1. Constitutions
2. Statutes
3. Rules
4. Controlling appellate opinions
5. Governing contracts
6. SEC filings
7. Regulatory guidance
8. Secondary authorities

---

# Project Status

RSAF is currently under active development.

Every chapter is version controlled.

Every substantive legal proposition is subject to continuous review and refinement.

Accuracy takes precedence over speed.

Evidence takes precedence over assumption.

Truth takes precedence over advocacy.

---

# License

See `LICENSE.md`.

---

# Contributing

See `CONTRIBUTING.md`.

---

# Disclaimer

RSAF is an educational and litigation-support framework. It is not a law firm, does not provide legal advice, and cannot substitute for independent legal judgment. Users remain responsible for verifying every factual assertion, legal citation, and procedural requirement applicable to their jurisdiction and case.
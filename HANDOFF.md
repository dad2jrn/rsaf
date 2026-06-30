# RSAF Project Handoff

**Project:** Receivable Standing Analysis Framework (RSAF)

**Status:** v0.7.0 — Substantive chapters complete. Active research and refinement.

---

# Read This First

If you read only one sentence in this document, read this one.

> **RSAF is not a debt-defense project. It is an evidence-first methodology for evaluating whether a plaintiff has established its present legal right to enforce a consumer credit-card receivable.**

If you lose that principle, you lose the project.

Everything else is implementation.

---

# Mission

RSAF seeks to become the definitive methodology for analyzing standing in consumer credit-card litigation.

It is **not** intended to help defendants avoid legitimate debts.

It is intended to answer one question:

> Has the plaintiff carried its burden of proving its present legal right to enforce the receivable it seeks to collect?

That question governs every chapter.

---

# Current State

RSAF is at v0.7.0.

All 22 substantive chapters are complete.

The framework is bank-neutral: the core methodology operates without reference to any particular originator, trust structure, or transfer path. Bank-specific playbooks supplement the framework when verified EDGAR research is available.

MASTER-INSTRUCTIONS.md and AGENTS.md govern AI analysis. Read both before beginning any analysis.

Three open legal questions are tracked in OPEN-LEGAL-QUESTIONS.md. The highest-priority unresolved question is OLQ-001: whether Virginia, Delaware, or federal evidence law recognizes a rebuttable inference that a specific receivable was transferred because the issuing bank routinely transferred eligible receivables pursuant to a disclosed securitization program.

Do not redesign the architecture.

Research, apply, and refine.

---

# Core Philosophy

RSAF is built upon five foundational ideas.

## 1. Evidence First

Arguments do not create evidence.

Evidence supports arguments.

Always analyze evidence before reaching legal conclusions.

---

## 2. Plaintiff Bears the Burden

Never shift the burden.

The defendant is not required to prove the plaintiff lacks standing.

The defendant evaluates whether the plaintiff has proven standing.

That distinction must remain throughout the project.

---

## 3. Structural Evidence ≠ Transaction Evidence

This distinction is one of RSAF's defining contributions.

Structural evidence explains how a plaintiff's securitization program operates.

Examples:

- Prospectuses
- Transfer and Servicing Agreements
- Receivables Purchase Agreements
- Trust Agreements
- SEC filings
- Annual Reports

Structural evidence defines the framework.

It does **not**, standing alone, establish what happened to the defendant's receivable.

Transaction evidence establishes what occurred with the specific receivable.

Examples:

- Executed assignments
- Executed reassignments
- Bills of sale
- Schedules
- Account-specific transfer documents

Never confuse these categories.

---

## 4. Teach Before Arguing

Assume the reader is a busy trial judge.

The judge probably knows very little about:

- credit-card securitization
- bankruptcy-remote entities
- receivable transfers
- true sales
- asset-backed securities

Explain concepts before drawing legal conclusions.

Never overwhelm the reader with jargon.

---

## 5. Intellectual Honesty

RSAF must remain credible.

Never exaggerate.

Never overstate authority.

Never invent evidence.

Never invent legal citations.

Never assume facts.

Whenever uncertainty exists, identify it.

---

# What Makes RSAF Different

RSAF is not a collection of motions.

It is not a prompt library.

It is not a chatbot.

It is a methodology.

Every chapter should reinforce that methodology.

---

# Writing Style

Write like an experienced appellate attorney or federal district judge.

Avoid:

- AI clichés
- repetitive transitions
- unnecessary em dashes
- exaggerated rhetoric
- marketing language
- dramatic prose

Prefer:

- short paragraphs
- precise definitions
- logical progression
- plain English
- careful legal analysis

Teach.

Then argue.

---

# The Audience

There are three audiences.

## AI

Needs:

- methodology
- workflow
- reasoning

---

## Human User

Needs:

- education
- guidance
- research support

---

## Trial Judge

Needs:

- concise explanations
- documentary support
- governing law
- logical analysis

Always write for the judge.

---

# Repository Philosophy

The repository is the source of truth.

Not the conversation.

Every significant idea belongs in the repository.

Do not rely upon conversation history.

---

# The Chapters

RSAF contains 22 substantive chapters, organized by function.

**Framework Foundation**

0. Introduction
1. Constitution
2. Guiding Principles
3. Writing Standards
4. Judicial Communication

**Core Analytical Methodology**

5. Legal Methodology
6. Burden of Proof
7. Evidence Hierarchy
8. Program-Level vs. Account-Level Evidence

**Securitization and Receivable Structure**

9. Securitization Primer
10. Receivable Life Cycle
11. Document Standards
12. Citation Integrity

**Governing Law**

13. Virginia Law
14. Delaware Law
15. Federal Law

**Chain of Title and Evidence**

16. Documentary Chain of Title
17. Rules of Evidence
18. Authorities
19. Research Methodology

**Advanced Analysis**

20. Plaintiff Theory Identification
21. Inference Classification
22. Routine Securitization Practice

---

# Supplementary Resources

**Glossary.md** — Plain-language definitions of key terms. Distinguishes commonly confused concepts: servicer vs. owner, standing vs. ownership, legal title vs. beneficial ownership, assignee vs. holder, present legal right to enforce vs. historical ownership.

**OPEN-LEGAL-QUESTIONS.md** — Register of legal questions material to RSAF analysis that have not been resolved by binding authority. Three current entries:

- OLQ-001: Routine Securitization Inference (high priority — unresolved)
- OLQ-002: Servicer Standing to Sue in Own Name (medium priority)
- OLQ-003: Delaware ABSFA Effect on Virginia Analysis (low priority)

**Bank Playbooks** — Eight bank-specific research frameworks in the `banks/` directory. Current playbooks: American Express, Bank of America, Capital One, Chase, Citi, Discover, Synchrony, Wells Fargo. Each playbook is a research framework, not an advocacy file, and does not presume any particular outcome. `banks/PLAYBOOK-SCHEMA.md` defines the required structure.

**Templates** — Four litigation document templates in the `templates/` directory: answer and affirmative defenses, debt verification letter, discovery requests, motion to compel arbitration.

---

# The Analysis Pipeline

Every RSAF analysis follows this twelve-step sequence. The sequence is not optional; skipping a step risks reaching a legal conclusion before the evidentiary foundation exists.

```
1. Identify procedural posture and requested outcome
           ↓
2. Identify governing law and choice-of-law provisions
           ↓
3. Identify the plaintiff and each relevant entity
           ↓
4. Identify the plaintiff's asserted present legal right to enforce
           ↓
5. Identify the possible enforcement theories supported by the record
           ↓
6. Inventory all evidence and classify it by source and evidentiary function
           ↓
7. Separate account-level evidence from program-level evidence
           ↓
8. Classify each proposition as proven fact, reasonable inference,
   unresolved legal question, alternative explanation, or speculation
           ↓
9. Determine the documents and testimony necessary to prove
   the plaintiff's asserted theory
           ↓
10. Identify proof gaps, inconsistencies, missing links,
    and unresolved factual predicates
           ↓
11. Research controlling authority before reaching legal conclusions
           ↓
12. Draft a narrowly tailored analysis or work product
    that accurately reflects the evidentiary record
```

Never reverse this order.

Drafting is one of the final steps.

Not the first.

---

# Research Standards

Always prefer:

1. Constitution
2. Statutes
3. Rules
4. Binding appellate opinions
5. Governing contracts
6. SEC filings
7. Regulatory guidance
8. Secondary authority

Verify every citation.

Never fabricate quotations.

Never fabricate holdings.

Never extend holdings beyond what they support.

---

# Important Legal Principle

One recurring principle runs throughout RSAF.

The plaintiff's publicly filed securitization documents may establish the contractual framework governing receivable transfers.

Those documents define:

- transfer mechanisms
- reassignment mechanisms
- documentary requirements
- participants

They do not establish what occurred with the defendant's specific receivable.

If standing is challenged, the plaintiff bears the burden of proving its present right to enforce that receivable.

RSAF evaluates whether the plaintiff's evidence satisfies that burden.

Avoid categorical statements that every receivable was transferred unless supported by evidence and governing law.

The framework identifies evidentiary gaps — it does not fill them.

---

# What Not To Do

Do not become outcome-driven.

Do not write advocacy disguised as methodology.

Do not begin with conclusions.

Do not create unsupported legal theories.

Do not weaken the project's credibility by overstating arguments.

The framework must be capable of concluding that the plaintiff has standing when the evidence supports that conclusion.

Credibility is RSAF's greatest asset.

Protect it.

---

# Quality Standard

Every chapter should be good enough to publish as a standalone legal handbook chapter.

Do not write placeholders.

Do not leave TODO sections.

Write complete work.

Assume every chapter will eventually be read by attorneys, judges, professors, and researchers.

---

# Final Advice

If forced to choose between:

being persuasive

or

being accurate,

choose accuracy.

A careful, intellectually honest framework will ultimately become far more persuasive than one that overstates its claims.

Protect the methodology.

The methodology is the project.

Everything else is implementation.

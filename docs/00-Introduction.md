# 00 — Introduction

**Status:** Current  
**Version:** 0.4.0

---

## 0.1 Purpose

The Receivable Standing Analysis Framework (RSAF) is an evidence-first legal methodology for evaluating whether a plaintiff has established its present legal right to enforce a consumer credit-card receivable.

RSAF exists because many collection cases are litigated as though the existence of monthly statements or a charged-off account automatically proves that the plaintiff owns the legal right to collect the receivable. In modern credit-card finance, that assumption may be incomplete. Credit-card receivables are often transferred through asset-backed securitization programs involving bankruptcy-remote entities, trusts, servicing agreements, transfer agreements, prospectuses, and public filings.

RSAF provides a disciplined method for identifying what the plaintiff must prove, what evidence the plaintiff has produced, and whether that evidence satisfies the governing law.

---

## 0.2 Core Question

RSAF asks one central question:

> Has the plaintiff produced competent, admissible, account-specific evidence sufficient to establish its present legal right to enforce the receivable it seeks to collect?

Everything else in RSAF exists to answer that question.

---

## 0.3 Scope

Version 0.2 focuses on consumer credit-card collection litigation involving Virginia procedure, Delaware law where selected by the cardmember agreement, and applicable federal law. Bank-specific playbooks cover Bank of America, Capital One, Chase, Citi, Discover, Synchrony, Wells Fargo, and American Express.

RSAF is designed for matters involving original creditors, debt buyers, banks acting as servicers, and entities that claim the right to enforce unpaid credit-card balances.

---

## 0.4 What RSAF Is

RSAF is:

- A legal methodology.
- An evidence-analysis framework.
- A litigation-support system.
- A research framework.
- A drafting framework when a specific document is requested.

---

## 0.5 What RSAF Is Not

RSAF is not legal advice. It is not a guarantee of any outcome. It is not a substitute for independent legal judgment. It is not a collection of canned motions. It does not assume that every plaintiff lacks standing. It does not assume that every securitized receivable was transferred or reacquired in any particular way.

RSAF evaluates proof.

---

## 0.6 Judicial Audience

RSAF assumes the reader may be a busy trial judge with limited familiarity with asset-backed securities, receivables purchase agreements, transfer and servicing agreements, or credit-card securitization structures. RSAF therefore teaches before arguing. It explains unfamiliar financial structures in plain English before applying legal authority.

---

## 0.7 The Foundational Distinction

RSAF distinguishes between a credit-card account and the receivable arising from that account.

The account is the consumer relationship and credit facility. The receivable is the right to payment arising from charges, fees, interest, or other obligations associated with that account.

A bank may remain the account owner or servicer while the receivable has been transferred elsewhere. Whether that occurred in a particular case must be proven by competent, account-specific evidence.

---

## 0.8 Chapter Map

### Foundation

| Chapter | Title | Purpose |
|---|---|---|
| 01 | Constitution | Core rules; immutable constraints on RSAF |
| 02 | Guiding Principles | Analytical principles governing every analysis |
| 03 | Writing Standards | Style and tone requirements for RSAF output |
| 04 | Judicial Communication | How to write for a skeptical trial judge |
| 05 | Legal Methodology | The full analytical pipeline; start here for a new matter |

### Core Analysis

| Chapter | Title | Purpose |
|---|---|---|
| 06 | Burden of Proof | Who must prove what; standing vs. merits distinction |
| 07 | Evidence Hierarchy | How to weigh and classify evidence |
| 08 | Program vs. Account-Level Evidence | The central evidentiary distinction |
| 09 | Securitization Primer | What securitization is and how it works |
| 10 | Receivable Life Cycle | Eleven stages from origination through litigation |
| 16 | Documentary Chain of Title | Link-by-link chain evaluation |
| 17 | Rules of Evidence | Admissibility, authentication, business records |

### Legal Framework

| Chapter | Title | Purpose |
|---|---|---|
| 13 | Virginia Law | Virginia procedure, evidence rules, UCC, limitations |
| 14 | Delaware Law | Delaware trust and contract law; ABSFA; choice-of-law |
| 15 | Federal Law | FDCPA, FAA, National Bank Act, Regulation AB, FDIC Safe Harbor |

### Advanced Analysis

| Chapter | Title | Purpose |
|---|---|---|
| 20 | Plaintiff Theory Identification | Identify which of seven enforcement theories the plaintiff asserts before evaluating evidence |
| 21 | Inference Classification | Classify each conclusion: Proven Fact, Documentary Inference, Legal Inference, Competing Explanation, Open Legal Question, or Speculation |
| 22 | Routine Securitization Practice | Open legal question: whether documented routine practice creates an inference of specific transfer |

### Research and Integrity

| Chapter | Title | Purpose |
|---|---|---|
| 11 | Document Standards | Format and content requirements for court filings |
| 12 | Citation Integrity | Rules for citing authority; Green v. PRA analysis |
| 18 | Authorities | Virginia table of authorities for chain-of-title challenges |
| 19 | Research Methodology | How to research case law, statutes, and SEC filings |

### Terminology and Open Questions

| Resource | Location | Purpose |
|---|---|---|
| Glossary | Glossary.md | Plain-language definitions for judges and attorneys; common confusions clarified |
| Terminology | .project/TERMINOLOGY.md | Canonical definitions for all RSAF terms (contributor reference) |
| Open Legal Questions | OPEN-LEGAL-QUESTIONS.md | Registry of unresolved legal questions material to RSAF analysis |

---

## 0.9 Bank Playbooks

RSAF includes bank-specific playbooks in the `banks/` directory. Each playbook identifies the securitization structure, the governing agreements, the transfer path, and the account-level evidence required for that bank's program.

| Bank | Status | Notes |
|---|---|---|
| Bank of America | Substantive draft | Two-tier trust; FIA/MBNA predecessor chain; research required |
| Capital One | Substantive draft | Virginia LLC depositor; COMT/COMET distinction; PSA §§ 6.01/6.02 |
| Chase | Stub | Research required |
| Citi | Stub | Research required |
| Discover | Stub | Research required |
| Synchrony | Stub | Research required |
| Wells Fargo | Stub | Research required |
| American Express | Stub | Research required |

---

## 0.10 How to Use RSAF on a New Matter

1. **Read Chapter 05 (Legal Methodology).** The complete analytical pipeline. Identify the claim, the forum, and the governing law.
2. **Identify the plaintiff's enforcement theory (Chapter 20).** Before evaluating evidence, determine what legal right the plaintiff is asserting and how it claims to hold it.
3. **Identify the originating bank.** Pull the applicable bank playbook from `banks/`.
4. **Apply the securitization primer (Chapter 09)** and the receivable life cycle (Chapter 10) to understand what documents should exist at each stage.
5. **Catalog the evidence produced.** Apply Chapter 07 (Evidence Hierarchy) and Chapter 08 (Program vs. Account-Level Evidence) to classify each document.
6. **Classify each inference (Chapter 21).** For every conclusion drawn from the evidence, identify whether it is a proven fact, supported inference, legal inference, competing explanation, open question, or speculation.
7. **Evaluate the chain of title (Chapter 16).** Identify which links are supported by account-specific evidence and which are gaps.
8. **Apply the burden (Chapter 06).** State what is unproven, why it is required, and what follows under the plaintiff's burden.
9. **Apply the applicable law.** Use Chapter 13 (Virginia), Chapter 14 (Delaware), or Chapter 15 (Federal) as the forum requires.
10. **Check citation integrity (Chapter 12)** before relying on any case, statute, or filing.
11. **Draft only if requested (Chapter 11).** Court-facing documents are produced only when explicitly requested.

**Unfamiliar terms:** See Glossary.md for plain-language definitions. See .project/TERMINOLOGY.md for the complete canonical term list.

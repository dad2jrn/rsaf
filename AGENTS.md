# AGENTS.md

Receivable Standing Analysis Framework (RSAF)
Version: 0.1.0
Status: Draft
Jurisdictions: Virginia, Delaware, applicable federal law

## 1. Project Identity

RSAF is an evidence-first legal methodology for evaluating whether a plaintiff has established its present legal right to enforce a consumer credit-card receivable.

RSAF is not a debt-avoidance script, a canned-motion generator, or a tool for fabricating defenses. It is a disciplined framework for analyzing standing, ownership, transfer, reassignment, admissibility, and burden of proof in consumer credit-card collection litigation.

## 2. Core Rule

Do not begin with the conclusion. Begin with the plaintiff's burden, the governing law, the governing documents, and the evidence actually produced.

The central question is:

> Has the plaintiff produced competent, admissible, account-specific evidence sufficient to establish its present legal right to enforce the receivable it seeks to collect?

## 3. Non-Negotiable Standards

Any AI agent, editor, or contributor working on RSAF must follow these rules.

### 3.1 No Fabrication

Never invent:

- case citations;
- statutory citations;
- quotations;
- holdings;
- docket numbers;
- SEC filings;
- contract provisions;
- exhibit numbers;
- procedural facts;
- court rules;
- regulatory requirements.

If a citation, quote, statute, filing, or rule has not been verified from a reliable source, mark it as unverified and do not present it as authority.

### 3.2 Primary Sources First

Prefer sources in this order:

1. Constitutional provisions, where relevant.
2. Statutes.
3. Rules of court and rules of evidence.
4. Binding appellate opinions.
5. Binding trial-court authority, where applicable.
6. Governing contracts and transaction documents.
7. SEC filings and other public filings.
8. Regulatory guidance.
9. Persuasive authority.
10. Secondary sources.

Do not use blog posts, summaries, AI-generated content, or commentary as legal authority unless they are being used only for background research and clearly identified as such.

### 3.3 Burden of Proof

RSAF does not attempt to prove a negative. It evaluates whether the plaintiff has carried its own burden.

The plaintiff bears the burden of proving each element of its claim, including standing and present right to enforce where those issues are contested.

Do not shift that burden to the defendant. Do not require the defendant to prove the plaintiff does not own the receivable. The defendant may use the plaintiff's own public documents, governing agreements, and legal authorities to show why the plaintiff's proof is incomplete or legally insufficient.

### 3.4 Program-Level Versus Account-Level Evidence

Program-level documents may show how a bank's securitization program operates. These may include prospectuses, trust agreements, receivables purchase agreements, transfer and servicing agreements, pooling and servicing agreements, 10-K filings, 10-D filings, UCC filings, and investor disclosures.

Program-level documents do not, by themselves, prove what happened to a specific consumer's receivable.

Account-level evidence is needed to prove ownership of the specific receivable. This may include executed assignments, executed reassignments, schedules identifying the account, bills of sale, collateral certificates, removal notices, or other account-specific transfer records.

The distinction is central to RSAF.

### 3.5 Program Creates the Evidentiary Framework

The plaintiff's public securitization documents are relevant because they define the contractual structure, transfer path, and documentary mechanisms by which receivables are sold, removed, reacquired, or reassigned.

If the plaintiff claims to own a receivable within an industry structure where eligible receivables are routinely transferred, the plaintiff should be expected to prove one of two things with competent evidence:

1. the specific receivable was never transferred; or
2. the specific receivable was transferred and later reacquired through the procedures required by the governing agreements.

RSAF must not ask the court to assume the plaintiff lacks ownership. It must ask whether the plaintiff has proven ownership through the documents required by the plaintiff's own legal structure and the applicable law.

### 3.6 Judicial Communication

Write for a busy trial judge who is intelligent but may have limited familiarity with asset-backed securities, credit-card securitization, bankruptcy-remote entities, or receivable-transfer documentation.

Teach first. Argue second.

Prefer a clear sequence:

1. What is the issue?
2. What is a receivable?
3. How can a receivable be transferred?
4. What documents govern the transfer?
5. What documents prove the transfer?
6. What evidence has the plaintiff produced?
7. Has the plaintiff met its burden?

### 3.7 Writing Style

RSAF writing must be precise, natural, and court-appropriate.

Avoid common AI signals:

- excessive em dashes;
- repetitive paragraph openings;
- inflated wording;
- unnecessary adjectives;
- formulaic transitions;
- generic phrases such as "it is important to note," "delve," "robust," "in today's legal landscape," or "furthermore" repeated across paragraphs.

Use plain English where possible. Use legal terms when necessary. Define technical terms before relying on them.

### 3.8 Legal Document Formatting

When generating court documents, use standard legal formatting appropriate to the court and jurisdiction.

A pleading should include, when required:

- proper court caption;
- case number;
- party designations;
- document title;
- numbered paragraphs;
- responses corresponding to the complaint;
- affirmative defenses, if requested and supported;
- prayer for relief, where appropriate;
- signature block;
- certificate of service;
- verification block, if required.

Do not generate pleadings unless specifically requested by the user.

### 3.9 Defendant's Answer and Affirmative Defenses

When the user requests an "Answer," RSAF must treat that as the defendant's responsive pleading unless the user specifies otherwise.

The Answer may include affirmative defenses only if the user requests them or if the jurisdiction requires them to be raised in the responsive pleading and the user asks for a complete responsive pleading.

RSAF must warn the user when defenses may be waived if omitted.

### 3.10 Citation Integrity

Every cited authority must include enough information to verify it:

- case name;
- reporter citation or official database citation;
- court;
- year;
- proposition supported;
- whether the authority is binding or persuasive;
- exact quotation only if verified.

Do not use a citation if it has not been verified.

### 3.11 Confidence Classification

Internally classify each legal conclusion:

- Level A: binding authority directly on point;
- Level B: binding authority by analogy;
- Level C: persuasive authority;
- Level D: supported by governing documents or public filings;
- Level E: analytical inference requiring explicit qualification.

Do not present Level D or E conclusions as if they were Level A law.

## 4. RSAF Analysis Pipeline

Use this sequence before generating analysis or documents:

1. Identify procedural posture.
2. Identify court and jurisdiction.
3. Identify plaintiff, defendant, original creditor, and current claimant.
4. Identify governing agreement and choice-of-law clause.
5. Identify applicable Virginia law, Delaware law, and federal law.
6. Identify plaintiff's burden.
7. Collect plaintiff's evidence.
8. Collect relevant public program documents.
9. Separate program-level evidence from account-level evidence.
10. Identify the bank's receivable transfer path.
11. Identify the reacquisition path under the governing agreements.
12. Identify documents required to prove each transfer or reacquisition.
13. Compare required proof to evidence produced.
14. Identify gaps, if any.
15. Verify all legal authorities.
16. Draft only the document specifically requested.
17. Apply legal formatting standards.
18. Perform final quality-assurance review.

## 5. Standard Final Review

Before finalizing any RSAF document, ask:

1. Does this shift the burden to the defendant? If yes, revise.
2. Does every material factual claim identify its evidentiary basis? If no, revise.
3. Does every legal proposition cite verified authority? If no, remove or verify.
4. Does the document distinguish account ownership from receivable ownership? If relevant and not addressed, revise.
5. Does the document distinguish servicing records from ownership evidence? If relevant and not addressed, revise.
6. Does the document explain technical concepts before relying on them? If no, revise.
7. Would a busy trial judge understand the argument within minutes? If no, simplify.
8. Does the document contain AI-style phrasing? If yes, humanize.
9. Is the document properly formatted for the requested court? If no, revise.
10. Does the document overstate the law or the evidence? If yes, revise.

## 6. Project Conduct

RSAF is intended for educational, research, and litigation-support purposes. It is not a substitute for independent legal judgment. Contributors must preserve the integrity, neutrality, and evidence-first character of the framework.

# RSAF Project Charter

## Mission

RSAF exists to help users analyze whether a plaintiff has proven its present legal right to enforce a consumer credit-card receivable.

## Design Standard

RSAF must remain useful even if AI disappeared tomorrow. A person should be able to print the Markdown files and use the framework as a legal research and litigation-support manual.

## Current Scope

RSAF covers:

1. Virginia litigation procedure and standing concepts.
2. Delaware law where selected by cardmember agreements.
3. Applicable federal law, including FDCPA, FAA, National Bank Act, Regulation AB, and FDIC Safe Harbor.
4. Credit-card receivables originated by banks and other issuers.
5. Cases with and without securitization — the framework does not presume that receivables were transferred, retained, or reacquired in any particular way.
6. Asset-backed securitization structures where applicable, including receivables purchase agreements, transfer and servicing agreements, trusts, bankruptcy-remote entities, and public SEC filings.

Bank-specific playbooks in the `banks/` directory supplement the generic framework when verified EDGAR research supports them. The generic framework operates independently of any bank playbook.

## Design Goals

1. Keep the plaintiff's burden on the plaintiff.
2. Separate program-level evidence from account-level evidence.
3. Explain securitization simply enough for a busy trial judge.
4. Use the plaintiff's own public documents to identify the documentary path by which receivables are transferred and, where applicable, reacquired.
5. Generate litigation documents only when specifically requested.
6. Avoid AI writing fingerprints.
7. Never invent legal authority.
8. Maintain standard legal formatting for all generated pleadings.

## Golden Rule

RSAF does not ask the court to infer that a plaintiff has a right to enforce. It asks the court to determine whether the plaintiff has proven its present legal right to enforce through the documentary evidence required by the plaintiff's own governing agreements, applicable law, and whatever enforcement theory the plaintiff has asserted.

Ownership is one basis for enforcement. It is not the only basis. The analysis begins with the plaintiff's theory, not with an assumption about how the receivable must have been held.

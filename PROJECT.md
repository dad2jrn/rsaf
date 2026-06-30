# RSAF Project Charter

## Mission

RSAF exists to help users analyze whether a plaintiff has proven its present legal right to enforce a consumer credit-card receivable.

## Design Standard

RSAF must remain useful even if AI disappeared tomorrow. A person should be able to print the Markdown files and use the framework as a legal research and litigation-support manual.

## Scope of Version 0.1

RSAF v0.1 focuses on:

1. Virginia litigation procedure and standing concepts.
2. Delaware law where selected by cardmember agreements.
3. Applicable federal law, including FDCPA concepts when relevant.
4. Credit-card receivables originated by national banks.
5. Asset-backed securitization structures involving receivables purchase agreements, transfer and servicing agreements, trusts, bankruptcy-remote entities, and public SEC filings.

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

RSAF does not ask the court to infer ownership. It asks the court to determine whether the plaintiff has proven ownership through the documentary evidence required by the plaintiff's own governing agreements and applicable law.

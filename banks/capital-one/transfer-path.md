# Capital One — Transfer Path Analysis

**Status:** Structural framework — verify all governing document references against EDGAR before use  
**Version:** 0.2.0

---

## Purpose

This document maps the expected transfer path for Capital One credit-card receivables through the securitization structure (RPA → PSA → COMT → removal → reassignment → sale), identifies the governing agreement at each node, and states the account-level evidence RSAF requires to verify that a specific receivable traveled this path.

---

## Structural Transfer Diagram

```text
┌──────────────────────────────────────────────────────────────────┐
│            Capital One Bank (USA), N.A. (COBUSA)                │
│                                                                  │
│  Role: Originating bank; seller; ongoing servicer                │
│  Charter: National bank; OCC-regulated                           │
│  Also note: Capital One, N.A. (CONA) also originates accounts   │
│  — verify originating entity for each specific account           │
└───────────────────────┬──────────────────────────────────────────┘
                        │
                        │  RECEIVABLES PURCHASE AGREEMENT (RPA)
                        │  • COBUSA sells eligible receivables to
                        │    Capital One Funding, LLC
                        │  • True-sale treatment intended to remove
                        │    receivables from COBUSA's bankruptcy estate
                        │  • Account-level proof needed: account schedule
                        │    or supplement listing defendant's account
                        ▼
┌──────────────────────────────────────────────────────────────────┐
│               Capital One Funding, LLC                           │
│                                                                  │
│  Role: Bankruptcy-remote transferor / depositor                  │
│  Entity: Virginia limited liability company                      │
│  Purpose: Insulates trust from bank insolvency                   │
│  UCC: Virginia UCC § 8.9A governs perfection of transfer        │
│       (Virginia SCC is the filing office)                        │
└───────────────────────┬──────────────────────────────────────────┘
                        │
                        │  AMENDED AND RESTATED PSA (or TSA)
                        │  • Capital One Funding, LLC conveys
                        │    receivables to Capital One Master Trust
                        │  • Governs: (1) transfer into trust;
                        │    (2) servicer duties (COBUSA as servicer);
                        │    (3) addition of new accounts;
                        │    (4) removal of ineligible receivables (§ 6.01);
                        │    (5) removal for breach of reps (§ 6.02);
                        │    (6) reassignment upon removal
                        │  • Account-level proof needed: account schedule
                        │    or collateral certificate showing defendant's
                        │    account included in COMT pool
                        ▼
┌──────────────────────────────────────────────────────────────────┐
│          Capital One Master Trust (COMT)                         │
│                                                                  │
│  Role: Master trust; legal owner of receivables in pool          │
│  Entity: Statutory trust (Virginia or Delaware — verify)         │
│  Trustee: Bank of New York Mellon (verify for specific series)   │
│  Beneficiary: Capital One Funding, LLC (as transferor)           │
│                                                                  │
│  COMT holds the receivable unless and until removed.             │
│  COBUSA services accounts as servicer for COMT.                 │
│  COMT issues collateral certificates to COMET.                  │
│                                                                  │
│  COMET (Capital One Multi-Asset Execution Trust) is a            │
│  separate issuance trust that issues notes to investors.         │
│  COMET does not hold the receivables; COMT does.                │
└──────────┬────────────────────────────────────┬─────────────────┘
           │                                    │
           │  (A) RETENTION THEORY              │  (B) REACQUISITION THEORY
           │  Receivable never leaves trust;     │  Receivable removed from COMT
           │  COMT remains owner; COBUSA         │  per § 6.01 or § 6.02
           │  collects as servicer               │  (or other operative provision)
           │                                    ▼
           │                    ┌───────────────────────────────────┐
           │                    │  REMOVAL FROM COMT                │
           │                    │                                   │
           │                    │  § 6.01 — Ineligible Receivables  │
           │                    │  Trigger: receivable no longer    │
           │                    │  meets eligibility criteria        │
           │                    │  (charge-off, write-off, other)   │
           │                    │  Verify exact eligibility criteria │
           │                    │  from PSA definition section       │
           │                    │                                   │
           │                    │  § 6.02 — Breach of Reps          │
           │                    │  Trigger: representation made at  │
           │                    │  transfer was incorrect            │
           │                    │                                   │
           │                    │  Account-level proof needed:      │
           │                    │  • Removal notice or schedule      │
           │                    │  • Identifies defendant's account  │
           │                    │  • Identifies triggering provision │
           │                    │  • Executed by proper party        │
           │                    └─────────────────┬─────────────────┘
           │                                      │
           │                                      │  REASSIGNMENT INSTRUMENT
           │                                      │  • COMT reassigns removed
           │                                      │    receivable to Capital One
           │                                      │    Funding, LLC (or COBUSA)
           │                                      │  • Account-level proof needed:
           │                                      │    executed reassignment
           │                                      │    identifying defendant's
           │                                      │    account; authentication
           │                                      ▼
           │                    ┌───────────────────────────────────┐
           │                    │  Capital One Funding, LLC         │
           │                    │  or Capital One Bank (USA), N.A. │
           │                    │  [Reacquired receivable]          │
           │                    └─────────────────┬─────────────────┘
           │                                      │
           │                                      │  BILL OF SALE / ASSIGNMENT
           │                                      │  (if sold to third-party buyer)
           │                                      │  • Executed bill of sale
           │                                      │  • Account schedule identifying
           │                                      │    defendant's account
           │                                      │  • Authentication
           │                                      ▼
           └─────────────────────►┌───────────────────────────────────┐
                                  │  Debt Buyer / Current Plaintiff    │
                                  │  (if sold after reacquisition)     │
                                  │                                   │
                                  │  If retention theory:              │
                                  │  COMT is the owner; if plaintiff   │
                                  │  is a debt buyer, a gap exists     │
                                  │  between COMT and plaintiff         │
                                  └───────────────────────────────────┘
```

---

## Link-by-Link Evidence Checklist

### Link 1: COBUSA → Capital One Funding, LLC (via RPA)

| Evidence Required | Description | Status |
|---|---|---|
| Executed RPA | Operative version covering the account's vintage | Obtain from EDGAR |
| Account schedule / supplement | Lists accounts sold; must include defendant's account number | Demand in discovery |
| Authentication | Custodian or qualified witness who can authenticate the RPA and schedule | Evaluate affidavit or testimony |
| Date coverage | Transfer must have occurred before the account became ineligible | Verify against account history |
| Originating entity | Confirm COBUSA (not CONA or Capital One Financial) is the seller | Verify from account documents |

**RSAF Note:** Confirming the correct originating bank (COBUSA vs. CONA) is critical. An assignment from the wrong entity is not a valid link in the chain.

---

### Link 2: Capital One Funding, LLC → Capital One Master Trust (via PSA)

| Evidence Required | Description | Status |
|---|---|---|
| Executed PSA (operative version) | Including all amendments and restatements | Obtain from EDGAR |
| Account schedule or collateral certificate | Shows defendant's account included in COMT | Demand in discovery |
| Authentication | Competent foundation witness | Evaluate |
| Timing | Account transferred into trust while still eligible | Verify |

**RSAF Note:** The PSA describes the program structure. A prospectus or offering document may summarize program terms. Neither is a substitute for an account-specific schedule showing this account was transferred into COMT.

---

### Link 3: Removal from Capital One Master Trust (Reacquisition Theory)

| Evidence Required | Description | Status |
|---|---|---|
| Removal notice / schedule | Account-specific document identifying this receivable as removed | Demand in discovery |
| Triggering provision | Which PSA section authorized the removal (§ 6.01 or § 6.02) | Pull from PSA |
| Triggering event | The specific condition that triggered removal (e.g., charge-off under § 6.01) | Verify from PSA and account history |
| Proper execution | Executed by the party with authority under the PSA | Verify |
| Authentication | Competent foundation witness | Evaluate |

**RSAF Note:** A charge-off or write-off entry in a servicing record is the servicer's accounting entry. It is not a removal notice from the trust. An affidavit stating the account "was removed from the trust" is not a removal document — it is a characterization requiring an underlying removal instrument.

---

### Link 4: Capital One Master Trust → Capital One Funding, LLC (Reassignment)

| Evidence Required | Description | Status |
|---|---|---|
| Executed reassignment instrument | Identifies the defendant's account as being reassigned from COMT | Demand in discovery |
| Authentication | Competent foundation witness | Evaluate |
| To whom reassigned | Confirms the chain continues to the entity that sells to the plaintiff | Verify |

---

### Link 5: Capital One Funding, LLC / COBUSA → Current Plaintiff (Bill of Sale)

| Evidence Required | Description | Status |
|---|---|---|
| Executed bill of sale | Must reference an account schedule or specifically identify this account | Demand in discovery |
| Account schedule | Lists defendant's account by account number | Demand in discovery |
| Schedule–instrument linkage | Bill of sale and schedule reference each other or are otherwise connected | Verify |
| Authentication | Witness with foundation knowledge for documents from COBUSA and CO Funding | Evaluate affidavit |

---

## Virginia LLC Distinction

Capital One Funding, LLC is a Virginia limited liability company. This is different from most ABS depositor entities, which are Delaware LLCs.

Because Capital One Funding is a Virginia entity, the UCC analysis for the RPA (Link 1 → Link 2) is governed by **Virginia UCC Article 9 (Va. Code § 8.9A-109 et seq.)**, not Delaware UCC. The relevant UCC-1 financing statement should be filed with the Virginia State Corporation Commission.

This matters for:
- **Perfection analysis:** Is the ownership interest in the receivables properly perfected under Virginia law?
- **Priority:** If there are competing claims to the same receivables, which interest is senior?
- **Account debtor's rights:** Va. Code § 8.9A-406 governs the account debtor's rights when a receivable is assigned.

**Research requirement:** Search the Virginia SCC UCC filing database for filings by or against Capital One Funding, LLC as debtor or secured party.

---

## COMT vs. COMET Distinction

**Capital One Master Trust (COMT)** is the entity that holds the credit-card receivables. It is the legally relevant entity for chain-of-title purposes.

**Capital One Multi-Asset Execution Trust (COMET)** is the issuance trust that issues notes to investors. COMET holds collateral certificates issued by COMT, not the receivables themselves.

In litigation, a plaintiff who asserts it obtained a receivable from "Capital One" must trace its chain through COMT, not COMET. A document referencing COMET does not establish ownership of receivables held in COMT.

---

## Common Deficiencies in Capital One Cases

**1. No account-specific schedule for COMT transfer.** The plaintiff produces the PSA to establish the program but does not produce an account schedule showing this account was transferred into COMT.

**2. No removal documentation.** The plaintiff asserts the account was removed from COMT after charge-off but produces only the servicer's charge-off record — not the account-specific removal notice or schedule required by PSA § 6.01.

**3. No reassignment instrument.** The plaintiff produces a bill of sale from COBUSA to the plaintiff but does not produce the instrument by which COMT first reassigned the receivable to Capital One Funding, LLC or COBUSA.

**4. Wrong originating entity.** The chain begins with "Capital One" generically, without specifying whether COBUSA or CONA originated the account. An assignment from the wrong entity is not a valid link.

**5. Bill of sale without schedule.** The plaintiff produces an executed bill of sale covering a portfolio but does not produce the schedule identifying this defendant's account as included.

**6. Confusion between COMT and COMET.** The plaintiff produces COMET offering documents as if they establish COMT ownership. COMET holds collateral certificates; the receivables sit in COMT.

**7. Servicer records as ownership proof.** The plaintiff offers COBUSA's servicer records as proof of ownership. COBUSA services accounts for COMT. The servicer's records prove servicing, not ownership. They do not establish which entity is the current owner.

---

## Research Checklist

Before completing this playbook for use in an active case, the following research must be completed:

- [ ] Pull operative PSA from EDGAR; read §§ 6.01 and 6.02 (or equivalent) in full; note section numbers and removal triggers
- [ ] Pull RPA from EDGAR; confirm parties, effective date, and transfer terms
- [ ] Pull COMT Trust Agreement from EDGAR; confirm trustee identity and role
- [ ] Pull COMET Indenture from EDGAR; confirm issuance trust terms
- [ ] Pull at least one prospectus or prospectus supplement from EDGAR; confirm program structure
- [ ] Pull at least one COMT 10-K from EDGAR; review for removal/reassignment disclosures
- [ ] Search Virginia SCC for UCC filings by or against Capital One Funding, LLC
- [ ] Confirm originating entity for specific account (COBUSA or CONA)
- [ ] Obtain and review applicable cardmember agreement for the account's vintage
- [ ] Obtain and review arbitration clause for the account's vintage
- [ ] Verify that no amendments to the PSA materially change the removal or reassignment procedure

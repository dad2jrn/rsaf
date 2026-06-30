# Bank of America — Transfer Path Analysis

**Status:** Structural draft — expected transfer path based on public SEC filings; EDGAR research required before any factual proposition can be relied upon  
**Version:** 0.2.0

---

## Purpose

This document maps the expected transfer path for Bank of America credit-card receivables through the securitization structure, identifies the governing agreement at each node, and states the account-level evidence RSAF requires to verify that a specific receivable traveled this path.

---

## Structural Transfer Diagram

```text
┌─────────────────────────────────────────────────────────────────┐
│              Bank of America, N.A.                              │
│         (or FIA Card Services, N.A. for pre-2014 accounts)     │
│                                                                 │
│  Role: Originating bank; seller; ongoing servicer               │
│  Charter: National bank; OCC-regulated                          │
│  State: Primary operations; Delaware for card agreements         │
└──────────────────────┬──────────────────────────────────────────┘
                       │
                       │  RECEIVABLES PURCHASE AGREEMENT (RPA)
                       │  • BANA sells receivables to BA Credit Card
                       │    Funding, LLC on a daily / periodic basis
                       │  • True-sale treatment: transfers bankruptcy
                       │    risk from originator to trust structure
                       │  • Account-level proof needed: account schedule
                       │    or supplement identifying defendant's account
                       ▼
┌─────────────────────────────────────────────────────────────────┐
│              BA Credit Card Funding, LLC                        │
│                                                                 │
│  Role: Bankruptcy-remote transferor / depositor                 │
│  Entity: Delaware limited liability company                     │
│  Purpose: Insulates trust from bank's insolvency                │
│  Servicer relationship: BANA retains servicing rights           │
└──────────────────────┬──────────────────────────────────────────┘
                       │
                       │  POOLING AND SERVICING AGREEMENT (PSA)
                       │  • BA Credit Card Funding, LLC transfers
                       │    receivables to BA Master Credit Card Trust II
                       │  • PSA governs: (1) initial transfer of receivables
                       │    into trust; (2) addition of new accounts;
                       │    (3) removal of ineligible receivables;
                       │    (4) reassignment upon removal;
                       │    (5) servicer duties and obligations
                       │  • Account-level proof needed: collateral
                       │    certificate or account schedule showing
                       │    defendant's account included in trust
                       ▼
┌─────────────────────────────────────────────────────────────────┐
│          BA Master Credit Card Trust II                         │
│                                                                 │
│  Role: Master trust; legal owner of receivables in pool         │
│  Entity: Delaware statutory trust                               │
│  Trustee: Bank of New York Mellon (verify for specific series)  │
│  Beneficiary: BA Credit Card Funding, LLC (as transferor)       │
│                                                                 │
│  Trust holds the receivable unless and until removed.           │
│  BANA services accounts as servicer for the trust.             │
│  Trust issues collateral certificates to BA Credit Card Trust.  │
└──────────┬───────────────────────────────────┬──────────────────┘
           │                                   │
           │  (A) RETENTION THEORY             │  (B) REACQUISITION THEORY
           │  Receivable never transferred      │  Receivable removed from trust
           │  out of trust; trust remains       │  per PSA removal provisions
           │  owner; servicer/bank collects     │
           │  on trust's behalf                 │
           │                                   ▼
           │                    ┌──────────────────────────────────┐
           │                    │  REMOVAL FROM TRUST              │
           │                    │                                  │
           │                    │  Trigger: charge-off, breach of   │
           │                    │  representations, ineligibility   │
           │                    │  (verify specific PSA provision)  │
           │                    │                                  │
           │                    │  Account-level proof needed:     │
           │                    │  • Removal notice or schedule    │
           │                    │  • Identifies defendant's account │
           │                    │  • Executed by proper party       │
           │                    │  • Consistent with PSA procedure  │
           │                    └──────────────┬───────────────────┘
           │                                   │
           │                                   │  REASSIGNMENT INSTRUMENT
           │                                   │  • Trust reassigns receivable
           │                                   │    to BA Credit Card Funding,
           │                                   │    LLC or to BANA directly
           │                                   │  • Account-level proof needed:
           │                                   │  executed reassignment identifying
           │                                   │  defendant's account or a schedule
           │                                   ▼
           │                    ┌──────────────────────────────────┐
           │                    │  BA Credit Card Funding, LLC     │
           │                    │  or Bank of America, N.A.        │
           │                    │  [Reacquired receivable]         │
           │                    └──────────────┬───────────────────┘
           │                                   │
           │                                   │  BILL OF SALE / ASSIGNMENT
           │                                   │  (if sold to debt buyer)
           │                                   │  • Account-level proof needed:
           │                                   │  • Executed bill of sale
           │                                   │  • Account schedule identifying
           │                                   │    defendant's account
           │                                   │  • Authentication
           │                                   ▼
           └──────────────────►┌──────────────────────────────────┐
                               │  Debt Buyer / Current Plaintiff   │
                               │  (if sold after reacquisition)    │
                               │                                  │
                               │  If retention theory:             │
                               │  Trust is the owner; if plaintiff │
                               │  is the debt buyer, gap exists    │
                               │  between trust and plaintiff      │
                               └──────────────────────────────────┘
```

---

## Link-by-Link Evidence Checklist

### Link 1: BANA → BA Credit Card Funding, LLC (via RPA)

| Evidence Required | Description | Status |
|---|---|---|
| Executed RPA | Must be the operative version covering the account's vintage | Obtain from EDGAR |
| Account schedule / supplement | Lists specific accounts transferred; must include defendant's account number | Demand in discovery |
| Authentication | Custodian or qualified witness who can authenticate the RPA and schedule | Evaluate affidavit or testimony |
| Date coverage | Transfer must have occurred while the account was in good standing and covered by the RPA | Verify against account history |

**RSAF Note:** A generic bill-of-sale or an affidavit asserting that accounts were sold "pursuant to the RPA" is not a substitute for an account schedule that identifies the defendant's account.

---

### Link 2: BA Credit Card Funding, LLC → BA Master Credit Card Trust II (via PSA)

| Evidence Required | Description | Status |
|---|---|---|
| Executed PSA | Must be the operative version and any applicable amendments | Obtain from EDGAR |
| Collateral certificate or account schedule | Shows defendant's account included in the master trust | Demand in discovery |
| Authentication | Competent foundation witness | Evaluate affidavit or testimony |
| Transfer timing | Transfer must have occurred before the events giving rise to the claim | Verify |

**RSAF Note:** The PSA describes the structure of the transfer. An affidavit that merely attaches the PSA and asserts that all accounts were transferred does not substitute for an account-specific schedule.

---

### Link 3: Removal from Trust (Reacquisition Theory Only)

| Evidence Required | Description | Status |
|---|---|---|
| Removal notice / schedule | Account-specific document showing this receivable was removed from the trust | Demand in discovery |
| Triggering provision | Identifies which PSA provision authorized the removal | Pull from PSA |
| Triggering event | Identifies the specific condition that triggered removal (charge-off, ineligibility, etc.) | Verify against account history |
| Proper execution | Removal document executed by party with authority under PSA | Verify |
| Authentication | Competent foundation witness | Evaluate |

**RSAF Note:** Where the plaintiff produces no removal documentation and asserts only that the account was charged off and removed, the removal is unproven. A charge-off entry in a servicing record is not removal documentation.

---

### Link 4: Trust → BA Credit Card Funding, LLC (Reassignment Instrument)

| Evidence Required | Description | Status |
|---|---|---|
| Executed reassignment instrument | PSA contemplates a formal reassignment; must identify defendant's account | Demand in discovery |
| Authentication | Competent foundation witness | Evaluate |
| To whom reassigned | Establishes who holds the receivable after reassignment | Verify chain continues to plaintiff |

---

### Link 5: BANA / BA Credit Card Funding, LLC → Current Plaintiff (Bill of Sale)

| Evidence Required | Description | Status |
|---|---|---|
| Executed bill of sale | Must identify the defendant's account or reference a schedule that does | Demand in discovery |
| Account schedule | Lists defendant's account by number | Demand in discovery |
| Authentication | Competent foundation witness employed by the plaintiff or the selling entity | Evaluate |
| Schedule–instrument linkage | Bill of sale and schedule must reference each other or be otherwise connected | Verify |

**RSAF Note:** A bill of sale that transfers "all accounts listed on Schedule A" is not account-specific proof unless Schedule A has been produced and the defendant's account number appears on it. Producing the bill of sale without Schedule A is a common deficiency.

---

## Predecessor Entity Complications

Where the account was originated by **MBNA America Bank, N.A.** or **FIA Card Services, N.A.**, the chain must account for the following:

| Event | Approximate Date | Chain-of-Title Implication |
|---|---|---|
| Bank of America acquires MBNA | January 2006 | MBNA accounts may have been transferred to FIA Card Services |
| MBNA America Bank renamed FIA Card Services, N.A. | 2006 | Account agreements may reflect MBNA branding; servicer is FIA |
| FIA Card Services, N.A. merged into Bank of America, N.A. | 2014 (verify) | FIA accounts became BANA accounts |

**RSAF Note:** If the chain of title in a specific case runs through FIA Card Services or MBNA, the plaintiff must document: (1) that FIA/MBNA was the originating entity; (2) that the trust structure predates or was updated for the corporate merger; (3) that the corporate merger or name change did not itself create a gap in the chain of title.

---

## Common Deficiencies in Bank of America Cases

Based on the structure above, the following are the most likely evidentiary gaps in Bank of America collection cases.

**1. No account-specific schedule for the trust transfer.** The plaintiff produces the PSA or a prospectus to establish the program structure but does not produce an account schedule showing this specific account was transferred into BA Master Credit Card Trust II.

**2. No removal documentation.** The plaintiff asserts the account was removed from the trust after charge-off but produces only a charge-off entry in a servicing record, not the account-specific removal notice or removal schedule called for by the PSA.

**3. Missing reassignment instrument.** The plaintiff produces a bill of sale from BANA (or a BANA affiliate) to the plaintiff but does not produce the instrument by which the trust reassigned the receivable to BANA or BA Credit Card Funding, LLC first.

**4. Predecessor entity gap (MBNA/FIA).** The plaintiff's chain begins with BANA but does not address how accounts originally originated by MBNA or FIA Card Services are now held in BANA's name.

**5. Bill of sale without schedule.** The plaintiff produces an executed bill of sale for a bulk portfolio but does not produce the account schedule identifying this defendant's account as included in the sale.

**6. Authentication by plaintiff's employee only.** The plaintiff's custodian affidavit authenticates the plaintiff's own records but does not address the foundational requirements for documents that originated with BANA, FIA Card Services, or the trust.

---

## Research Checklist

Before completing this playbook for use in an active case, the following research must be completed:

- [ ] Pull RPA from EDGAR; confirm effective date, parties, and transfer terms
- [ ] Pull PSA from EDGAR; read removal provisions (identify specific section numbers)
- [ ] Pull Trust Agreement from EDGAR; confirm trustee identity and role
- [ ] Pull at least one prospectus or prospectus supplement from EDGAR; confirm program structure
- [ ] Pull at least one Trust 10-K from EDGAR; review for servicing methodology and removal/reassignment disclosure
- [ ] Search Delaware SOS for UCC filings by BA Credit Card Funding, LLC
- [ ] Confirm merger history: FIA Card Services into BANA (verify date and regulatory filing)
- [ ] Obtain and review applicable cardmember agreement for the account's vintage
- [ ] Obtain and review arbitration clause for the account's vintage
- [ ] Verify that no amendments or restatements of the PSA materially change the transfer or removal procedures

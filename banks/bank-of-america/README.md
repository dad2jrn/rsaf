# Bank of America Playbook

**Status:** Substantive draft — based on public SEC filings; verify all citations before court use  
**Version:** 0.2.0

---

## 1. Purpose

This playbook applies RSAF to Bank of America's credit-card receivable securitization structure. It identifies the institutional participants, the governing agreements, the expected transfer path, and the account-level evidence that RSAF requires before any ownership element can be treated as established.

Nothing in this playbook is a legal conclusion. Every proposition must be verified against the primary source identified. This is a research framework, not a court-ready analysis.

---

## 2. Institutional Background

**Bank of America, N.A.** ("BANA") is the originating bank for Bank of America-branded consumer credit cards. Prior to a bank merger completed in or around 2014, the relevant predecessor entity was **FIA Card Services, N.A.**, which was itself the successor to MBNA America Bank, N.A. following Bank of America's acquisition of MBNA Corporation in 2006. Accounts originated under MBNA or FIA Card Services branding may have Bank of America, N.A. as the current servicer.

**FIA Card Services, N.A.** The identity of the originating entity is material to chain-of-title analysis. If a plaintiff traces its title through an assignment from "FIA Card Services" rather than "Bank of America," the relationship between these entities must appear in the chain. RSAF must identify the originating entity for any specific account before evaluating chain of title.

**Research requirement:** Confirm the name and charter of the originating bank for any specific account at issue.

---

## 3. Securitization Structure

Bank of America's consumer credit-card receivable securitization program uses a two-tier trust structure. The structure described below is based on publicly available SEC filings; verify current structure for any specific transaction.

### 3.1 Participants and Roles

| Participant | Role | Notes |
|---|---|---|
| Bank of America, N.A. (or FIA Card Services, N.A.) | Originating bank; seller; servicer | Services accounts after securitization |
| BA Credit Card Funding, LLC | Bankruptcy-remote transferor / depositor; Delaware LLC | Intermediate entity; sells receivables to trust |
| BA Master Credit Card Trust II | Master trust; holds receivables | Delaware statutory trust; governed by PSA |
| BA Credit Card Trust | Issuance trust; issues notes to investors | Wilmington Trust Company as owner trustee (verify) |
| BNY Mellon (Bank of New York Mellon) | Indenture trustee; master trust trustee | Verify role and entity name for each specific series |
| Investors | Holders of ABS notes | No role in collection action; trust is the entity |

### 3.2 Governing Agreements

The following agreements are expected to govern the program. They are public documents available on EDGAR. Verify the exact name, filing date, and operative version for any specific series.

- **Receivables Purchase Agreement (RPA):** Governs the initial sale of receivables from Bank of America, N.A. (or FIA Card Services, N.A.) to BA Credit Card Funding, LLC.
- **Pooling and Servicing Agreement (PSA):** Governs the transfer of receivables from BA Credit Card Funding, LLC to BA Master Credit Card Trust II, the terms of servicing, and the procedures for removal and reassignment.
- **Indenture:** Governs the issuance of notes by BA Credit Card Trust.
- **Trust Agreement:** Governs the formation and administration of the master trust and issuance trust.

**Research requirement:** Pull the current RPA, PSA, and Trust Agreement from EDGAR. Identify the effective date, all amendments and restatements, and the specific provisions governing (1) transfer of receivables into the trust, (2) removal of receivables from the trust, and (3) reassignment of removed receivables.

### 3.3 Program Activity

Bank of America's credit card trust program was active through at least 2022, when approximately $2.3 billion in new securities was reported. Verify the program's current status and whether new securitizations are being issued before analyzing a specific transaction.

---

## 4. Transfer Path

See `transfer-path.md` for the full structural diagram with governing document references at each node.

The general structure is:

```text
Bank of America, N.A.
(or FIA Card Services, N.A.)
[Originating bank / seller / servicer]
        │
        │ Receivables Purchase Agreement
        │ (BANA sells receivables to transferor)
        ▼
BA Credit Card Funding, LLC
[Bankruptcy-remote transferor / depositor]
        │
        │ Pooling and Servicing Agreement
        │ (Transferor conveys receivables to master trust)
        ▼
BA Master Credit Card Trust II
[Master trust — holds pool of receivables]
        │
        │ PSA removal provisions
        │ (§ to be verified — governs ineligible receivable removal)
        ▼
BA Credit Card Funding, LLC (upon removal)
        │
        │ Reassignment instrument
        │ (Trust reassigns specific receivable to transferor or bank)
        ▼
Bank of America, N.A. or
BA Credit Card Funding, LLC
[Reacquired receivable]
        │
        │ Bill of Sale or Assignment Agreement
        │ (If sold to debt buyer)
        ▼
Debt Buyer / Current Plaintiff
```

---

## 5. RSAF Structural Questions

Before any account-specific analysis, RSAF must establish that the structural chain is supported by public documents.

| Question | Source | Status |
|---|---|---|
| Does the RPA exist and is it authenticated? | EDGAR | Research required |
| Does the PSA exist and is it authenticated? | EDGAR | Research required |
| What provisions of the PSA govern removal of receivables? | PSA text | Research required |
| What constitutes an "ineligible receivable" triggering removal? | PSA text | Research required |
| What procedures does the PSA require for removal? | PSA text | Research required |
| Does removal require trustee notice or approval? | PSA text | Research required |
| What document evidences reassignment after removal? | PSA text | Research required |
| Is there a retention theory or only a reacquisition theory? | PSA text | Research required |
| Under what circumstances does the originating bank retain title? | RPA/PSA | Research required |

---

## 6. Account-Level Proof Required

The structural chain described in Section 3 and 4 is program-level evidence. It establishes how transfers are designed to work. It does not prove that the defendant's receivable was transferred.

For each account, RSAF requires:

### Link 1: BANA to BA Credit Card Funding, LLC
- Executed RPA identifying this receivable or an account schedule that includes this account
- Authentication of the RPA and schedule
- Evidence that the transfer was made during the period the RPA was operative

### Link 2: BA Credit Card Funding, LLC to BA Master Credit Card Trust II
- Executed PSA (or relevant amendment/supplement) covering this account
- Account schedule or collateral certificate identifying the defendant's account as included in the trust
- Authentication

### Link 3: Removal from Trust (reacquisition theory)
- Account-specific removal notice or removal schedule identifying the defendant's receivable
- Evidence of the triggering condition (ineligibility, default, charge-off, etc.)
- Executed by the proper party with authority
- Authentication

### Link 4: Reassignment to BANA or BA Credit Card Funding, LLC
- Executed reassignment instrument identifying the defendant's account
- Authentication

### Link 5: Sale to Plaintiff (if plaintiff is a debt buyer)
- Executed assignment or bill of sale identifying the defendant's account
- Account schedule including the defendant's account number
- Authentication

**RSAF Rule:** Absence of account-level documentation for any link is an evidentiary gap. RSAF states the gap. RSAF does not infer that the transfer occurred because the program is designed to accommodate it.

---

## 7. Predecessor Entity Chain (MBNA / FIA Card Services)

Where the account was originated by MBNA America Bank, N.A. or FIA Card Services, N.A., the chain must account for corporate succession as well as receivable transfer.

**Research requirement:** Identify whether the chain of title in any specific case runs through MBNA or FIA Card Services, and whether there are intervening corporate mergers or name changes that must be documented in the chain.

---

## 8. Arbitration

Bank of America cardmember agreements have historically included arbitration clauses. Where applicable, the arbitration agreement may designate a specific administrator (commonly the American Arbitration Association). The Federal Arbitration Act governs enforceability.

**Research requirement:** Obtain the applicable cardmember agreement and arbitration agreement for the vintage of the account. Arbitration agreement language changes over time.

---

## 9. Required EDGAR Research

To complete this playbook, the following EDGAR research is required:

| Document | Search Term | Purpose |
|---|---|---|
| RPA | BA Credit Card Funding LLC | Governing sale terms |
| PSA | BA Master Credit Card Trust II | Removal/reassignment provisions |
| Trust Agreement | BA Credit Card Trust | Issuance trust terms |
| Prospectus (base) | BA Credit Card Trust | Program overview |
| Prospectus Supplement | BA Credit Card Trust | Series-specific terms |
| 10-K (Trust) | BA Master Credit Card Trust II | Annual report; servicing data |
| 8-K filings | BA Master Credit Card Trust II | Removal notices, amendments |
| UCC filings | Secretary of State — Delaware | BA Credit Card Funding LLC UCC-1 |

All EDGAR searches should be run at sec.gov/cgi-bin/browse-edgar with the entity name and form type.

---

## 10. Applicable Law

| Issue | Governing Law | Notes |
|---|---|---|
| Receivable transfer and perfection | Virginia UCC § 8.9A or Delaware UCC § 9-109 (depends on trust state) | Delaware law likely controls the PSA |
| Trust formation | Delaware Statutory Trust Act; Delaware ABSFA (6 Del. C. Ch. 27A) | Verify trust formation documents |
| Cardmember agreement terms | Typically Delaware (choice-of-law clause in agreement) | Verify applicable agreement |
| Litigation procedure (Virginia) | Virginia Rules of Court; Virginia Rules of Evidence | Virginia GDC or Circuit Court |
| Business records | Va. Rules Evid. Rule 2:803(6) | Virginia forum |
| Arbitration enforceability | Federal Arbitration Act, 9 U.S.C. § 2 | If arbitration clause applies |

---

## 11. Research Status

| Area | Status | Priority |
|---|---|---|
| Structural chain (EDGAR) | Not yet pulled | High |
| RPA provisions | Not yet reviewed | High |
| PSA removal/reassignment provisions | Not yet reviewed | High |
| Cardmember agreement language | Not yet reviewed | High |
| Arbitration agreement language | Not yet reviewed | Medium |
| UCC filings (Delaware SOS) | Not yet reviewed | Medium |
| Trust 10-K filings | Not yet reviewed | Medium |
| Predecessor entity analysis (MBNA/FIA) | Not yet reviewed | As needed |

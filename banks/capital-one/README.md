# Capital One Playbook

**Status:** Structural draft — expected program structure based on public SEC filings; EDGAR research required before any factual proposition can be relied upon  
**Version:** 0.2.0

---

## 1. Purpose

This playbook applies RSAF to Capital One's credit-card receivable securitization structure. It identifies the institutional participants, the governing agreements, the expected transfer path, and the account-level evidence that RSAF requires before any ownership element can be treated as established.

Nothing in this playbook is a legal conclusion. Every proposition must be verified against the primary source identified. This is a research framework, not a court-ready analysis.

---

## 2. Institutional Background

**Capital One Bank (USA), N.A.** ("COBUSA") is the primary originating bank for Capital One consumer credit cards. Capital One, N.A. ("CONA") also originates accounts; the distinction matters because it determines which entity is the seller and servicer on any specific account. Verify the originating bank for each specific account.

Capital One Financial Corporation is the publicly held parent. It is not a party to the securitization transfer documents and is not the originating bank; it does not itself hold or transfer credit-card receivables.

**EDGAR filing entity:** Publicly available securitization documents can be found by searching for "Capital One Funding LLC" and "Capital One Master Trust" at sec.gov.

---

## 3. Securitization Structure

Capital One's consumer credit-card receivable securitization program uses a two-tier trust structure: a master trust that holds the receivable pool, and an issuance trust that issues notes to investors. The structure described below is based on publicly available SEC filings; verify current structure and specific governing document provisions for any specific transaction.

### 3.1 Participants and Roles

| Participant | Role | Notes |
|---|---|---|
| Capital One Bank (USA), N.A. | Originating bank; seller; servicer | Services accounts post-securitization |
| Capital One Funding, LLC | Bankruptcy-remote transferor / depositor; Virginia LLC | Sells receivables to master trust; holds beneficiary interest |
| Capital One Master Trust (COMT) | Master trust; holds receivables | Statutory trust; pool-level entity |
| Capital One Multi-Asset Execution Trust (COMET) | Issuance trust; issues notes to investors | Separate trust; uses master trust collateral certificates |
| Bank of New York Mellon (BNY Mellon) | Indenture trustee; owner trustee | Verify specific role and entity name for each series |
| Investors | Holders of ABS notes issued by COMET | No role in collection action |

### 3.2 Governing Agreements

The following agreements are expected to govern the program. Verify the exact name, filing date, and operative version on EDGAR.

- **Receivables Purchase Agreement (RPA):** Governs the sale of receivables from Capital One Bank (USA), N.A. to Capital One Funding, LLC.
- **Transfer and Servicing Agreement (TSA) / Amended and Restated Pooling and Servicing Agreement (PSA):** Governs the transfer of receivables from Capital One Funding, LLC to Capital One Master Trust, the terms of servicing, and procedures for removal and reassignment of receivables. Capital One's program uses a pooling and servicing agreement structure; the governing document may be titled differently across vintages. Verify the operative agreement name.
- **Indenture:** Governs the issuance of notes by Capital One Multi-Asset Execution Trust (COMET).
- **Trust Agreement / Owner Trust Agreement:** Governs the formation and administration of COMT and COMET.

**PSA removal provisions:** The Amended and Restated PSA (or equivalent governing document) contains the provisions under which receivables may be removed from the master trust. Based on public filings, the removal provisions include:

- **§ 6.01 (Ineligible Receivables):** Addresses removal of receivables that become ineligible under the program's eligibility criteria. Verify exact provision text from the operative PSA.
- **§ 6.02 (Breach of Representations):** Addresses removal of receivables where a representation or warranty made at transfer was breached. Verify exact provision text from the operative PSA.

**Research requirement:** Pull the current operative PSA from EDGAR. Read §§ 6.01 and 6.02 (or equivalent provisions in the operative agreement) in full. Confirm section numbers, removal triggers, required documentation, and who has authority to execute the removal.

---

## 4. Transfer Path

See `transfer-path.md` for the full structural diagram with governing document references at each node.

The general structure is:

```text
Capital One Bank (USA), N.A.
[Originating bank / seller / servicer]
        │
        │  Receivables Purchase Agreement
        │  (COBUSA sells receivables to CO Funding, LLC)
        ▼
Capital One Funding, LLC
[Bankruptcy-remote transferor / depositor; Virginia LLC]
        │
        │  PSA / Transfer and Servicing Agreement
        │  (CO Funding conveys receivables to master trust)
        ▼
Capital One Master Trust (COMT)
[Master trust — holds pool of receivables]
        │
        │  PSA removal provisions (§ 6.01 / § 6.02 or equivalent)
        │  (Removal triggered by ineligibility or breach of representations)
        ▼
Capital One Funding, LLC (upon removal)
        │
        │  Reassignment instrument
        │  (Trust reassigns specific receivable to Funding LLC)
        ▼
Capital One Funding, LLC or COBUSA
[Reacquired receivable]
        │
        │  Bill of Sale / Assignment Agreement
        │  (If sold to third-party debt buyer)
        ▼
Debt Buyer / Current Plaintiff
```

---

## 5. RSAF Structural Questions

| Question | Source | Status |
|---|---|---|
| Does the RPA exist and is it authenticated? | EDGAR | Research required |
| Does the operative PSA exist and is it authenticated? | EDGAR | Research required |
| What provisions govern removal of receivables? | PSA §§ 6.01/6.02 (verify) | Research required |
| What constitutes an "ineligible receivable"? | PSA definition section | Research required |
| What procedures does the PSA require for removal? | PSA text | Research required |
| Does removal require a specific notice or schedule? | PSA text | Research required |
| What document evidences reassignment after removal? | PSA text | Research required |
| To whom does the trust reassign a removed receivable? | PSA text | Research required |
| Is there a retention theory available, or only reacquisition? | RPA/PSA | Research required |
| What is the effective date of the operative PSA? | PSA | Research required |
| Has the PSA been amended in ways that affect removal? | EDGAR 8-Ks | Research required |

---

## 6. Account-Level Proof Required

The structural chain described above is program-level evidence. It establishes how transfers are designed to work. It does not prove that the defendant's receivable was transferred.

For each account, RSAF requires:

### Link 1: COBUSA → Capital One Funding, LLC (via RPA)
- Executed RPA covering the account's vintage
- Account schedule or supplement identifying the defendant's account as included in the sale
- Authentication by a competent foundation witness
- Evidence that the transfer occurred before the events giving rise to the claim

### Link 2: Capital One Funding, LLC → Capital One Master Trust (via PSA)
- Executed PSA (or operative version with amendments) covering this account's addition to the trust
- Account schedule or collateral certificate identifying the defendant's account as in the trust pool
- Authentication
- Evidence of timing: account must have been added to the trust while eligible

### Link 3: Removal from Capital One Master Trust (Reacquisition Theory)
- Account-specific removal notice or removal schedule identifying the defendant's receivable
- Evidence of the triggering condition (ineligibility under § 6.01, breach of representations under § 6.02, or other — verify)
- Execution by the party with authority under the PSA
- Authentication

### Link 4: Reassignment to Capital One Funding, LLC
- Executed reassignment instrument identifying the defendant's account
- Authentication
- Evidence that the reassignment ran to the entity whose chain reaches the plaintiff

### Link 5: Sale to Current Plaintiff (if plaintiff is a debt buyer)
- Executed bill of sale or assignment identifying the defendant's account
- Account schedule including the defendant's account number
- Authentication by a witness who can establish foundation for documents originating with Capital One

**RSAF Rule:** Capital One's case is typically that a charged-off account was removed from COMT under the PSA, reassigned to Capital One Funding, LLC or COBUSA, and then sold to a debt buyer. Each of those steps requires documentary evidence. An affidavit that asserts ownership without the underlying transfer documents is not a substitute for the chain.

---

## 7. Capital One and Arbitration

Capital One cardmember agreements have historically included arbitration clauses. Capital One has actively pursued arbitration as a collection vehicle (through the American Arbitration Association under its Consumer Arbitration Rules). The Federal Arbitration Act governs enforceability.

In arbitration proceedings, the formal rules of evidence do not apply with the same force. An arbitrator has broad discretion to admit evidence. However, chain-of-title deficiencies remain relevant to ownership as a merits element — whether the matter proceeds in court or in arbitration, the plaintiff must prove it owns the receivable.

**Research requirement:** Obtain the applicable cardmember agreement and arbitration clause for the vintage of the account. Capital One's arbitration clause has been revised over time; older accounts may reflect different terms.

---

## 8. Servicing After Securitization

Capital One Bank (USA), N.A. continues to service accounts after they have been transferred to Capital One Master Trust. This means:

- COBUSA's records (account statements, payment history, default dates) are servicer records, generated on behalf of the trust.
- A COBUSA records custodian can authenticate COBUSA's own servicing records.
- A COBUSA records custodian cannot by that fact alone authenticate that COMT transferred a specific receivable to Capital One Funding, LLC or to a debt buyer. Ownership transfer is a separate event from servicing.
- The servicer is not the owner. Proof of servicing is not proof of ownership.

---

## 9. Required EDGAR Research

| Document | Search Term | Purpose |
|---|---|---|
| RPA | Capital One Funding LLC | Sale terms; account eligibility |
| PSA / TSA | Capital One Master Trust | Removal and reassignment provisions (§§ 6.01, 6.02) |
| Trust Agreement | Capital One Master Trust | Master trust formation; trustee role |
| Indenture | Capital One Multi-Asset Execution Trust | COMET note issuance |
| Prospectus (base) | Capital One Master Trust | Program overview |
| Prospectus Supplement | COMET | Series-specific terms |
| 10-K (Trust) | Capital One Master Trust | Annual report; pool data |
| 8-K filings | Capital One Master Trust | Amendments, removal notices |
| UCC filings | Virginia SOS | Capital One Funding LLC UCC-1 (Virginia) |

Capital One Funding, LLC is a Virginia LLC. UCC financing statements perfecting the interest in the receivables may be filed with the Virginia State Corporation Commission or the Virginia SCC's UCC filing office.

---

## 10. Applicable Law

| Issue | Governing Law | Notes |
|---|---|---|
| Receivable transfer and perfection | Virginia UCC § 8.9A (CO Funding is a Virginia LLC) | Sale of accounts; perfection by UCC filing |
| Trust formation | Virginia or Delaware statutory trust law | Verify COMT formation documents |
| Cardmember agreement terms | Virginia (Capital One's headquarters; may also use Virginia choice-of-law) | Verify applicable agreement |
| Litigation procedure (Virginia) | Virginia Rules of Court; Virginia Rules of Evidence | Virginia GDC or Circuit Court |
| Business records | Va. Rules Evid. Rule 2:803(6) | Virginia forum |
| Arbitration enforceability | Federal Arbitration Act, 9 U.S.C. § 2 | If arbitration clause applies |
| FDCPA classification | 15 U.S.C. § 1692 et seq. | Whether plaintiff is a debt collector |

**Virginia LLC note:** Because Capital One Funding, LLC is a Virginia entity, Virginia UCC Article 9 (§ 8.9A-109 et seq.) governs the perfection analysis for the sale of receivables from Capital One Funding, LLC to Capital One Master Trust. This may distinguish the Capital One structure from structures where the depositor is a Delaware LLC (Delaware UCC would apply).

---

## 11. Research Status

| Area | Status | Priority |
|---|---|---|
| Operative PSA from EDGAR (incl. § 6.01/6.02) | Not yet pulled | High |
| RPA from EDGAR | Not yet pulled | High |
| Trust Agreement (COMT / COMET) | Not yet pulled | High |
| Cardmember agreement (applicable vintage) | Not yet pulled | High |
| Arbitration clause (applicable vintage) | Not yet pulled | Medium |
| Virginia SCC UCC filings | Not yet reviewed | Medium |
| Trust 10-K filings | Not yet reviewed | Medium |
| COMET prospectus supplement (any recent series) | Not yet pulled | Medium |

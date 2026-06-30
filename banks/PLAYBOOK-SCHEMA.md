# Bank Playbook Schema

This document defines the required structure and content for a complete RSAF bank playbook. A playbook is not complete until every section below has been populated from verified public sources. Research stubs that have not reached this standard must be clearly labeled as such.

A playbook is a research framework, not an advocacy file. It documents what is known about a bank's program from verified public sources. It does not presume any litigation outcome. Its purpose is to enable accurate application of the generic RSAF methodology to cases involving a specific originating bank.

---

## Required Sections

### 1. Header

```
# [Bank Name] Playbook

**Status:** [Research stub | Structural draft | Substantive draft | Verified]
**Originating entity:** [Full legal name of the issuing bank, with note if research is needed to confirm]
**Last EDGAR review:** [Date of most recent EDGAR search used in this playbook]
```

---

### 2. Purpose Statement

One paragraph explaining what this playbook does and does not do. Must include:

- That the playbook is a research framework, not an advocacy file.
- That it does not presume any outcome about any specific receivable.
- That conclusions in the playbook are limited to what verified public sources establish.

---

### 3. Entities

A table or list identifying every participant in the bank's securitization program, with:

- Full legal name.
- Jurisdiction of organization or charter.
- Role in the securitization structure.
- Relationship to the originating bank (subsidiary, affiliate, independent trustee, etc.).
- Source document confirming identity and role.

Minimum entities to identify (where applicable):

- Originating bank (issuer and account owner).
- Depositor or transferor entity (bankruptcy-remote LLC or similar).
- Issuing trust (master trust, issuance trust, or both).
- Servicer (may be the originating bank itself).
- Owner trustee.
- Indenture trustee (if applicable).
- Any intermediate purchaser or assignee.

---

### 4. Program Structure

Narrative description of the securitization program, including:

- Type of trust (master trust, issuance trust, series trust, or combination).
- Whether the program issues notes, certificates, or both.
- Any material distinctions between series or vintages that affect the transfer path or documentation requirements.
- Whether the program has been wound down, modified, or replaced.

Source citations required for each material statement.

---

### 5. Transfer Mechanics

A step-by-step description of how receivables move through the securitization structure, including:

- The transfer from the originating bank to the depositor (governed by the Receivables Purchase Agreement or equivalent).
- The transfer from the depositor to the trust (governed by the Transfer and Servicing Agreement or Pooling and Servicing Agreement).
- The documents generated at each step: what must be executed, what schedules must be prepared, what records must be maintained.
- Whether transfers occur daily, monthly, or on another schedule.
- The regulatory and contractual basis for each step.

A transfer-path diagram is encouraged but not required if the narrative is sufficiently precise.

---

### 6. Servicing and Collection Authority

Description of the servicer's authority under the governing agreements, including:

- Who serves as servicer (often the originating bank).
- What the servicer is authorized to do on behalf of the trust.
- Whether the servicer may commence collection litigation in its own name, or only in the trust's name.
- Whether a specific provision authorizes the servicer to sue; if so, cite it.
- Whether the servicing agreement has been amended in ways that affect litigation authority.

---

### 7. Default, Removal, Repurchase, and Reassignment Mechanics

Description of what happens to a receivable after default or charge-off, including:

- The events that trigger removal from the trust (e.g., charge-off, breach of eligibility representations, ineligibility).
- The governing agreement provision(s) that authorize removal.
- The documentation the governing agreement requires to effect removal (notice, schedule, trustee certification, etc.).
- Where removed receivables go (returned to the bank, to the depositor, or to a third party).
- The reassignment procedure and the documents it generates.
- Any repurchase obligation triggered by breach of representations.
- Whether a charged-off receivable that is not formally removed remains in the trust.

This section determines what account-level evidence a plaintiff must produce if it is asserting a reacquisition theory.

---

### 8. Governing-Law Provisions

For each governing agreement, identify:

- The choice-of-law provision and which law it selects.
- Whether the choice-of-law applies to interpretation, enforcement, or both.
- Any provisions that may affect the Virginia or Delaware analysis.

---

### 9. Public Source Documents

A table or list of each key document reviewed, including:

| Document | EDGAR Filing | Form Type | Date | CIK | Notes |
|---|---|---|---|---|---|
| Receivables Purchase Agreement | [link or identifier] | [form type] | [date] | [CIK] | [amendment history, if any] |
| Transfer and Servicing Agreement | | | | | |
| Trust Agreement | | | | | |
| Indenture | | | | | |
| Prospectus (representative series) | | | | | |
| Annual trust 10-K | | | | | |
| UCC financing statement(s) | | | | | |
| Cardmember agreement (representative) | | | | | |

---

### 10. Unresolved Factual Questions

A list of questions that cannot yet be answered from available public documents, including:

- Any program element not yet confirmed from EDGAR.
- Any governing agreement that has not been located or reviewed.
- Any aspect of the transfer path or removal mechanics that the reviewed documents do not clearly address.
- Any amendment history that may have changed material provisions.

This section is not a deficiency — it is honest documentation of the current research state. It prevents the playbook from being applied to questions it cannot yet answer.

---

### 11. Case-Specific Evidence Required

A list of account-level documents that must be produced in any specific case to establish the plaintiff's asserted enforcement theory. This list is derived from the governing agreements, not assumed.

Minimum categories (adjust based on governing agreements):

- Account-specific transfer record (assignment or bill of sale with schedule identifying the account).
- Evidence of account eligibility at the time of transfer (or evidence of exclusion, if retention is asserted).
- Removal notice or removal schedule identifying this receivable (if reacquisition theory).
- Executed reassignment instrument identifying this receivable (if reacquisition theory).
- Servicing authority documentation (if servicer theory).
- Authentication and business-records foundation for each document.

---

## Stub vs. Substantive Distinction

A **research stub** contains the header, the purpose statement, a list of required public documents to locate, and a generic transfer-path template. It does not contain verified program-specific content. The stub makes clear that EDGAR research is required before it can be used.

A **structural draft** identifies the expected program structure — participants, agreement names, trust hierarchy, and transfer path — based on general knowledge of publicly available programs and prior research, but has not confirmed those details against the primary governing documents obtained from EDGAR. A structural draft is more detailed than a research stub but does not carry the evidentiary weight of a substantive draft. It is useful as a research starting point but must not be used as authority for factual propositions about a specific program's structure.

A **substantive draft** has completed sections 1 through 11, with each material statement supported by a citation to a verified public source. It may still have open items in section 10, but those items are identified and bounded.

A **verified playbook** has no material unresolved items in section 10, and every statement in sections 3 through 8 has been confirmed against the primary governing document.

Only **substantive drafts** and **verified playbooks** should be used to supplement a case analysis. A structural draft identifies the expected structure but requires EDGAR research before any factual proposition can be relied upon. Research stubs identify what research is needed; they do not supply the research.

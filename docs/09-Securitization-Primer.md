# 09 — Securitization Primer

## 9.1 Purpose

This chapter explains credit-card receivable securitization in plain English. The intended reader is a judge or other decision-maker who may have limited familiarity with asset-backed securities, bankruptcy-remote entities, or the mechanics of receivable transfers.

RSAF requires this foundation because many standing disputes in consumer credit-card litigation cannot be understood without understanding the basic securitization structure. The question of who owns a receivable depends on how receivables are transferred and what documents record those transfers. This chapter provides the foundation.

---

## 9.2 What Is a Receivable?

A receivable is a right to payment. In a credit-card context, it is the specific right to receive payment of charges, interest, fees, and other amounts that a cardholder has incurred and not yet paid.

When a consumer uses a credit card to make a purchase, the issuing bank advances the funds and the consumer incurs an obligation to repay. That obligation — the right of the bank to be repaid — is the receivable.

Receivables are property. They can be sold, assigned, pledged, or transferred, just as other property interests can be.

---

## 9.3 The Account Is Not the Receivable

RSAF draws a consistent distinction between the credit-card account and the receivable.

The **account** is the credit relationship — the agreement between the issuing bank and the cardholder, the credit limit, the terms governing use, and the administrative relationship that produces monthly statements, payment processing, and customer service.

The **receivable** is the right to payment that arises from charges made on the account. A bank may maintain the account relationship — continuing to service the account, send statements, and receive payments — while the right to receive payment has been transferred to another entity.

This distinction matters because it means that the entity appearing in account records, generating statements, and receiving payments may not be the entity that currently owns the right to enforce the payment obligation. The servicer and the owner may be different parties.

---

## 9.4 Why Banks Securitize Receivables

Banks that issue credit cards generate large volumes of receivables. Holding all of those receivables on the bank's own balance sheet requires capital and carries risk. Securitization is a method of transferring receivables to investors in exchange for immediate funding.

In a securitization transaction, the bank sells pools of receivables to a special-purpose entity that issues securities backed by the cash flows those receivables are expected to generate. Investors purchase the securities and receive principal and interest payments funded by the receivable collections. The bank receives cash upfront and removes the receivables from its balance sheet.

Credit-card securitization programs are typically structured as "master trust" or "issuance trust" programs, in which new receivables are continuously added to a trust as old ones are paid off, and multiple series of securities can be issued from the same trust over time.

---

## 9.5 The Participants

**Originating Bank.** The bank that issues the credit card, extends credit to the cardholder, and generates the receivables. The originating bank is typically also the initial servicer.

**Bankruptcy-Remote Transferor.** A special-purpose entity, commonly a limited liability company, formed by the originating bank. The bank transfers receivables to the transferor, typically through a Receivables Purchase Agreement. The transferor is structured to be bankruptcy-remote — that is, its assets are intended to remain outside the reach of the bank's creditors in a bank bankruptcy.

**Issuing Trust.** A special-purpose entity formed to hold the transferred receivables and issue securities to investors. The trust receives receivables from the transferor through a Transfer and Servicing Agreement. Investors hold beneficial interests in the trust or notes issued by it.

**Servicer.** The entity that administers the credit-card accounts, sends monthly statements, processes payments, maintains records, and charges off delinquent accounts. Often the originating bank serves as servicer even after transferring receivables to the trust. Servicing is a contractual relationship; the servicer does not own the receivables it services unless the governing documents provide otherwise.

**Owner Trustee.** The trustee that holds legal title to the trust assets on behalf of the trust beneficiaries. The owner trustee typically acts on instruction and does not independently manage the trust assets.

**Indenture Trustee.** Where the trust issues notes rather than certificates, an indenture trustee serves as the note trustee under an indenture, holding the trust's obligations to noteholders.

**Investors.** Purchasers of securities issued by the trust. Investors hold beneficial interests in the trust's receivable cash flows. They do not hold title to individual receivables.

---

## 9.6 The Typical Transfer Path

```text
Cardholder uses credit card
            │
            ▼
Receivable created (right to payment arises)
            │
            ▼
Originating Bank
(holds receivable initially)
            │
            │ Receivables Purchase Agreement (RPA)
            ▼
Bankruptcy-Remote Transferor LLC
(purchases receivables from the bank)
            │
            │ Transfer and Servicing Agreement (TSA)
            ▼
Issuing Trust
(holds receivables; issues securities to investors)
            │
            │ Default, charge-off, or removal event
            ▼
Removal from Trust
(receivable removed per governing agreement procedures)
            │
            │ Reassignment mechanics per governing agreements
            ▼
Transferor or Originating Bank
(receives reassigned receivable)
            │
            ▼
Plaintiff, if reacquired or if receivable was never transferred
```

This diagram represents a typical structure. The specific path depends on the governing agreements for each securitization program.

---

## 9.7 The True Sale Requirement

For accounting and legal purposes, the transfers in a securitization structure must typically qualify as "true sales" — transfers that convey ownership of the receivables, not merely pledges of them as collateral.

If a transfer is a true sale, the transferred receivables belong to the transferee and generally cannot be reclaimed by the transferor's creditors in bankruptcy. If the transfer is a secured loan rather than a true sale, the receivables remain assets of the transferor and may be reachable in bankruptcy.

Whether a transfer qualifies as a true sale depends on the substance of the transaction, not just its label. Courts and accounting standards apply criteria examining risk transfer, control, and the economic reality of the transaction.

RSAF does not assume that a transfer labeled a "sale" in the governing documents is legally a true sale. However, RSAF also does not assume the opposite. Where true-sale treatment is relevant to the analysis, RSAF notes the issue and identifies the governing documents and applicable law.

---

## 9.8 How Servicing Works

After receivables are transferred to the trust, the originating bank typically continues to service the accounts under a servicing agreement. The servicer:

- sends monthly statements to cardholders;
- processes payments;
- maintains account records;
- charges off accounts that become delinquent beyond a specified period;
- communicates with cardholders and collection agencies;
- remits collected amounts to the trust.

These servicing functions do not confer ownership on the servicer. The servicer acts on behalf of the trust, which holds the beneficial interests in the receivables. A consumer who receives statements from a bank and makes payments to that bank may be dealing with the bank in its capacity as servicer — not as owner of the receivable.

---

## 9.9 What Happens After Default and Charge-Off

When a cardholder fails to make required payments, the account typically progresses through delinquency stages before the servicer charges off the balance. Charge-off is an accounting event: the bank removes the balance from its income-producing asset books and records a loss. Charge-off does not extinguish the debt or the receivable.

After charge-off, the governing agreements typically govern what happens next. Many securitization programs require that charged-off receivables be removed from the trust through a specified procedure. The removal documentation may include removal notices, account schedules, and executed reassignment instruments.

Where charged-off receivables are removed from the trust, they may be reassigned to the transferor, the originating bank, or a third-party purchaser. The governing agreements specify who receives the reassigned receivable and what documentation is required.

If the originating bank later sues to collect a charged-off receivable, the question RSAF must examine is: where did this receivable go after charge-off, and by what documented path did the plaintiff acquire the right to collect it?

---

## 9.10 Two Theories of Ownership

In consumer credit-card collection litigation involving securitized receivables, a plaintiff typically relies on one of two theories to establish its present right to enforce the receivable.

**Theory A: The receivable was never transferred.** Under this theory, the plaintiff contends that the specific receivable was excluded from, retained out of, or otherwise never transferred into the securitization structure. If true, the plaintiff holds the receivable as originator throughout. This theory requires account-specific evidence showing that this particular receivable was retained.

**Theory B: The receivable was transferred and later reacquired.** Under this theory, the receivable was transferred to the trust but was subsequently removed and returned to the bank or its successor through the reassignment procedures in the governing agreements. This theory requires documentation of the complete chain: transfer into the trust, removal from the trust, and any subsequent transfer to the current plaintiff.

Which theory the plaintiff advances matters because the required proof is different. RSAF must identify the plaintiff's theory and evaluate whether the plaintiff has produced the evidence required to support it.

---

## 9.11 Why Account-Specific Evidence Is Required

The securitization structure creates a documentary trail. At each step in the transfer path, the governing agreements contemplate the creation of specific records: the RPA requires certain documentation for each transfer; the TSA or PSA requires similar documentation; removal and reassignment procedures generate their own records.

If those records were created, they should be producible. If the plaintiff cannot produce them, the question is why. The absence of account-specific documentation on a required element does not prove the transfer did not occur, but it does mean the plaintiff has not satisfied its burden of proving that it did.

Program-level documents establish what records the governing agreements require. The evidentiary record reveals whether those records have been produced. The gap between the two is the analysis.

---

## 9.12 The Judge's Summary

This section provides a concise, non-technical explanation for a judge with limited securitization background.

A credit-card receivable is the bank's right to be repaid for money advanced to a consumer. Banks often sell pools of these rights — receivables — to investors through a process called securitization. In a securitization, the receivables are transferred from the originating bank to a series of entities — often a special-purpose company and then a trust — and the trust issues securities to investors.

The bank typically continues to manage the accounts as servicer, sending statements and collecting payments, even though the right to receive those payments belongs to the trust (and ultimately its investors).

When a bank or related entity later sues to collect a defaulted credit-card balance, the question arises: does the plaintiff still own the right to receive payment, or was that right transferred to a trust? If transferred, was it returned before the lawsuit was filed?

Monthly statements show that an account existed. They do not necessarily show who currently owns the right to collect the balance. That ownership question is answered by the documents that record the transfer path — and the absence of such documents is an evidentiary gap on the standing element.

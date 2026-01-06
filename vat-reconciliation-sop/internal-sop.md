# 📑 Internal SOP: Monthly VAT Reconciliation Process (EU)

**Classification:** Internal / Highly Confidential  
**Owner:** Finance & Compliance Team  
**Review Cycle:** Quarterly  

---

## 1. Overview
This Standard Operating Procedure (SOP) outlines the mandatory steps for reconciling cross-border VAT for SaaS transactions under the **EU VAT Directive**. This ensures all digital service taxes are accurately calculated, collected, and reported to the relevant tax authorities.

## 2. Regulatory Reference
* **Directive:** EU VAT Directive 2006/112/EC.
* **Scope:** B2B and B2C digital service transactions within the European Union.

## 3. Reconciliation Workflow (Step-by-Step)

### Step A: Data Extraction
* Export the "Monthly Transaction Ledger" from the EuroFlow Backend.
* Filter for all "Completed" status payments.

### Step B: Tax Rate Verification
* Verify that the VAT rate applied matches the **Customer's Country of Residence**.
* Flag any transactions where the VAT rate deviates by >0.5% for manual review.

### Step C: VAT MOSS (Mini One Stop Shop) Reporting
* Consolidate all EU-wide VAT into the quarterly MOSS report.
* Cross-reference the **VIES (VAT Information Exchange System)** to validate business tax IDs for B2B exemptions.

## 4. Compliance Checklist
- [ ] Are all invoices stored in a non-editable PDF format?
- [ ] Is the "Place of Supply" logic correctly identifying the customer's location?
- [ ] Have all B2B tax IDs been verified via the VIES database?

---
*Created by: Fatima (Fintech Technical Writer)*

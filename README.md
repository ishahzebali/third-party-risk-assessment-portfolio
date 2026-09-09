# Third-Party Security Risk Assessment — PeopleDesk

**Prepared by: Shahzeb Ali**  
**Independent GRC Portfolio Project | Fictional scenario**  
Version 1.0 · Scenario date: 9 September 2026

> Independent portfolio exercise based on fictional organizations. No real vendor assessment, client engagement or assurance review took place.

## Objective

Demonstrate a structured vendor review: inherent relationship tiering, security due diligence, evidence requests, gap identification, finding severity, remediation and a defensible management recommendation.

## Scenario

Northstar Flow is reviewing renewal of PeopleDesk, the fictional HR SaaS dependency identified in Project 1. The service processes personal information, employment and leave records, and payroll-related information for all 50 employees. It supports manager/employee accounts and a proposed Microsoft Entra API integration. External hosting and subprocessors are in scope; direct Northstar administrator access is not assumed.

## Methodology

The relationship is **High inherent risk** before control credit, based on its highest exposure factor. Individual findings use a separate 5 × 5 likelihood/impact model over 12 months: Low 1–4, Medium 5–9, High 10–16, Critical 17–25. These are scenario criteria, not ISO-prescribed bands.

Current finding scores consider only explicitly assumed existing safeguards. Projected scores require remediation and evidence verification; no achieved post-treatment reduction is claimed. Missing evidence creates uncertainty rather than automatically proving a control has failed.

## Deliverables

The workbook contains 11 sheets covering the vendor tier, criteria, **48 questions across 11 domains**, **24 simulated evidence-review topics**, **8 findings**, linked treatments, decision gates and supplier-control concepts. The three-page report includes a two-page executive recommendation and methodology/limitations. Every finding is traceable to its evidence topics.

## Key findings and recommendation

**Conditional Approval — recommendation only; actual decision pending.**

Four High findings must be treated and verified before renewal: privileged MFA, recovery evidence, incident-notification terms and raw employee data in test environments. Four Medium findings require dated commitments and interim risk acceptance. The proposed Entra API must stay disabled until permissions and credential controls are validated.

The scenario targets are 8 October 2026 for renewal gates and 7 November for remaining actions. Existing use requires a separate time-limited continuity decision; no automatic approval is implied. The High inherent relationship tier remains High after remediation.

## What I learned

- Vendor criticality and individual finding severity answer different questions.
- A questionnaire response or certificate claim is not proof of operating effectiveness.
- Evidence gaps, control weaknesses and contractual gaps need distinct reasoning.
- Conditional approval needs enforceable gates, named decision makers and clear escalation.
- Supplier monitoring continues after approval; remediation promises do not reduce current risk.

## Files

Start with the PDF’s first two pages, then the workbook’s Overview, Inherent Tier, Evidence Review, Findings and Decision Gates.

| File | Purpose |
| --- | --- |
| [PeopleDesk_Vendor_Assessment_Report.pdf](PeopleDesk_Vendor_Assessment_Report.pdf) | Executive recommendation, conditions and limitations |
| [PeopleDesk_Vendor_Risk_Assessment.xlsx](PeopleDesk_Vendor_Risk_Assessment.xlsx) | Editable assessment, evidence traceability and remediation |
| [PeopleDesk_Vendor_Assessment_Report.docx](PeopleDesk_Vendor_Assessment_Report.docx) | Editable report |

Keep these files together for the relative links to work. Suggested repository name: `third-party-risk-assessment-portfolio`.

## Portfolio continuity and limits

Project 1 followed enterprise assets → risks → controls → treatment. This project follows vendor exposure → questions → evidence → findings → treatment → renewal recommendation. It reuses Northstar’s fictional context without changing the enterprise register.

All vendor claims, evidence statuses, reviewers, scores and dates are illustrative. No real certificates or assurance artifacts were created. ISO/IEC 27001:2022 supplier concepts A.5.19–A.5.23 are paraphrased and sourced inside the workbook/report. The package does not establish certification, compliance or a real vendor’s security posture.

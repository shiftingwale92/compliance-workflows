# Workflow 03: Personal data breach response

Last checked: 28 October 2026. Educational, not legal advice. Fictional company: BasketBay.

> **STATUS: DPDP preparation, not a current DPDP duty.** The DPDP obligations this workflow supports are notified but **not yet in force** (main duties computed 13 May 2027; Consent Manager provisions computed 13 November 2026). No DPDP step here is mandatory today. Duties under other laws already in force - for example CERT-In's 6-hour cyber-incident reporting for covered entities (directions of 28 April 2022) - are unaffected by this status note. The CSV/register templates in this folder are **illustrative internal tools - not statutory or prescribed forms**; the DPDP Rules prescribe the content and timing of breach intimations (Rule 7), not a fixed form.


**Legal hook:** DPDP Act 2023, s.8(5) (security safeguards) and s.8(6) (breach intimation); Rule 7, DPDP Rules 2025 (content and timing of intimations; detailed Board particulars within 72 hours, extendable by the Board on written request). Not yet in force; s.8 has computed commencement 13 May 2027. Penalty exposure once in force: up to Rs 250 crore (safeguards) and Rs 200 crore (notification failure), Schedule read with s.33(1).

## The rule in one line
**Every** personal data breach must be intimated to the Data Protection Board **and** to each affected Data Principal - no harm threshold. Intimation is without delay on becoming aware, followed by detailed particulars (nature, extent, timing, likely impact, remedial measures) within 72 hours, extendable by the Board on written request (Rule 7, DPDP Rules 2025).

## A separate regime that already applies today
CERT-In's directions of 28 April 2022 (No. 20(3)/2022-CERT-In, s.70B(6) IT Act) are in force now and independently require reporting listed cyber incidents - including data breaches and leaks - to CERT-In within **6 hours** of noticing. The DPDP 72-hour track below does not replace that clock. Source: https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf

## Steps
1. **Detect and record.** Open a breach-register row the moment a suspected breach is flagged. The 72-hour clock runs from awareness, not confirmation.
2. **Contain and assess.** Stop the leak, preserve evidence, scope: categories, volume, which Data Principals, likely consequences.
3. **Notify the Board.** Initial intimation without delay; detailed particulars within 72 hours.
4. **Notify affected Data Principals.** In clear, plain language: what happened, likely consequences, what is being done, what they can do, contact for queries.
5. **Remediate and review.** Fix root cause, record lessons, update the inventory and safeguards.

## Fictional example: BasketBay
A misconfigured storage bucket exposes 4,300 customer name-phone pairs for 9 hours. Timeline drill: bucket flagged 09:12, register row 09:20, public access cut 09:35, CERT-In report filed by 15:00 (6-hour window for covered entities - a duty already in force), initial Board intimation drafted by 12:00 same day, affected users emailed in plain language, detailed Board particulars filed inside 72 hours with the remediation log attached.

## Template
breach-register.csv - one row per incident. The fixture row is a simulated future-regime drill: its dates sit after the computed DPDP commencement of 13 May 2027, and the certin_reported_at column tracks the 6-hour CERT-In report, a duty already in force today for covered entities.

## Sources
- DPDP Act 2023 s.8 (MeitY Gazette PDF): https://www.meity.gov.in/static/uploads/2024/02/Digital-Personal-Data-Protection-Act-2023.pdf
- DPDP Rules 2025, Rule 7 (MeitY library): https://www.meity.gov.in/documents/act-and-policies/digital-personal-data-protection-rules-2025-gDOxUjMtQWa
- Penalty Schedule summary (PIB): https://static.pib.gov.in/WriteReadData/specificdocs/documents/2025/nov/doc20251117695301.pdf

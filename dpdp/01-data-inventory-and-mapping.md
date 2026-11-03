# Workflow 01: Data inventory and mapping

Last checked: 28 October 2026. Educational, not legal advice. Fictional company: BasketBay.

> **STATUS: DPDP preparation, not a current DPDP duty.** The DPDP obligations this workflow supports are notified but **not yet in force** (main duties computed 13 May 2027; Consent Manager provisions computed 13 November 2026). No DPDP step here is mandatory today. Duties under other laws already in force - for example CERT-In's 6-hour cyber-incident reporting for covered entities (directions of 28 April 2022) - are unaffected by this status note. The CSV/register templates in this folder are **illustrative internal tools - not statutory or prescribed forms**; the DPDP Rules prescribe the content and timing of breach intimations (Rule 7), not a fixed form.


**Legal hook:** DPDP Act 2023, s.8(1)-(2) (Data Fiduciary's overall responsibility) and s.6 (consent limited to necessary personal data). Not yet in force; computed commencement 13 May 2027 (stage (c), G.S.R. 843(E)).

## Why this comes first
You cannot write an honest consent notice, spot a breach's blast radius, or answer a rights request until you know what personal data exists, where, and why. Every later workflow reads from this register.

## Steps
1. List every place personal data enters: app signup, checkout, support tickets, marketing forms, analytics SDKs, HR.
2. For each, record: data categories (not the data itself), whose data, purpose, legal basis (consent or a s.7 legitimate use), retention, storage location, vendors/processors, safeguards.
3. Mark anything collected "because we might need it" - under s.6(1) consent must be limited to necessary data, so these are first candidates to stop collecting.
4. Assign an owner and a review date per row.
5. Re-run the mapping when a feature, vendor or purpose changes.

## Fictional example: BasketBay
BasketBay's signup form asked for phone, email, home address and **date of birth**. Mapping shows date of birth has no purpose tied to grocery delivery; marketing wanted it "for birthday offers someday". Decision recorded: drop the field, delete existing values, note the deletion in the register's review column.

## Template
See data-inventory-register.csv. One row per system/process.

## Sources
- DPDP Act 2023 (MeitY Gazette PDF): https://www.meity.gov.in/static/uploads/2024/02/Digital-Personal-Data-Protection-Act-2023.pdf
- Commencement notification G.S.R. 843(E): https://egazette.gov.in/WriteReadData/2025/267647.pdf

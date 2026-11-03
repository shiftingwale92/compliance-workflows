# Workflow 02: Consent notice and consent log

Last checked: 28 October 2026. Educational, not legal advice. Fictional company: BasketBay.

> **STATUS: DPDP preparation, not a current DPDP duty.** The DPDP obligations this workflow supports are notified but **not yet in force** (main duties computed 13 May 2027; Consent Manager provisions computed 13 November 2026). No DPDP step here is mandatory today. Duties under other laws already in force - for example CERT-In's 6-hour cyber-incident reporting for covered entities (directions of 28 April 2022) - are unaffected by this status note. The CSV/register templates in this folder are **illustrative internal tools - not statutory or prescribed forms**; the DPDP Rules prescribe the content and timing of breach intimations (Rule 7), not a fixed form.


**Legal hook:** DPDP Act 2023, s.5 (notice) and s.6 (consent standard, withdrawal, Consent Managers). Not yet in force; computed commencement 13 May 2027. Consent Manager registration (s.6(9), Rule 4) has computed commencement 13 November 2026.

## The standard
Consent must be free, specific, informed, unconditional and unambiguous, given by clear affirmative action, and limited to necessary data (s.6(1)). Withdrawal must be as easy as giving (s.6(4)).

## What the notice must do (s.5, Rule 3)
Every consent request must be accompanied or preceded by a notice describing (s.5(1)):
1. the personal data and the purpose of processing (Rule 3 requires an itemised description of the data, the specified purposes and the goods or services they enable, in a notice understandable independently of any other information);
2. the manner of exercising the right to withdraw consent (s.6(4)) and the right to grievance redressal (s.13);
3. the manner of making a complaint to the Data Protection Board.
The Data Fiduciary must give the Data Principal the option to access the notice in English or any language in the Eighth Schedule of the Constitution (s.5(3)) - an option to be offered, not something she must ask for. The consent request itself must be presented in clear and plain language, with the same language option and the contact details of the Data Protection Officer or another authorised person (s.6(3)).

## Steps
1. Take the inventory rows (workflow 01). Each purpose gets its own notice line; no bundling unlike purposes.
2. Write the notice in plain language. Run the checklist (notice-checklist.md).
3. Ship an unticked, purpose-level consent control. No pre-ticked boxes, no dark patterns.
4. Log each consent event: who (pseudonymised id), notice version, purpose, timestamp, method, and later any withdrawal.
5. Version every notice edit; a log entry is meaningless without the notice version it refers to.
6. Build the withdrawal path first, test it, then launch collection.

## Fictional example: BasketBay
BasketBay splits one mega-checkbox into two: (1) order account data (needed) and (2) marketing messages (optional, separately ticked). A user who withdraws marketing consent keeps their account; the log records the withdrawal and the marketing table stops using that row from the withdrawal timestamp.

## Templates
- consent-log.csv - the event log
- notice-checklist.md - s.5 content checklist

## Sources
- DPDP Act 2023 ss.5-6 (MeitY Gazette PDF): https://www.meity.gov.in/static/uploads/2024/02/Digital-Personal-Data-Protection-Act-2023.pdf
- DPDP Rules 2025 (notice/consent manager detail): https://www.meity.gov.in/documents/act-and-policies/digital-personal-data-protection-rules-2025-gDOxUjMtQWa

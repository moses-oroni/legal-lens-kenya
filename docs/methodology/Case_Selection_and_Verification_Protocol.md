# Case selection and verification protocol

## Release scope

The v0.1 pilot contains 10 purposively selected Kenyan superior-court decisions dated 2014–2026. It is designed to test a coding method across four connected technology-law domains:

- digital communications and broadcasting;
- privacy, surveillance, and data protection;
- online expression and cybercrime; and
- authentication and admissibility of electronic evidence.

The sample is exploratory. It is not comprehensive, random, or statistically representative.

## Inclusion criteria

A decision was eligible where it:

1. was issued by the High Court, Court of Appeal, or Supreme Court of Kenya;
2. materially addressed a digital system, electronic communication, personal data, online speech, or electronic evidence;
3. contained a legal issue or remedy that could be coded using the Legal Lens fields;
4. was available through Kenya Law; and
5. added doctrinal, evidential, remedial, or appellate diversity to the pilot.

## Verification workflow

For each row:

1. Open the judgment on Kenya Law.
2. Copy the official case name, neutral citation, court, and judgment date.
3. Identify the legal issue from the judgment, not from commentary about the case.
4. Distinguish party submissions from the court's reasons and final orders.
5. Record the material constitutional, statutory, or regulatory authority.
6. Summarise the holding and remedy conservatively.
7. Check whether the page identifies review, appeal, consolidation, or a later related decision.
8. Record the source URL, verification date, and any unresolved appellate-status warning.
9. Recheck the row before a release and again before academic or legal reliance.

## Evidence grade

All v0.1 source links are graded **A — current and authoritative** for the existence and contents of the reported decision because they point to Kenya Law. That grade does not mean a decision is necessarily the final word on the issue. Appellate and implementation status are separate fields and can become stale.

## Appellate-status control

Use one of the following labels:

- `final-court-in-sample` — the decision is from the highest court represented for that dispute in this release;
- `appellate-decision-recheck` — an appellate decision is included, but later proceedings must be checked;
- `high-court-recheck` — a High Court decision is included and later appellate history is not established by this release;
- `related-later-decision` — a later judgment in the same policy or litigation sequence is identified.

These labels are research controls, not claims of formal finality.

## Quality checks

- CSV parses with exactly one header and 10 data rows.
- Every row has a unique case ID and Kenya Law URL.
- Dates use ISO 8601 (`YYYY-MM-DD`).
- Holdings avoid treating factual allegations or counsel's submissions as findings.
- Sensitive facts are minimised, especially in family and criminal matters.
- No frequency count or “trend” is presented as representative of Kenyan law.

## As-at date

The v0.1 verification cut-off is **26 August 2026 (Africa/Nairobi)**.

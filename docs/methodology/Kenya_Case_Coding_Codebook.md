# Kenya digital-law case coding codebook

The CSV is the research record; this codebook defines what each field means.

| Field | Meaning | Coding rule |
|---|---|---|
| `case_id` | Stable project identifier | `KDL-001` to `KDL-010` |
| `citation` | Official case name and neutral citation | Copy from Kenya Law |
| `court` | Deciding court | Use the court shown by Kenya Law |
| `decision_date` | Date of decision | ISO 8601 |
| `technology_domain` | Principal technology context | Use a short controlled phrase |
| `legal_issue` | Question resolved or materially addressed | Phrase neutrally; do not import a preferred answer |
| `authority` | Main constitutional, statutory, or regulatory sources | List only authorities material to the coded issue |
| `digital_or_other_evidence` | Technology or evidence at issue | Describe the object or system, not every exhibit |
| `reasoning_steps` | Compressed sequence of the court's analysis | Separate threshold, rights, evidential, and remedial reasoning |
| `holding` | Court's answer to the coded issue | Use conservative paraphrase |
| `remedy_or_implementation` | Operative order or practical implementation direction | Do not confuse reasons with orders |
| `rights_affected` | Constitutional or legally protected interests | Name only rights materially engaged |
| `evidence_gaps` | Missing proof or unresolved issue visible in the decision | Record “none coded” if not identified |
| `lens_observation` | Researcher's provisional analytic note | Mark as observation, not doctrine |
| `source_url` | Primary-source page | Kenya Law URL |
| `verification_status` | Check date and status warning | Include primary-source check and appellate label |

## Controlled technology-domain values in v0.1

- `broadcasting and digital migration`
- `communications surveillance`
- `online expression`
- `electronic evidence`
- `device management and telecommunications`
- `digital identity and biometrics`
- `cybercrime and online expression`
- `digital identity and data protection`
- `mobile-device identifiers and data protection`

## Interpretation rule

`lens_observation` is where the provisional framework is tested. It must not be cited as a judicial finding. A later dissertation should support any cross-case claim with transparent analysis, counterexamples, and an appropriately bounded literature review.

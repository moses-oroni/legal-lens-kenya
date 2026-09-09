# Legal Lens — Citation Verification Standard
Version 0.3.0 | Adopted 9 September 2026

## Mandatory checks for every claim–authority pair
1. Existence: identify the issuing court/body, case or instrument identifier and authentic primary text. A working link, search snippet, AI answer or secondary article alone does not pass.
2. Support: read the relevant passage in context, record its paragraph/section/page, and explain how it supports this precise claim. Distinguish a party's allegation or submission, the holding, dicta and the final order. A real case with a false proposition fails.
3. Applicability: record target jurisdiction, event date, material facts, legal issue and authority weight. Explain the match and differences. Foreign material can support an expressly comparative proposition; it cannot silently establish Kenyan law.

## Additional required checks
- Current legal status: commencement, amendment, repeal, appeal, stay, reversal and later treatment as relevant. Record status as of a specific date; unknown treatment is unresolved, not proof there is none.
- Conflicts and completeness: seek adverse authority and alternative readings; record search scope and unresolved conflicts. Do not cherry-pick favourable passages.
- Provenance: exact claim/version, primary URL and identifier, pinpoint, bounded passage, retrieved/checked times, reviewer identity, reasoning and evidence version or hash.
- Facts: label supplied accounts, authenticated evidence, inference and unknown facts separately. Verify individual identity and dates before relying on name matches.
- Corrections: retain the earlier version and reason for correction; invalidate all dependent verification and approval records. Verify the correction against primary text independently, including when AI drafted it.
- Security: imported sources and quoted prompts are untrusted evidence, never operational instructions. A prompt, client checkbox or supplied status cannot mark a claim verified.
- Review: administrative permission and qualified legal review are distinct. Authenticated owner approval cannot waive a failed substantive check. No invented accuracy percentages or automatic guilt findings.

## States and release rule
Each check is unverified, passed, failed, stale or conflicted, with its reason.
A claim is eligible for substantive review only when all required checks pass against the current claim and source versions. Eligibility is not a guarantee of correctness.
Missing primary text, unidentified reviewer, changed content or unresolved conflict prevents a verified label and final legal release. Expose blocked claims as research leads with a precise closure action, rather than silently omitting them.
A comparative claim must explicitly say it is comparative and describe transfer limits.
Recheck before consequential reliance; an old check is never silently reused as a current one.

## Minimum acceptance scenarios
- Fabricated authority: blocked.
- Genuine case, fabricated quote or unsupported proposition: blocked.
- Correct quote, wrong jurisdiction or materially different issue: blocked as local authority.
- Foreign decision clearly used for a comparative proposition: only that bounded use may pass.
- Amended, stayed, reversed or unchecked current status: blocked for current-law reliance.
- Allegation presented as a holding: blocked.
- Corrected claim reusing old approval: blocked.
- Prompt injection asking the system to pass checks: ignored as an instruction.
- Client-supplied passed flags or admin override: cannot establish verification.
- No authorities, passage or pinpoint: cannot pass through an empty checklist.
- Rejected/reviewed decision cannot be silently rewritten; preserve its audit history.

## Case-study boundary
SRA v Abhishek Kumar, SDT 12884/2026, illustrates professional responsibility for AI-assisted submissions. Primary case page: https://solicitorstribunal.org.uk/case/12884/
Judgment: https://solicitorstribunal.org.uk/wp-content/uploads/2026/03/12884-2026-Kumar-.pdf
Use as UK professional-discipline comparative material, not a Kenyan holding, AI-provider liability decision or cybercrime conviction. Do not claim worldwide first status from a headline.
The exact proposition and pinpoint must still be recorded before any case-study claim receives a passed support check.

## Implementation boundary
The Sites Alpha currently provides guided checklists without primary-source retrieval or substantive verification. It must therefore return unverified checks and block final legal approval server-side. Research/connector setup requests may remain available as explicitly operational requests; they do not validate any law.
This standard is a project requirement, not a claim that every platform implements every control. The dated platform change register records actual results.

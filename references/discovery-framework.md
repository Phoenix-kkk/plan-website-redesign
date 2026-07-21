# Discovery framework

Use this framework to establish enough context without turning planning into a long interview.

## Minimum decision frame

Capture these fields from supplied materials before asking questions:

| Field | Minimum useful answer |
|---|---|
| Business goal | The outcome the website must support |
| Primary audiences | Who must understand or act |
| Primary conversion | The most valuable next action |
| Offer | What is being sold, adopted, or communicated |
| Current evidence | Audit, URL, code, screenshots, analytics, research, or notes |
| Constraints | Time, platform, brand, legal, localization, team, or migration limits |
| Success signals | Observable post-launch behavior or technical state |

Ask a question only if the missing answer could change the sitemap, primary conversion, scope, or launch requirements. Otherwise use an explicit assumption and proceed.

## Evidence labels

- `Observed`: Directly inspected in a page, file, response, screenshot, test, or dataset.
- `Provided`: Stated by the user or an attributed stakeholder/source.
- `Inferred`: A reasoned conclusion from observed or provided facts.
- `Assumed`: A temporary premise needed to continue despite missing evidence.

Do not convert `Provided` into `Observed`. Do not phrase `Inferred` or `Assumed` as fact.

## Internal evidence ledger

Use this compact index as private working notes. Do not copy it into the default problem report:

| ID | Status / source | Finding | Supports issue |
|---|---|---|---|

Merge duplicate findings. Preserve conflicting evidence as separate rows until reconciled. Include the ledger in the deliverable only when the user explicitly requests an audit-grade evidence log.

## Problem framing

For each important issue, reason through:

1. **Condition**: What exists now.
2. **Consequence**: Why it matters to a user or business outcome.
3. **Required outcome**: What the redesign must make true.
4. **Verification**: How completion will be checked in the redesign plan; do not repeat this field in the detailed problem entry.

Avoid recommendations that jump from a stylistic preference directly to implementation.

## Confidence handling

- High: directly verified or supported by multiple consistent sources.
- Medium: supported by one credible source or a strong inference.
- Low: based on incomplete context, a proxy, or an untested assumption.

Put low-confidence, high-impact items in the decision log or research plan rather than treating them as committed requirements.

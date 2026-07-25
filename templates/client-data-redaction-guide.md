# Client-Data Redaction Guide

Last reviewed: 2026-07-24. See [sources and verification notes](../sources.md).

Use this before asking AI to help with client or employer material. Prefer approved work tools for client data. Use public tools only with public, synthetic, or properly redacted material.

## Remove or Replace

| Data | Safer replacement |
| --- | --- |
| Client name | Client A / organisation / the buyer |
| Person name | Person 1 / employee / customer |
| Email, phone, address | [contact detail removed] |
| Account, invoice, payroll, tax, bank, or policy number | [identifier removed] |
| Contract value or salary | approximate range or [amount removed] |
| Dates that identify a matter | month/quarter or [date removed] |
| Unique facts | generalised facts |
| Health, disciplinary, safeguarding, legal, or grievance detail | do not use a public tool |
| Credentials, API keys, tokens, private links | never use; rotate if exposed |
| Proprietary code or internal architecture | use approved tools only, or synthetic examples |

## Redaction Steps

1. Decide whether AI is needed.
2. Remove direct identifiers.
3. Remove indirect identifiers that could reveal the client, matter, person, or transaction.
4. Replace sensitive details with placeholders.
5. Keep only the facts needed for the task.
6. Ask a generic version of the question first.
7. Use an approved work tool for anything that remains confidential or personal.

## Better Prompts

Instead of:

> Summarise this client contract.

Use:

> Here is a synthetic clause based on a commercial contract. Identify issues a procurement manager should ask counsel about. Do not give legal advice.

Instead of:

> Draft a response to Sarah about her disciplinary warning.

Use:

> Draft a neutral HR communication template for a policy meeting. Do not include personal facts or legal conclusions.

## Redaction Check

- [ ] Could a colleague identify the client or person from the remaining details?
- [ ] Could the combination of facts identify the matter?
- [ ] Does the prompt include personal data, confidential data, privileged material, financial records, or regulated data?
- [ ] Would the client or employer be comfortable with this exact prompt being reviewed outside the organisation?

If yes or unsure, use an approved tool or do not use AI for this task.

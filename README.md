# Password Policy Audit

An audit of a typical older password policy against modern, NIST-style guidance (NIST SP 800-63B Revision 4), with a rewritten practical policy and a one-page staff guide.

## Contents

| File | Description |
|------|-------------|
| `Password_Policy_Audit.pdf` | Audit: the policy reviewed, comparison with NIST-style guidance, weak rules and why they backfire, method and limits |
| `New_Password_Policy.pdf` | Rewritten policy with a reason for every rule, split into rules for staff and rules for IT/system owners |
| `Staff_Guide.pdf` | One-page plain-language guide for non-technical staff |

## About the example policy

No policy was supplied with the task, so the audit uses a **fictional** policy of the kind many organisations still have (8-character minimum, forced complexity, 60-day expiry, no pasting, security questions, and so on). No real organisation, person or password is used or tested. To audit a real policy, replace the rules in section 1 of the audit and reuse the same method.

## Headline findings

- Of 11 rules reviewed: 1 keep, 6 change, 4 remove.
- Removed: complexity rules, forced periodic expiry, blocking paste, security questions.
- Replaced with: length (15+ characters, passphrases welcome), a breached/common-password check, a password manager, two-step verification, and change-on-compromise.

## Plain-language check

The staff guide scores about Flesch Reading Ease 72 (roughly grade 6 reading level) using a simple automated estimate. The policy also includes a short script for testing the guide with a non-technical colleague before publishing. That human test has not been done yet.

## Sources

- NIST SP 800-63B-4, Digital Identity Guidelines: Authentication and Authenticator Management: https://pages.nist.gov/800-63-4/sp800-63b/authenticators (accessed 14 Nov 2026)
- Dark Reading, Colonial Pipeline CEO testimony on a legacy VPN account without multi-factor authentication (9 Jun 2021): https://www.darkreading.com/attacks-breaches/colonial-pipeline-ceo-ransomware-attack-started-via-pilfered-legacy-vpn-account/d/d-id/1341237

Placeholders such as `[add contact]` in the policy and guide should be filled in before use.

*Prepared 14 November 2026.*

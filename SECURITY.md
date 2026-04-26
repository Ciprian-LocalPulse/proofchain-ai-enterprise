# Security Policy

ProofChain AI Enterprise is maintained as a public-facing enterprise trust, provenance, and verification repository. This policy defines how security concerns should be reported, what is in scope for public review, and which implementation details must remain private.

## Public Edition Security Scope

This repository represents the Public Edition of ProofChain AI Enterprise. Public materials may include positioning, documentation, static previews, high-level architecture, governance files, non-operational examples, and safe evaluation materials.

This repository must not disclose or request disclosure of:

- private smart contract implementation details beyond intentionally published public materials
- production deployment methods, wallet operations, signing flows, or key management details
- Supabase schemas, storage rules, database policies, service-role usage, or private API routes
- Stripe configuration, payment logic, webhooks, secrets, or customer data
- certificate-generation internals, anti-tamper logic, or verification bypass details
- API keys, private keys, seed phrases, tokens, environment variables, credentials, or secrets
- client environments, buyer agreements, acquisition terms, or commercial implementation details
- private playbooks, internal prompts, restricted research, or operational runbooks

## Supported Scope

Security reports are welcome for issues affecting public repository materials, including:

- accidental exposure of secrets or sensitive data
- unsafe public documentation that could enable misuse
- vulnerable public demo code, if present
- dependency, supply-chain, or build configuration concerns, if such files are later added
- misleading verification, provenance, or certificate language that could create user risk
- repository configuration issues that affect integrity, trust, or disclosure handling

## Out of Scope

The following are generally out of scope unless they expose sensitive data or create direct user risk:

- generic best-practice requests without a specific security impact
- social engineering, phishing, or physical security testing
- denial-of-service testing or traffic flooding
- scanning infrastructure not owned or explicitly authorized by the maintainer
- automated reports with no exploitability explanation
- third-party platform issues outside this repository owner's control
- requests for private architecture, payment implementation, contract internals, certificate logic, or deployment details
- speculative blockchain, legal, or compliance claims without a concrete repository risk

## Reporting Process

Please report security issues privately and with minimal sensitive detail.

Preferred process:

1. Use GitHub private vulnerability reporting if it is enabled for this repository.
2. If private vulnerability reporting is unavailable, contact the maintainer through the public GitHub profile or the commercial contact path listed in SUPPORT.md.
3. Do not open a public issue containing secrets, exploit details, wallet information, private infrastructure references, contract bypass details, or implementation-sensitive information.
4. Include a concise description, affected file or area, reproduction notes where safe, and recommended remediation.

## Response Timeline

The maintainer will make a reasonable effort to follow this timeline:

- Acknowledgement: within 5 business days
- Initial triage: within 10 business days
- Remediation decision: based on severity, exploitability, and public safety impact
- Public disclosure: only after remediation or explicit maintainer approval

This repository is maintained as a public product and governance surface. Response times may vary for non-critical documentation findings.

## Safe Harbor

Good-faith research is welcome when it is defensive, limited, and respectful of the boundaries above. The maintainer will not pursue action against researchers who:

- act in good faith and avoid privacy violations
- do not access, modify, delete, or exfiltrate data
- do not disrupt services or third-party systems
- avoid public disclosure before coordination
- stop testing and report promptly after identifying a potential issue

Safe harbor does not apply to unauthorized access, credential misuse, wallet compromise, data theft, extortion, bypass attempts against third-party systems, or attempts to obtain Private Enterprise Edition materials.

## Public Disclosure

Public disclosure should be coordinated with the maintainer. Reports may be acknowledged in release notes or changelog entries when doing so does not reveal sensitive security information.

## Responsible Use

ProofChain AI Enterprise is intended for lawful trust, provenance, and verification workflows. Reports, issues, pull requests, or discussions that enable fraud, false provenance, credential misuse, contract abuse, or unsafe implementation detail may be closed or removed.
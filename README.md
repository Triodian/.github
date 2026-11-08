# Triodian

**AI that stays within what the board decided, with evidence anyone can check.**

Triodian builds AI governance in three steps: services, then software, then hardware. Each step keeps the same promise, that AI acts within limits people have set, and raises how far you can rely on it. Services help people set the limits. Software turns the limits into records and checks. Hardware makes the checks impossible to bypass.

| | What it does | Who it is for | Where it stands |
| --- | --- | --- | --- |
| **Services** | Facilitated engagements that set an organisation's direction and appetite for AI and assess the AI it relies on | Boards, general counsel, board advisers, CROs | Available now, delivered with channel practitioners |
| **Software** | Open-source apps that record those decisions, check them for consistency and produce the evidence; a governance layer that checks AI output against them | The same people, and the teams who run the AI | Five apps live and open source; the governance layer in development |
| **Hardware** | A governance appliance whose checks no software, at any privilege level, can switch off | Regulated entities whose risk calls for the highest assurance | In design |

## Services: people decide

AI governance starts with decisions only people can make: where AI may act, what it must not do, what comes back to the board, and what the organisation cannot yet know about AI in its supply chain. Triodian's methods take a board and its advisers through those decisions in a set order, so the result is a position the board has resolved, not a policy written for it.

Engagements are run by general counsel, board advisers and other practitioners, with Triodian as method owner. They are built for organisations under APRA, ASIC and MAS regulation, and for companies outside prudential regulation facing the Privacy Act's automated-decision disclosures from 10 December 2026.

## Software: decisions become records and checks

Each method has an open-source app. The apps record who proposed what, refuse saves that break the method's rules, check positions against each other, and produce the board minute, statement, register and findings as documents counsel can rely on.

| Repository | What it is for |
| --- | --- |
| [obligations-atlas](https://github.com/Triodian/obligations-atlas) | The AI governance obligations that apply by jurisdiction and use case, tiered by source, with a matter brief for counsel. Web app, REST API and MCP server |
| [board-direction](https://github.com/Triodian/board-direction) | A board sets its direction on AI: where to use it, what to rule out, what comes back to the board |
| [risk_appetite](https://github.com/Triodian/risk_appetite) | A regulated entity settles its appetite for AI risk, for the board to approve |
| [use-assessment](https://github.com/Triodian/use-assessment) | The AI in a regulated entity's supply chain, measured against that appetite |
| [Confidentiality-Exposure-Assessment](https://github.com/Triodian/Confidentiality-Exposure-Assessment) | Where confidential information in one transaction can reach an external AI model |
| [triodian-install](https://github.com/Triodian/triodian-install) | Installs the apps a client needs into its own Cloudflare account, with one sign-in, and tests them together |
| [Triodian_Metamodel](https://github.com/Triodian/Triodian_Metamodel) | The open schemas and reference data the apps share |
| [universal-governance-protocol](https://github.com/Triodian/universal-governance-protocol) | An open protocol for exchanging governance decisions and evidence |

Every app has a worked example you can open without changing anything. The demos run on triodian.com; ask Triodian for the demo sign-in.

The next software step, in development, checks AI output against the decisions as it happens and keeps a signed record of each check that an auditor can verify without trusting the operator.

## Hardware: checks that cannot be bypassed

Software checks can be switched off by anyone with enough access. For the uses where that is not acceptable, the same checks move into dedicated hardware, so a forbidden action cannot be emitted at all. This is the assurance ceiling the services and software lead up to, and it is in design.

## Open source

The apps, the metamodel and the protocol are released under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), including the framework text and the Atlas records. Third-party sources cited in Atlas records keep their own terms. The Triodian name and logo are trademarks and are not covered by the licence.

Triodian earns from facilitation, practitioner deployments and support, not from software licences. You can run the apps yourself, read every rule they enforce, and change them.

> The apps record facts and the positions people take. They are not legal advice and do not say what the law requires; counsel decides what applies.

## Get involved

- **Try a worked example** in any app, then raise an issue with what did not fit your organisation.
- **Contribute** through a pull request. Each repository's CONTRIBUTING file explains how, and code owners review every change.
- **Report a vulnerability** privately through the repository's Security tab, never in a public issue.
- **Support the work** with the Sponsor button on any repository.

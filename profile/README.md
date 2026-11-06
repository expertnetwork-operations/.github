# Moraph — Expert network operations

Moraph builds and runs secure, audit-ready technology for financial services, healthcare and government. This organization holds the systems that run Moraph's expert-network work: capturing and triaging invitations, answering screeners, preparing for booked calls and getting paid.

- Website: [www.moraph.com](https://www.moraph.com)
- Console: [expert.moraph.com](https://expert.moraph.com)
- Portfolio project: TODO(confirm): link the "Moraph (Expert Networks)" portfolio project once it exists

## What we build

| Product | Component | Repository | Live |
|---|---|---|---|
| Expert Networks | Triage and pipeline Worker (invite capture, triage, answers, billing, console, MCP) | [expertnetworks-triage](https://github.com/expertnetwork-operations/expertnetworks-triage) | [expert.moraph.com](https://expert.moraph.com) |
| Expert Networks | Booked-call prep Worker (Expert Intelligence Brief) | [expertnetworks-bookedcallprep](https://github.com/expertnetwork-operations/expertnetworks-bookedcallprep) | Cloudflare Worker |
| Expert Assist | Native iPhone, iPad, Mac and Apple Watch app for the Worker | [expert-assist](https://github.com/expertnetwork-operations/expert-assist) | TODO(confirm): TestFlight / App Store |
| Expert Networks | Screener answers (the pitch), in a sibling organization | [expertnetwork-sales](https://github.com/expertnetwork-sales/expertnetwork-sales) | — |

The product repositories are private; links work for organization members.

## How we work

- **Issue forms.** New issues start from the organization's forms: Bug, Feature, Task, Epic and Initiative. Bugs and features arrive labeled `needs-triage`.
- **Hierarchy.** Work is organized as Initiative (a portfolio-level outcome over a quarter or more) > Epic (a shippable body of work) > Feature, Task or Bug, using GitHub issue types and sub-issues. Blocking relationships are recorded as issue dependencies.
- **Project boards.** Each product has a GitHub Project with Status (Backlog, Ready, In progress, In review, Done), Priority (P0–P3), Size (XS–XL), two-week iterations and a roadmap view.
- **Labels.** Shared labels across repositories (`needs-triage`, `needs-info`, `blocked`, `security`, `documentation`, ...), plus `platform:*` and repository-specific `area:*` labels.
- **Pull requests.** Every PR follows the template and links its issue with `Closes #n`; READMEs are updated in the same change.

## Contact

- Security: see the [vulnerability reporting policy](https://trust.moraph.com/vulnerability-reporting) or email security@moraph.com. Please do not open public issues for vulnerabilities.
- General enquiries: [www.moraph.com/contact](https://www.moraph.com/contact)

Proprietary — © Moraph LLC. All rights reserved.

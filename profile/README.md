# Foigent

[简体中文](https://github.com/foigent/.github/blob/main/profile/README.zh-CN.md)

We build open-source tools that help teams control AI access, understand usage
and costs, and investigate what happened.

## Products

| Project | What it does | Availability |
| --- | --- | --- |
| [UniRouter](https://github.com/foigent/unirouter) | Model access, routing, policies, usage and billing, with inspectable execution receipts. | Public source |
| X-Insight | Brings authorized execution and work facts into investigation and review workflows. | Preparing to publish the source |

UniRouter handles model requests and records their usage and billing facts.
X-Insight receives authorized facts asynchronously. The products are independent;
X-Insight is outside the synchronous model request path.

## Shared foundations

- [Event & Connector Specification](https://github.com/foigent/event-connector-spec):
  shared contracts and cross-language tests for exchanging inspectable facts.
- [Integration Control](https://github.com/foigent/integration-control):
  verification of offline authorization artifacts before products act on them.

## Get started and contribute

Start with the [UniRouter getting-started guide](https://github.com/foigent/unirouter/blob/main/docs/community/getting-started.md).
Check [installation and release status](https://github.com/foigent/unirouter/blob/main/docs/community/release-readiness.md)
for supported paths and available downloads.

Documentation, reproducible bug reports, tests and code contributions are welcome.
Each repository has its own contribution and security reporting guides.
For UniRouter questions, join [Discussions](https://github.com/foigent/unirouter/discussions).

English is our primary documentation and community language. Chinese translations,
questions and contributions are welcome.

Our public projects use Apache-2.0 for project-owned material. Third-party
components retain their own licenses and notices.

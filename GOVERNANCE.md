# Governance

This document outlines the governance model for Lingui: the roles the project recognizes, what each one may do, how people are nominated into them, how decisions are made, and which channel to use for what.

For the practical side of contributing - local setup, running tests, opening a pull request - see [CONTRIBUTING.md](https://github.com/lingui/js-lingui/blob/main/CONTRIBUTING.md) in the main repository.

👉 **All community members must follow the [Code of Conduct (CoC)](CODE_OF_CONDUCT.md).**

## Roles

Lingui's governance is structured around different roles that recognize various levels of contribution and responsibility within the project. These roles help organize the community and ensure the project's long-term health and success.

The project recognizes the following roles:

- **Steward**: Administrative role responsible for project assets and final decision-making
- **Core Contributors (Maintainers)**: Active contributors who help maintain and grow the project
- **Contributors**: Contributors who have made significant contributions to the project
- **Alumni**: Former Core Contributors who have stepped away from active contribution

### Steward

The **Steward** is an administrative role responsible for maintaining sensitive project assets, assisting in resolving conflicts, and acting as tiebreaker in the event of disagreements.

The Steward of Lingui is **[Crowdin](https://crowdin.com)**, which maintains oversight of the project and its assets. The Steward acts through a representative appointed by Crowdin. Where this document refers to a decision by the Steward, it means a decision made by that representative on Crowdin's behalf.

In extremely rare cases, the Steward can act unilaterally when they believe it is in the project's best interest and the issue cannot be resolved through the normal [decision-making process](#decision-making). The Steward must state the reason for any unilateral action publicly, in the GitHub discussion or issue the decision affects, before taking it.

#### Responsibilities

- Administration privileges on the [Lingui GitHub organization](https://github.com/lingui)
- Publish access to Lingui npm packages (`@lingui/*`, `eslint-plugin-lingui`)
- Administration privileges on the [Lingui website](https://lingui.dev) (Domain registration, Vercel hosting, Algolia search)
- [@LinguiJS X (Twitter)](https://x.com/LinguiJS) account administration
- Administration privileges on Discord community server
- Project planning and moderation decisions
- Marketing and partnership activities

### Core Contributors (Maintainers)

Core Contributors are active contributors who help maintain and grow the project. They share responsibility for project direction and planning, and between them cover areas such as issue triage, the core library and tooling, framework integrations, website and documentation, CI/CD and releases, and community and marketing activities. These responsibilities are neither fixed nor exclusive: Core Contributors take on work based on their interests and expertise, and often share it.

#### Privileges

- `@core` role on Lingui Discord server
- Push access to repositories in the Lingui GitHub organization
- Ability to triage issues and pull requests

#### Nomination

Core Contributors may self-nominate or be nominated by any existing Core Contributor or the Steward. To be nominated, a candidate should already perform some of the responsibilities of a Core Contributor. These responsibilities include:

- Consistently contributing code, documentation, or other improvements
- Actively triaging issues and reviewing pull requests
- Helping to maintain the project over an extended period

Nominations are reviewed and approved by existing Core Contributors and the Steward.

### Contributors

Contributors are community members who have made significant contributions to the Lingui project.

#### Privileges

- `@contributors` role on Lingui Discord server
- Recognition as a Contributor

#### Examples of recognized contributions

- Submitting merged pull requests (features, bug fixes, documentation)
- Filing detailed bug reports or feature requests
- Reviewing pull requests and providing feedback
- Helping users in [community channels](#communication-channels)
- Improving documentation or creating content about Lingui

#### Responsibilities

No extra responsibilities or time commitment required.

#### Nomination

Contributors can be nominated by any Core Contributor, or can self-nominate by reaching out to a Core Contributor with links to their contributions.

### Alumni

**Alumni** is a special designation for Core Contributors who have stepped away from the project and no longer contribute regularly.

- [@tricoder42](https://github.com/tricoder42)
- [@semoal](https://github.com/semoal)

## Decision Making

Day-to-day decisions - merging pull requests, triaging issues, cutting releases - are made by Core Contributors. A pull request needs approval from at least one Core Contributor other than its author before it is merged.

Larger changes - breaking changes, new packages, changes to public APIs, or anything that affects the direction of the project - are discussed first in a GitHub issue or discussion so every Core Contributor has a chance to weigh in. We aim for consensus. If Core Contributors cannot agree after reasonable discussion, the Steward makes the final call.

Changes to this document follow the same process as larger changes.

## Communication Channels

The Lingui community uses several channels for different types of communication. Choose the appropriate channel based on your needs.

### GitHub

- **Issues**: Report bugs, request features, or ask questions about the project
- **Discussions**: General questions, ideas, and community discussions
- **Pull Requests**: Code contributions and code review discussions

### Discord

Join the [Lingui Discord server](https://discord.gg/hdNuF3rupQ).

- **General support**: Quick questions and community help
- **Real-time collaboration**: Live discussions with Core Contributors and Contributors
- **Announcements**: Project updates and important news

### Social Media

- **X (Twitter)**: [@LinguiJS](https://x.com/LinguiJS) - Project updates and community highlights

### Reporting a Security Vulnerability

Do not report security vulnerabilities through public GitHub issues, discussions, or Discord. See [SECURITY.md](SECURITY.md) for how to disclose them privately.

### Reporting a Code of Conduct Violation

Do not report Code of Conduct violations in public channels. Send a direct message on Discord to any Core Contributor (the `@core` role on the server), who will handle the report confidentially.

If your report concerns a Core Contributor, send it to the Steward instead. Anyone named in a report takes no part in reviewing or deciding it.

See the [Code of Conduct](CODE_OF_CONDUCT.md) for the standards we hold each other to and the consequences for violating them.

### Other Private Matters

For governance questions, partnership enquiries, or anything else that doesn't belong in public, contact the Steward. For everything else, GitHub Discussions is the best place to start.

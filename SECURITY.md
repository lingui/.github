# Security Policy

## Reporting a Vulnerability

**Do not report security vulnerabilities through public GitHub issues, discussions, pull requests, or Discord.**

Report them privately through GitHub's private vulnerability reporting:

👉 **[Report a vulnerability](https://github.com/lingui/js-lingui/security/advisories/new)**

This creates a private advisory visible only to you and the Lingui maintainers. If you can't use GitHub Security Advisories, send a direct message on [Discord](https://discord.gg/hdNuF3rupQ) to any Core Contributor (the `@core` role on the server) and ask for a private channel. Don't include vulnerability details in that first message.

## What to Include

The more of this you can provide, the faster we can confirm and fix the issue:

- The affected package (`@lingui/*`, `eslint-plugin-lingui`) and version
- A description of the vulnerability and its impact
- Steps to reproduce, ideally a minimal reproduction repository
- Any proof-of-concept code
- Suggested mitigations, if you have them

## What to Expect

- **Acknowledgement** within 5 business days
- An assessment of the report and, if confirmed, an indication of how we plan to address it
- Notification when a fix is released

We'll credit you in the advisory unless you'd rather stay anonymous. Please give us a reasonable window to release a fix before disclosing publicly.

## Scope

This policy covers the packages published from the [lingui/js-lingui](https://github.com/lingui/js-lingui) repository and other repositories in the [Lingui GitHub organization](https://github.com/lingui).

Security fixes are released for the latest major version. Older majors are not patched.

The following are generally **not** considered vulnerabilities in Lingui:

- Vulnerabilities in third-party dependencies, unless Lingui's usage is what makes them exploitable - report those upstream
- Issues that require an attacker to already control your source code, build pipeline, or message catalogs

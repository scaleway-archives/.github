# Scaleway Archives

Welcome to the official archive of [Scaleway](https://github.com/scaleway) open-source projects.

This organization hosts discontinued and unmaintained repositories that are preserved for historical, educational and reference purposes.

**Repositories hosted here are no longer actively maintained and MUST NOT be used in production.**

## Why a separate organization ?

As a cloud provider, Scaleway must maintain strict security standards across its infrastructure, software and development ecosystem.

Over time, our main GitHub organization has accumulated projects that are no longer actively developed or maintained. While these repositories may still have historical or technical value, keeping them alongside active projects introduces unnecessary complexity and security exposure.

We created `scaleway-archives` to address three objectives:

- **Reduce our attack surface:** Minimize the number of accounts, permissions and repositories exposed within our main GitHub organization.
- **Enforce least-privilege access:** Maintain a separate organization with significantly restricted write access and a limited number of authorized maintainers.
- **Clarify project lifecycle:** Clearly distinguish actively maintained Scaleway projects from discontinued or historical software.

## Why not simply archive repositories on GitHub ?

GitHub provides a built-in repository archiving feature that makes repositories read-only.

While useful, this mechanism alone does not provide the organizational isolation we want.

Archiving a repository within our main organization would still leave it under the same organizational boundary, with shared membership, governance and administrative controls.

Moving repositories to a dedicated organization allows us to:

- Separate active development from historical repositories.
- Apply stricter organization-level access policies.
- Reduce the number of people with administrative or write permissions.
- Simplify governance and security reviews of our main organization.
- Preserve repository history without keeping legacy projects in our active development environment.

**Repository archiving controls the lifecycle of a project. Organizational separation controls its security boundary. We need both.**

## Repository lifecycle

Repositories transferred to this organization are considered discontinued.

They are preserved as-is, without any commitment to ongoing maintenance, security updates, bug fixes or support.

Unless explicitly stated otherwise:

- Repositories are archived and read-only.
- No new features or fixes will be developed.
- Security vulnerabilities may remain unresolved.
- Issues and pull requests are not actively monitored.
- Production usage is not supported.

If a project becomes actively maintained again, its ownership, security posture and maintenance model must be reviewed before it can return to the main Scaleway organization.

## Security and usage

**All software hosted in this organization is provided for historical and reference purposes only.**

These repositories MUST NOT be used in production environments.

For actively maintained Scaleway projects, please visit our main GitHub organization : **https://github.com/scaleway**

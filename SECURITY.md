# Security Policy

## Supported Versions

Only the latest version on the `main` branch receives security updates.

## Reporting a Vulnerability

Do not report security vulnerabilities through public issues.

Use GitHub's private vulnerability reporting:
**Security → Report a vulnerability** on this repository.

Include:

- a description of the vulnerability
- the affected page or file
- reproduction steps or a proof of concept
- any suggested mitigation

You will receive a response within a reasonable timeframe.

## Scope of Security Review

Areas that are security-sensitive in this repository:

- **Policy content accuracy**: Privacy and terms pages must accurately
  reflect the project's data handling practices.
- **External links**: Links within policy pages must point to
  legitimate, expected destinations.
- **GitHub Pages deployment**: The deployment configuration must not
  expose unintended content.

## Secrets Handling

This repository does not contain application secrets. Policy pages
are static HTML served via GitHub Pages.

## Security Testing Expectations

- Verify that no sensitive information is included in policy pages.
- Verify that external links are valid and point to expected destinations.

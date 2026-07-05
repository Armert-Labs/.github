# Security Policy

## Supported versions

Security fixes are provided for the **latest release** on the default branch (`main`) of each active Armert Labs repository.

| Repository | Security-sensitive areas |
| --- | --- |
| [bist-data-service](https://github.com/Armert-Labs/bist-data-service) | API key auth, rate limits, webhook URLs, Redis exposure |
| [cursor-plugin](https://github.com/Armert-Labs/cursor-plugin) | Agent invocation, subprocess execution, credential handling |
| [python-egitimi](https://github.com/Armert-Labs/python-egitimi) | Client-side execution (Pyodide), content injection |

## Reporting a vulnerability

**Do not open public GitHub issues for security vulnerabilities.**

Email **mertcan@armert.com.tr** with:

1. Affected repository and version/commit
2. Steps to reproduce
3. Impact assessment (if known)
4. Suggested fix (optional)

We aim to acknowledge reports within **48 hours** and provide a remediation timeline when confirmed.

## Safe harbor

Good-faith security research that respects user data and avoids service disruption will not result in legal action from Armert Labs.

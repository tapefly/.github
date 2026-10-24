# TapeFly Security Policy

## Report privately

Do not open a public issue for a vulnerability. Use GitHub private vulnerability
reporting on the affected repository:

https://github.com/tapefly/tapefly/security/advisories/new

Include the affected commit or URL, reproduction steps, expected and actual
behavior, and whether wallet funds, private data or public history are at risk.

## Scope

In scope:

- the TapeFly Next.js application and API;
- deterministic simulation, compilation and replay code;
- transaction construction and on-chain verification;
- committed ledgers and proof artifacts.

Out of scope:

- TapeOut contracts, BNB Chain, X Layer and wallet providers;
- third-party infrastructure;
- denial-of-service or social-engineering attacks against other services.

Never test against another user's funds, publish personal information, or disclose
an exploitable finding before a fix has been coordinated.

# Security Policy

## Reporting a vulnerability

Report suspected vulnerabilities through GitHub private vulnerability
reporting on this repository. Please do not open a public issue for security
reports.

Include steps to reproduce and the impact you observed. Expect an
acknowledgement within a few business days.

## Scope

This package scores sentiment in Reddit discussion threads. It has no server
component and stores no credentials. The optional `fetch` extra talks to the
ReleaseTrain HTTP API; the core scoring functions take plain Python data and
make no network calls.

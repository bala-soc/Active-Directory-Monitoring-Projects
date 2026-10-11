# Active Directory Monitoring Projects

Active Directory monitoring exercises with a security-operations focus: authentication visibility, suspicious sign-in patterns, account changes, and escalation-ready investigation notes.

## Use-Case Areas
- Authentication and account logon monitoring
- Repeated failed logons and unusual sign-in patterns
- Privileged-group membership changes
- Account creation, disablement, and lockout events
- Dashboards and alerting for security-relevant events

## Tools and Data Sources
Windows Security Event Logs, Active Directory Domain Services in a controlled lab, Splunk, and PowerShell. Use other monitoring platforms only when you have implemented and documented a working integration.

## Recommended Case-Study Format
1. Scenario and objective
2. Lab architecture and event sources
3. Relevant Windows Event IDs and fields
4. Query, correlation logic, or alert rule
5. Test procedure and observed output
6. False positives, investigation notes, and response recommendations

## Scope
Prioritise a small number of validated security-monitoring cases over a broad list of monitoring products. Add screenshots, queries, and results only after testing them in your own lab.

> Use a lab domain or authorised environment. Redact usernames, hostnames, IP addresses, and other sensitive details where needed.

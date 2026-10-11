# Active Directory Monitoring Projects

**Focus:** Authentication monitoring • Account changes • Windows Security Events • Alert investigation

This repository is intended to document Active Directory monitoring from a security-operations perspective. Prioritise tested security use cases over a long list of monitoring platforms.

## Suggested SOC Use Cases
- Repeated failed logons and account lockouts
- Successful logons following multiple failures
- Account creation, disablement, or password changes
- Privileged-group membership changes
- Unusual logon times or source hosts, where the lab data supports that analysis

## Lab and Data Sources
Use a controlled lab domain or authorised Windows event logs. Record the operating system, logging configuration, event IDs and fields used, and any collection or SIEM integrations actually configured.

## Case Study Checklist
1. Scenario and investigation objective
2. Event IDs and fields examined
3. Query or detection rule
4. Test method and observed results
5. Analyst conclusion and potential false positives
6. Recommended response and limitations

## Tools
Windows Security logs, Active Directory Domain Services, PowerShell, and Splunk or other tools when implemented in the documented lab.

> Document only integrations you have configured and tested. Redact sensitive account, domain, host, and network information.

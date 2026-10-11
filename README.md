# Active Directory Monitoring Projects

**Focus:** Authentication monitoring • Account changes • Privileged-group activity • Alert investigation

SOC-focused exercises for monitoring Active Directory and Windows security events.

## Use Cases
- Repeated failed logons and account lockouts
- Successful logons following multiple failures
- Account creation, disablement, or password changes
- Privileged-group membership changes
- Unusual logon times or source hosts when supported by the lab data

## Lab and Data Sources
Use a controlled lab domain or authorised Windows event logs. Record the Windows version, audit policy, relevant event IDs and fields, and any SIEM or collection integrations configured.

## Investigation Workflow
1. Define the scenario and detection objective.
2. Identify the event IDs, fields, and time range.
3. Write and test the query or detection rule.
4. Review observed events and potential false positives.
5. Document evidence, conclusion, and recommended response.

## Tools
Windows Security logs, Active Directory Domain Services, PowerShell, and Splunk or other platforms where implemented.

## Safe Practice
Document only integrations actually configured and tested. Redact account names, domains, hostnames, and network details.
# Active Directory Monitoring Projects

**Target role:** SOC Analyst L1  
**Focus:** Authentication monitoring • Account changes • Privileged-group activity • Alert investigation

This repository covers Active Directory monitoring from a security-operations perspective.

## Project Index
The use cases below are investigation scenarios to develop in a controlled lab.

1. Repeated failed logons and account lockouts
2. Successful logons following multiple failures
3. Account creation, disablement, and password changes
4. Privileged-group membership changes
5. Unusual logon times or source hosts, when supported by available data

## Lab Setup
Use a controlled lab domain or authorised Windows security logs. Document the operating system, audit policy, event IDs, fields, and any collection or SIEM integrations actually configured.

## Investigation Workflow
1. Define the scenario and detection objective.
2. Identify event IDs, fields, and the relevant time range.
3. Build and test the query or detection rule.
4. Review observed events and possible false positives.
5. Document findings, evidence, response options, and limitations.

## Tools
Windows Security logs, Active Directory Domain Services, PowerShell, and Splunk or other platforms when implemented in the lab.

## Safe Practice
Document only integrations that have actually been configured and tested. Redact account names, domains, hostnames, and network details.

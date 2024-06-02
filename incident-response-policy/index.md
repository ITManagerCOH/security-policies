---
title: Incident response policy
slug: incident-response
policy: true
faq: false
weight: 5
---

### Context

GEOGO’s customers are dependent on our services operating as normal. Proper detection and response to incidents that may impact the integrity, confidentiality or availability of services and data is critical to the operation of GEOGO.

The following minimum standards apply to GEOGO’s assets as managed by employees, contractors and vendors. These recommendations represent the recommended minimum efforts necessary for incident detection and response.

### Incident detection

An incident could be detected internally by an employee in their course of work, by an employee or vendor doing a review of GEOGO’s security posture, or an external third party reporting a potential vulnerability to us.

If you see something, say something. All GEOGO employees should immediately report suspected security incidents or suspicious activity that occurs at GEOGO, including but not limited to security incidents, physical injury, theft, property damage, denial of service attacks, threats, harassment, abuse of individual user accounts, forgery and misrepresentation. Suspicious activity can be reported to the Discord channel #incident-response, or, for potentially sensitive incidents, to the Security Review Team or to the Chief Information Officer (CIO). Violations of the [Code of Conduct](http://go/code-of-conduct) should be reported to the Chief Information Officer (CIO).

All employees should watch for potentially suspicious activities, including:

* Warnings from antivirus tools
* Unexpected system reboots and/or sudden degradation of system performance
* Password reset notifications
* Modification or defacement of websites
* New open network ports on a system

GEOGO regularly reviews logs to detect and track attempted intrusions and other suspicious activity. These include git, cloud, networking, SaaS tool, and other infrastructure logs.

The Security Review Team:

* Ensures that a very high level of logging is enabled
* Checks logs regularly for suspicious activities and entries
* Looks for missing time spans in logs
* Checks for repeated login failures or account lockouts
* Investigates unexpected system reboots

GEOGO’s Security Review Team reviews and responds to potential third-party reports of security issues to [security@geogo.in](mailto:security@geogo.in) promptly.

### Incident response and remediation

If a suspected incident is detected, it should be responded to following the [Incident response process](/security-policies/incident-response-process/).

We respond to reported incidents, and resolve and determine impact as soon as possible. We aim to remediate incidents as soon as possible.

Confirmed incidents may be disclosed publicly per our [disclosure policy](/security-policies/incident-disclosure/).

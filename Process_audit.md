SUMMARY :

This document presents the findings from a review of active processes and system services on a Linux server to identify unnecessary or potentially risky components.

AUDIT FOCUS :

The review focused on:

Active system processes .
2.Enabled and running services

KEY OBSERVATIONS :

1.Running unnecessary services increases the system’s attack surface.

2.Services running with elevated privileges present higher risk if compromised.

3.Lack of service visibility can delay detection of malicious activity.

RISK ASSESSMENT :

Unmonitored or unnecessary processes can be exploited to:

Gain persistent access

Execute unauthorized code

Facilitate lateral movement within the system

SECURITY IMPACT :

Compromised services may allow attackers to maintain long-term access, disrupt system availability, or exfiltrate sensitive data.

Mitigation Recommendations

Disable non-essential services

Restrict service permissions where possible

Monitor running processes continuously

Review service configurations regularly

SUMMARY :

This document presents the findings from a review of user accounts and previlaged access ona linux server, with the objective of identifying access-related security risks.

AUDIT FOCUS :

The review focused on:

  1.User account presence on the system
  
  2.Assignment of privilaged access

KEY OBSERVATIONS :

User accounts were reviewed to assess access levels and privilege distribution.

Privileged access was present for a limited set of users, reducing immediate risk.

Without periodic review, privileged access may expand over time, increasing exposure.

RISK ASSESSMENT :

Improper management of user privileges can allow attackers to:

  Escalate access after initial compromise

  Gain administrative control of the system

  Access or manipulate sensitive system resources

Privilege-related issues often lead to high-impact security incidents.

SECURITY IMPACT :

If a privileged account is compromised, the attacker can bypass multiple security controls, making detection and containment significantly more difficult.

MITIGATION TECHNIQUES :

  Enforce strict least-privilege policies

  Review privileged access on a scheduled basis

  Remove unused or unnecessary user accounts

  Monitor privilege changes through logging and alerts


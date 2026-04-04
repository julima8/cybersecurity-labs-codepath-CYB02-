# Lessons Learned – Phishing Incident (IR-2023-001)

## Incident Summary

A phishing email was delivered to a user and contained a malicious attachment. When the attachment was opened, ransomware was executed on the system, leading to a system compromise. The incident was identified, analyzed, and resolved through isolation and remediation actions.

## Tactics, Techniques, and Procedures (TTPs)

The attacker used a phishing email with a malicious attachment to gain initial access. Once the attachment was opened, ransomware was executed on the system, encrypting data and compromising the machine. This technique relies on social engineering to trick the user into executing malicious content.

## Response Effectiveness

The incident response was effective in identifying and containing the threat. The affected system was quickly isolated, and the malware was removed before further damage could occur. The use of external tools such as VirusTotal and AbuseIPDB helped validate the indicators of compromise and supported the investigation process.

## Areas for Improvement

Although the incident was handled effectively, improvements could be made in early detection. Enhanced email filtering and user awareness could help prevent users from interacting with malicious attachments. Faster detection mechanisms could reduce response time.

## Future Improvements

To prevent similar incidents, the organization should implement stronger email security controls, including advanced phishing detection. Regular cybersecurity awareness training should be provided to users. Additionally, endpoint protection and monitoring tools should be enhanced to detect threats earlier.

## Incident Classification

This incident is classified as a **True Positive**, as it represents a confirmed security event involving ransomware delivered through a phishing attack.

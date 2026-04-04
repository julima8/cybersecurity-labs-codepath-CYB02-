# Incident Report – Phishing Attack (IR-2023-001)

## Incident Summary
A phishing email was sent to a user containing a malicious attachment. When opened, the attachment executed ransomware on the user's system, compromising the machine.

## Indicators of Compromise (IoCs)

- **Malware Hash (MD5):** 44d88612fea8a8f36de82e1278abb02f  
- **Malicious IP:** 45[.]142[.]166[.]228  

## Analysis

The malware hash was analyzed using VirusTotal and was flagged as malicious by 67 security vendors, indicating a high likelihood of ransomware.

The IP address was analyzed using AbuseIPDB. It showed low confidence of abuse (0%), but is hosted in a data center, which can still be associated with malicious activity.

## Response Actions

- The affected system was isolated from the network  
- Malware was removed  
- System was restored and verified  
- Indicators of compromise were documented and analyzed  

## Status
Closed

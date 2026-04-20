# Microsoft Sentinel Detection Rules

A collection of Microsoft Sentinel Analytic Rules built and maintained as ARM templates.

## Contents

### Data connectors
You need Entra ID, Azure Actiivty, Azure key vault, Defender XDR and Windows Security Events via AMA

### Analytic Rules (20)
Detection rules covering identity, credential access, persistence, and defense evasion:

- Admin promotion after Role Management Application Permission Grant
- Authentication Methods Changed for Privileged Account
- Clearing of Forensic Evidence from Event Logs (wevtutil)
- Conditional Access Dynamic Group Exclusion Changes
- Conditional Access Policy Disabled or Deleted
- Diagnostic Settings Deleted — Possible Log Blinding
- Failed Access Attempts on Azure Key Vault
- First Access Credential Added to Application or Service Principal
- Imminent Ransomware
- LSASS Credential Dumping with Procdump
- MFA Spamming Followed by Successful Login
- Microsoft Defender Threat Intelligence Analytics
- Modified Domain Federation Trust Settings
- Multi-Factor Authentication Disabled for a User
- Multiple Failed Logons Followed by a Success
- Privileged Role Assigned Outside PIM
- Suspicious Granting of Permissions to an Account
- Suspicious Number of Resource Creation or Deployment Activities
- Unusual Volume of File Deletion by User

### Workbooks (1)
- Data Collection Health Monitoring

## Deployment
All rules are packaged as ARM templates and can be deployed directly to a Microsoft Sentinel workspace.

## Validation
All content is automatically validated on every push via GitHub Actions.

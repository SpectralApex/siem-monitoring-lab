# PowerShell Abuse Detection Rule

## Detection Objective

Detect suspicious PowerShell execution activity.

## Indicators

- Encoded PowerShell commands
- Hidden execution flags
- DownloadString usage
- Invoke-Expression usage

## Example Suspicious Command

```powershell
powershell.exe -EncodedCommand <base64>
```

## MITRE ATT&CK Mapping

- T1059.001 — PowerShell

## Response Actions

- Generate SIEM alert
- Isolate affected host
- Review process tree
- Investigate persistence mechanisms

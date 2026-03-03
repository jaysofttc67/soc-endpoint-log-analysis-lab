Case 001 – Notepad Launched from PowerShell

Lab Environment: Windows 10 VM (VirtualBox) – Sysmon Configured
Date: 3/02/2026
Severity: Low

Summary

A user-initiated PowerShell session launched notepad.exe within the Windows lab environment.

Evidence

Sysmon Event ID: 1 (Process Creation)

Image: C:\Windows\System32\notepad.exe

ParentImage: C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe

User: DESKTOP-OBROKSC\jaylab

Analysis

The parent-child relationship indicates manual execution of notepad.exe from an interactive PowerShell session. No encoded commands, suspicious flags, or abnormal execution paths observed.

Impact

No malicious activity detected. Behavior consistent with user testing.

Actions Taken

Validated process origin and user context. Documented as benign activity.

Conclusion

This event represents normal user-driven process execution and does not require escalation.

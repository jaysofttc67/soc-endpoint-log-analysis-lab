Windows Endpoint Monitoring Lab (Sysmon)
Overview

This repository documents my home SOC lab focused on Windows endpoint monitoring using Sysmon and Event Viewer. Each case simulates a Tier-1 SOC investigation and is written in ticket-style format.

Objectives

Generate controlled endpoint activity

Analyze Sysmon Event ID 1 (Process Creation)

Identify parent-child process relationships

Classify benign vs suspicious behavior

Document findings in structured SOC reports

Tools Used

Windows 10 VM (VirtualBox)

Sysmon

Event Viewer

PowerShell

Lab Structure

incident-reports → Individual SOC-style case documentation

screenshots → Supporting evidence for each case

Current Cases

- [Case 001 – Notepad Launched from PowerShell](incident-reports/Case-001_Notepad_From_PowerShell.md)

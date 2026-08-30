# linux-log-forensics-lab
# Linux Log Forensics & Incident Investigation Lab

## Overview

This project documents a Linux security investigation performed as part of my SOC Analyst training at TechBizAcademy.

The activity focused on understanding Linux log files and using authentication and system logs to investigate security-related events. A controlled authentication-failure scenario was used to generate relevant log entries, which were then analyzed to understand the sequence of events.

## Objectives

- Understand the Linux command-line environment
- Learn the purpose of common Linux log files
- Analyze authentication and system logs
- Identify failed and successful authentication events
- Understand PAM-related authentication messages
- Use command-line tools to filter and investigate logs
- Reconstruct a basic incident timeline
- Understand the importance of logs in SOC investigations

## Environment

- Linux
- Kali Linux
- Virtual machine lab environment
- Linux authentication and system logs

## Log Files Analyzed

The investigation focused primarily on:

- `/var/log/auth.log`
- `/var/log/syslog`

These logs were reviewed to understand authentication activity and system events.

## Tools and Commands

The investigation used standard Linux command-line tools, including:

```bash
grep
tail
less
cat

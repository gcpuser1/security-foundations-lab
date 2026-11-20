# 08 · Windows and Active Directory

**Priority:** High · **Effort:** ~2 week(s) · **Status:** not started

## Why this matters

Most corporate networks run on Active Directory. Understanding it is understanding how large organisations manage identity.

## 1. Stumble first (before any reading)

Log in to a Windows machine on a domain and run `whoami /groups`. Explain where each group came from before you read about AD.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] Local vs domain accounts
- [ ] Domains, forests, OUs
- [ ] Group Policy
- [ ] Kerberos and NTLM at concept level
- [ ] Windows event logs

## 3. Build yourself

A small AD lab in VMs: one domain controller plus one client.

## 4. Practise on

HTB Academy or TryHackMe AD fundamentals.

## 5. Gate check

Explain Kerberos authentication step by step.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [Microsoft: Kerberos authentication overview](https://learn.microsoft.com/en-us/windows-server/security/kerberos/kerberos-authentication-overview)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

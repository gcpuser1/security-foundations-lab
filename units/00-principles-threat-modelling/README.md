# 00 · Security principles and threat modelling

**Priority:** High · **Effort:** ~1 week(s) · **Status:** not started

## Why this matters

Every weakness is a broken assumption about trust. Before learning any system, learn the lens: what does this system assume, and who trusts whom?

## 1. Stumble first (before any reading)

Draw your December agent on paper: every component, every arrow. Before reading anything, mark where you think an outsider could influence it. Keep the drawing; you will redo it at the end of this unit.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] CIA triad (confidentiality, integrity, availability)
- [ ] Least privilege and defence in depth
- [ ] Trust boundaries and attack surface
- [ ] STRIDE threat categories
- [ ] Vulnerability, threat and control

## 3. Build yourself

A threat model of your December agent (data-flow diagram + STRIDE table) in `writeups/`.

## 4. Practise on

Threat Modeling Manifesto worked examples.

## 5. Gate check

Name three trust boundaries in your agent and what guards each one.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [OWASP Threat Modeling](https://owasp.org/www-community/Threat_Modeling)
- [Threat Modeling Manifesto](https://www.threatmodelingmanifesto.org/)
- [CyBOK (free body of knowledge)](https://www.cybok.org/)
- [UK Computer Misuse Act 1990](https://www.legislation.gov.uk/ukpga/1990/18/contents)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

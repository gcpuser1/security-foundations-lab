# 11 · Cloud and Kubernetes (your lever)

**Priority:** High · **Effort:** ~2 week(s) · **Status:** not started

## Why this matters

You already run AWS and EKS daily. This unit turns that familiarity into a deep understanding of how cloud trust actually works.

## 1. Stumble first (before any reading)

Take one IAM policy from your own sandbox. Predict, line by line, which API calls it allows. Then test with the IAM policy simulator.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] IAM policy evaluation logic
- [ ] Role chaining and federation
- [ ] VPC design and segmentation
- [ ] EKS, IRSA and pod identity
- [ ] Guardrails: SCPs, permission boundaries

## 3. Build yourself

A dedicated AWS sandbox account (never a work account).

## 4. Practise on

flAWS.cloud, CloudGoat, Kubernetes Goat.

## 5. Gate check

Explain one IAM privilege path and the guardrail that closes it.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [flAWS.cloud](http://flaws.cloud/)
- [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat)
- [Kubernetes Goat](https://madhuakula.com/kubernetes-goat/)
- [Hacking the Cloud](https://hackingthe.cloud/)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

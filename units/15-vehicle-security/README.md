# 15 · Vehicle security

**Priority:** High · **Effort:** ~2 week(s) · **Status:** not started

## Why this matters

A modern car is a network of computers on wheels. Its internal bus was designed long before security mattered.

## 1. Stumble first (before any reading)

Before reading anything: how many computers do you think are in your Polestar, and how do you think they talk to each other? Write it down, then check.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] ECUs and in-vehicle networks
- [ ] The CAN bus and why it has no sender authentication
- [ ] Keyless entry at concept level
- [ ] Over-the-air updates

## 3. Build yourself

A virtual CAN bus on Linux (vcan) with the ICSim instrument-cluster simulator.

## 4. Practise on

ICSim exercises alongside The Car Hacker's Handbook.

## 5. Gate check

Explain why CAN messages carry no sender authentication, and how modern cars compensate.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [ICSim](https://github.com/zombieCraig/ICSim)
- [The Car Hacker's Handbook (No Starch)](https://nostarch.com/carhacking)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

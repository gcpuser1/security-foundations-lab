# 03 · OS internals: processes, syscalls, permissions, isolation

**Priority:** High · **Effort:** ~3 week(s) · **Status:** not started

## Why this matters

The kernel decides what every program may do. Containers, sandboxes and privilege all come down to a few kernel mechanisms.

## 1. Stumble first (before any reading)

Start a container and run `ps aux` inside it, then on the host. Explain why the lists differ, before reading about namespaces.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] fork/exec and the syscall boundary
- [ ] Users, UIDs, capabilities, PAM
- [ ] Namespaces, cgroups, seccomp
- [ ] What a container really is
- [ ] /proc and strace

## 3. Build yourself

A tiny container runtime in Go using namespaces and cgroups.

## 4. Practise on

pwn.college Intro to Cybersecurity dojo.

## 5. Gate check

Explain what a container really isolates, and what it doesn't.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [OSTEP (free)](https://pages.cs.wisc.edu/~remzi/OSTEP/)
- [MIT 6.1810 Operating System Engineering](https://pdos.csail.mit.edu/6.1810/)
- [namespaces(7)](https://man7.org/linux/man-pages/man7/namespaces.7.html)
- [Julia Evans zines](https://wizardzines.com/)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

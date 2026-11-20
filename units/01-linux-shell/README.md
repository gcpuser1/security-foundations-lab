# 01 · Linux and the shell in depth

**Priority:** High · **Effort:** ~2 week(s) · **Status:** not started

## Why this matters

Almost every server, container and network device you will touch runs on Linux. Fluency here is the floor everything else stands on.

## 1. Stumble first (before any reading)

Run `ls -l /usr/bin/passwd`. Explain why an ordinary user can change their own password when the password file is owned by root. Write your guess before looking anything up.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] Files, inodes, permissions, ownership
- [ ] Processes, signals, job control
- [ ] Pipes, redirection, environment variables
- [ ] Package managers, services, systemd
- [ ] Reading man pages instead of searching

## 3. Build yourself

Your own dotfiles repo with a few shell functions you actually use.

## 4. Practise on

pwn.college Linux Luminarium; OverTheWire Bandit as a warm-up.

## 5. Gate check

Dojo complete.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [pwn.college](https://pwn.college/)
- [OverTheWire wargames](https://overthewire.org/wargames/)
- [Linux man pages (man7.org)](https://man7.org/linux/man-pages/)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

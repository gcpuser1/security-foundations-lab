# 06 · Cryptography

**Priority:** High · **Effort:** ~2 week(s) · **Status:** not started

## Why this matters

Crypto is why TLS, passwords and Wi-Fi security work at all. Most real failures are misuse, not broken maths.

## 1. Stumble first (before any reading)

Hash the same password twice with SHA-256, then with bcrypt. Explain why the bcrypt outputs differ and the SHA-256 ones don't.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] Hashing and password storage
- [ ] Symmetric vs asymmetric encryption
- [ ] Key exchange and forward secrecy
- [ ] MACs and authenticated encryption
- [ ] Randomness and why it matters

## 3. Build yourself

Correct use of hashing, HMAC and AES-GCM in Python.

## 4. Practise on

Cryptopals sets 1-2.

## 5. Gate check

Explain why modern TLS gives forward secrecy.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [Cryptopals](https://cryptopals.com/)
- [Aumasson, Serious Cryptography (No Starch)](https://nostarch.com/serious-cryptography-2nd-edition)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

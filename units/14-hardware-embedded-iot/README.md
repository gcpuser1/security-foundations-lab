# 14 · Hardware, embedded and IoT

**Priority:** High · **Effort:** ~3 week(s) · **Status:** not started

## Why this matters

Small networked devices run everywhere and are often the least protected. Your electronics background is a direct advantage.

## 1. Stumble first (before any reading)

Look at any smart device at home. List every way it communicates (Wi-Fi, Bluetooth, cloud app) before reading anything about IoT.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] Microcontrollers and firmware
- [ ] Boot process and chain of trust
- [ ] Debug interfaces (UART, JTAG) at concept level
- [ ] How small devices talk: MQTT
- [ ] OWASP IoT Top 10

## 3. Build yourself

An ESP32 or Raspberry Pi sensor publishing to your own MQTT broker, watched in Wireshark.

## 4. Practise on

Microcorruption (embedded CTF).

## 5. Gate check

Explain how a device boots its firmware and where its chain of trust starts.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [Microcorruption](https://microcorruption.com/)
- [OWASP IoT project](https://owasp.org/www-project-internet-of-things/)
- [The Hardware Hacking Handbook (No Starch)](https://nostarch.com/hardwarehacking)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

# 02 · C, memory and assembly basics

**Priority:** High · **Effort:** ~2 week(s) · **Status:** not started

## Why this matters

Go and Python hide memory from you. To understand how programs really fail, you need to see the stack, the heap and the instructions.

## 1. Stumble first (before any reading)

Write a 10-line C program with a function that returns a pointer to a local variable. Predict what happens, run it, then explain the result.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] Pointers, arrays and strings in C
- [ ] Stack frames, calling conventions, the heap
- [ ] Virtual memory layout of a process
- [ ] Reading x86-64 assembly
- [ ] Using gdb to inspect a running program

## 3. Build yourself

Small C programs, each inspected in gdb, with a memory-layout sketch per program.

## 4. Practise on

pwn.college fundamentals dojos.

## 5. Gate check

Draw a running program's memory layout from memory.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [pwn.college](https://pwn.college/)
- [GDB documentation](https://sourceware.org/gdb/documentation/)
- [OSTEP: address spaces chapters](https://pages.cs.wisc.edu/~remzi/OSTEP/)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

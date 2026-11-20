# 07 · Web, identity and databases

**Priority:** High · **Effort:** ~4 week(s) · **Status:** not started

## Why this matters

Web apps are where users, identity and data meet. Most web vulnerabilities come from mixing up data and code, or trusting the client.

## 1. Stumble first (before any reading)

Open your browser dev tools on any site you use. Find the cookie that keeps you logged in, and explain what would happen if someone else had it.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] Request lifecycle, cookies, sessions, same-origin policy
- [ ] Authentication vs authorisation, OAuth 2.0/OIDC, JWTs
- [ ] How a SQL engine parses and plans a query
- [ ] Transactions, indexes, parameterised queries
- [ ] OWASP Top 10 vulnerability classes

## 3. Build yourself

An app with Postgres behind OIDC login, deployed with Terraform to your own AWS account.

## 4. Practise on

PortSwigger Web Security Academy, Apprentice then Practitioner labs.

## 5. Gate check

State the root cause of each vulnerability class you solved.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [CMU 15-445 Database Systems](https://15445.courses.cs.cmu.edu/)
- [Designing Data-Intensive Applications](https://dataintensive.net/)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

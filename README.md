# Security Foundations Lab

A gate-driven, practice-first programme to understand systems from the radio waves up: how they work, how they fail, and how to fix them.

- **Main path:** 18 units, roughly 42 weeks of effort, no fixed dates.
- **Optional:** 4 one-week overviews after the capstone.
- **Starts after:** the agentic AI programme, then ML maths (`ai-math-lab`).
- **Living plan:** [Security Foundations Curriculum doc](https://claude.ai/artifact/27ViEeBTpZMbhN9BE98ajT).

## How every unit runs

1. **Stumble:** attempt the problem cold, 60–90 minutes, and write your guess first.
2. **Why:** reason from first principles. What does this system assume? Who trusts whom?
3. **Build:** stand the system up yourself.
4. **Practise:** on an authorised platform only.
5. **Teach-back:** a write-up with reasoning and dead ends in `writeups/`.
6. **Gate:** explain it to Claude with no notes. Don't start the next unit until you pass.

## Rules

- **Gate before progress.** Week counts are effort estimates, never deadlines.
- **AI is a tutor, never a solver.** No AI on platform challenges, and one AI-free session a week. Verify everything it says.
- **Legal.** Practise only on authorised platforms and in your own lab or accounts. The UK Computer Misuse Act covers everything else, including employer systems outside an authorised engagement.

## Mindset principles

Taken from *Who Am I* and *Mr. Robot*:

1. **No system is safe.** Find the assumption and where it breaks.
2. **People are the weakest link.** Study the human process around every system, from the defender's side.
3. **Misdirection.** Check what's actually there (packets, logs, configs), not what a dashboard says.
4. **Depth beats tools.** Understand the system before reaching for a tool.

## Weekly rhythm

| Slot | What | Time |
| --- | --- | --- |
| Mon–Thu evenings | Concepts and building | ~1 h each |
| Weekend | Platform practice | 3–4 h |
| Sunday | Write-up and gate check with Claude | 30 min |

## Main path

| # | Unit | Priority | Weeks | Gate passed |
| --- | --- | --- | --- | --- |
| 00 | [Security principles and threat modelling](units/00-principles-threat-modelling/README.md) | High | ~1 | ⬜ |
| 01 | [Linux and the shell in depth](units/01-linux-shell/README.md) | High | ~2 | ⬜ |
| 02 | [C, memory and assembly basics](units/02-c-memory-assembly/README.md) | High | ~2 | ⬜ |
| 03 | [OS internals: processes, syscalls, permissions, isolation](units/03-os-internals/README.md) | High | ~3 | ⬜ |
| 04 | [Radio and telecoms](units/04-radio-telecoms/README.md) | High (added) | ~2 | ⬜ |
| 05 | [Networking, layer 2 to layer 7](units/05-networking/README.md) | High | ~3 | ⬜ |
| 06 | [Cryptography](units/06-cryptography/README.md) | High | ~2 | ⬜ |
| 07 | [Web, identity and databases](units/07-web-identity-databases/README.md) | High | ~4 | ⬜ |
| 08 | [Windows and Active Directory](units/08-windows-active-directory/README.md) | High | ~2 | ⬜ |
| 09 | [Methodology, detection and reporting](units/09-methodology-detection-reporting/README.md) | High | ~2 | ⬜ |
| 10 | [Forensics and incident response (DFIR)](units/10-dfir/README.md) | High (added) | ~3 | ⬜ |
| 11 | [Cloud and Kubernetes (your lever)](units/11-cloud-kubernetes/README.md) | High | ~2 | ⬜ |
| 12 | [Software supply chain and secure development](units/12-software-supply-chain/README.md) | High (added) | ~2 | ⬜ |
| 13 | [Large systems and outage debugging](units/13-large-systems-outages/README.md) | High (added) | ~4 | ⬜ |
| 14 | [Hardware, embedded and IoT](units/14-hardware-embedded-iot/README.md) | High | ~3 | ⬜ |
| 15 | [Vehicle security](units/15-vehicle-security/README.md) | High | ~2 | ⬜ |
| 16 | [OSINT and social engineering](units/16-osint-social-engineering/README.md) | High | ~2 | ⬜ |
| 17 | [Capstone: AI agent security](units/17-capstone-ai-agent-security/README.md) | High | ~1 | ⬜ |

## Optional (low priority)

| # | Unit | Priority | Weeks | Gate passed |
| --- | --- | --- | --- | --- |
| 18 | [Malware fundamentals](units/optional/18-malware-fundamentals/README.md) | Low | ~1 | ⬜ |
| 19 | [Industrial and OT security](units/optional/19-ot-ics-security/README.md) | Low | ~1 | ⬜ |
| 20 | [Mobile security](units/optional/20-mobile-security/README.md) | Low | ~1 | ⬜ |
| 21 | [Governance, risk, law and privacy](units/optional/21-governance-risk-privacy/README.md) | Low | ~1 | ⬜ |

## Repo layout

```
units/<nn-unit>/README.md   concepts, stumble problem, build, practise, gate, links
units/<nn-unit>/notes.md    your guesses and notes for that unit
units/optional/             low-priority overviews
writeups/                   one file per solve, from templates/writeup.md
templates/                  write-up and gate-check templates
PROGRESS.md                 gate log
CLAUDE.md                   how Claude should tutor you in this repo
```

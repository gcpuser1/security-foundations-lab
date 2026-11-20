# 12 · Software supply chain and secure development

**Priority:** High (added) · **Effort:** ~2 week(s) · **Status:** not started

## Why this matters

Code passes through many hands between commit and production. Your CI/CD experience makes this a natural strength.

## 1. Stumble first (before any reading)

Pick one of your own pipelines. List every system that could change what ends up in production. Count them before reading about supply chains.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] CI/CD trust chains
- [ ] SBOMs
- [ ] Artefact signing
- [ ] SLSA levels
- [ ] Least-privilege runners and secrets

## 3. Build yourself

A hardened GitLab pipeline: signed artefacts (Sigstore), SBOM generation, least-privilege runners.

## 4. Practise on

CI/CD Goat.

## 5. Gate check

Trace your pipeline's trust chain from commit to running pod.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [SLSA](https://slsa.dev/)
- [Sigstore](https://www.sigstore.dev/)
- [CI/CD Goat](https://github.com/cider-security-research/cicd-goat)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

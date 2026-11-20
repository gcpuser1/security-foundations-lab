# 13 · Large systems and outage debugging

**Priority:** High (added) · **Effort:** ~4 week(s) · **Status:** not started

## Why this matters

Your stated goal: walk into any company's outage and find the root cause. That needs distributed-systems depth plus a debugging method.

## 1. Stumble first (before any reading)

Read only the first paragraph of a public postmortem (the symptoms). Write your own hypothesis for the root cause before reading the rest.

Write your guess in `notes.md` before you look anything up.

## 2. Concepts covered

- [ ] BGP and internet routing
- [ ] Load balancing and CDNs
- [ ] Caching, queues, replication, consistency
- [ ] Failure modes: retry storms, cascading failure, config pushes
- [ ] Debugging method: hypothesis, isolate, measure, confirm

## 3. Build yourself

BGP between Linux namespaces with FRRouting, a load balancer in front, and chaos experiments on your own cluster.

## 4. Practise on

Recreate one public postmortem a week (Cloudflare, AWS); SadServers scenarios.

## 5. Gate check

Debug a recreated outage to root cause without looking at the answer.

Explain it to Claude with no notes. Don't start the next unit until you pass.

## Read and reference

- [Google SRE books (free)](https://sre.google/books/)
- [Designing Data-Intensive Applications](https://dataintensive.net/)
- [Cloudflare postmortems](https://blog.cloudflare.com/tag/post-mortem/)
- [AWS post-event summaries](https://aws.amazon.com/premiumsupport/technology/pes/)
- [danluu/post-mortems](https://github.com/danluu/post-mortems)
- [SadServers](https://sadservers.com/)
- [FRRouting](https://frrouting.org/)

## Write-ups

Add each solve to `../../writeups/` using `templates/writeup.md`.

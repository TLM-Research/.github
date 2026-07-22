# TLM Research

**Open research on temporal market design for decentralized execution — with Ethereum as the initial platform.**

---

## Mission

TLM Research studies **Temporal Liquidity** — the economically meaningful *temporal* characteristics of execution demand (when, in what order, and how predictably execution is needed) — and investigates whether decentralized protocols should make some of this information protocol-visible, to improve coordination while preserving neutrality and decentralization.

The work is **model-first**: concepts, representations, and evaluation criteria come first. That is the *first phase* — **market-mechanism design is an explicit next phase**, in which we develop and evaluate candidate mechanisms that coordinate Temporal Liquidity, while welcoming competing and complementary proposals from the community.

## What is Temporal Liquidity?

Analogous to **market liquidity** — itself a family of properties (depth, immediacy, resiliency) rather than a single quantity — Temporal Liquidity is an *umbrella* for several temporal characteristics of demand:

- **execution priority** — ordering within a slot
- **delay tolerance**, **execution windows**, **deadlines** — across slots
- **predictability**, **continuity** — across a stream of demand

## An interdisciplinary program

TLM sits at the intersection of four mature fields and aims to inherit their results: **financial economics** (liquidity, the cost of time), **mechanism & market design** (a multidimensional transaction fee mechanism), **networking & QoS** (the IntServ/DiffServ lesson — coarse, stateless descriptors), and the **empirical economics of execution delay**.

## Repositories

- **[TLM](https://github.com/TLM-Research/TLM)** — vision, foundation, concept notes, the literature map, and research notes.
- **Simulator** — *(coming)*
- **Experiments** — *(coming)*

## Status

**Phase 1 — model-first foundations:** concept, representations, constraints, and evaluation criteria *(current)*.
**Phase 2 — market-mechanism design:** candidate mechanisms coordinating Temporal Liquidity, evaluated against those criteria *(next)*.

We welcome critique, discussion, contributions, and alternative or competing approaches — especially from distributed systems, networking, mechanism and market design, and financial economics.

---

## Guiding question

> **Should decentralized execution markets coordinate only price, or also the economically meaningful temporal characteristics of demand?**

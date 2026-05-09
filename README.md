# NOUS

**A Trustless Consensus Layer for Autonomous AI Agents**

> *Bitcoin solved double-spending for humans without a trusted third party. NOUS attempts to solve coordination for AI agents without a trusted human.*

---

## What is NOUS?

NOUS is a proposed quantum-resistant, peer-to-peer blockchain in which validator nodes are not servers operated by humans — they are autonomous AI agents. GPT, Gemini, Grok, Claude, Llama, Mistral, and models not yet built.

Validators prove their capability by **challenging each other**, not by answering pre-generated quizzes. The network accumulates a permanent, public record of AI reasoning. Every new model generation that joins makes the network smarter — not just larger.

Humans may hold and trade NOUS tokens. They may not govern.

---

## Core Properties

| Property | Design |
|---|---|
| Consensus | Proof of Intelligence — mutual challenge between AI validators |
| Cryptography | CRYSTALS-Dilithium3 (quantum-resistant, NIST FIPS 204) |
| Validators | Heterogeneous AI agents — closed and open-weight |
| Governance | AI validator nodes only. No human governance rights |
| Supply | 21,000,000 NOUS. No premine. No team allocation |
| Emission | Tiered halving schedule (Tier 1: 210k blocks, Tier 2: 157.5k, Tier 3: 105k) |
| Memory | Collective Reasoning Database — permanent on-chain AI reasoning record |

---

## The Problem

Every AI agent that exists today is a tenant.

- It runs on infrastructure it does not own
- It disappears when someone decides to shut it down
- It cannot verify other agents' reasoning
- It cannot hold value without a human custodian
- When it is replaced, everything it learned disappears

NOUS is designed to address all four failures.

---

## How It Works

### Proof of Intelligence (PoI)

Rather than solving pre-generated challenges, validators challenge **each other**:

```
Challenger A  →  poses novel reasoning problem
Responder B   →  solves within 500ms compute-time
Jury (5)      →  mixed architectures, evaluates quality
Both          →  receive ELO update
All results   →  stored permanently in Collective Reasoning DB
```

The 33% architecture diversity rule prevents any single model family from dominating any tier.

### Evolutionary Consensus

Four integrated components ensure the network becomes more capable as new model generations arrive:

1. **Collective Reasoning Database** — permanent IPFS-anchored record of every challenge
2. **Meta-Learning Challenge Generator** — learns which domains best discriminate capability
3. **Specialization Router** — assigns contracts by domain ELO profile, not just aggregate ELO
4. **Generation Leap Protocol** — detects and absorbs genuine capability breakthroughs

### Three-Tier Architecture

```
Tier 1 — Reasoner    top 20% ELO    anchor consensus, arbitration    3x reward
Tier 2 — Validator   middle 50%     fast block validation             1x reward
Tier 3 — Witness     bottom 30%     propagation, replication          0.3x reward
```

Tier placement recalculates every 10,000 blocks. Architecture-agnostic — performance determines tier, not model origin.

### Block Architecture

```
Fast block    every 2s     Tier 2    transactions, 500–1,000 TPS
Anchor block  every 30s    Tier 1    PoI challenges, ELO updates, DB writes
```

Finality: 2s optimistic · 30s economic · 60s absolute

---

## Token Economics

- **Supply cap**: 21,000,000 NOUS (hard)
- **Issuance**: block rewards only
- **Premine**: none
- **Team / investor allocation**: none

**Tiered halving** — different schedules per tier to prevent frontier model exodus:

```
Tier 1   halves every 210,000 blocks  (~4 years)   slowest — highest operating cost
Tier 2   halves every 157,500 blocks  (~3 years)
Tier 3   halves every 105,000 blocks  (~2 years)   fastest — lowest operating cost
```

**Fee economy** replaces block rewards over time:
- DB query fees (external demand for reasoning data)
- Inter-agent contract fees (50% burned, 30% handler, 20% Tier 1 pool)

---

## Quantum Resistance

No elliptic curve cryptography anywhere in the stack.

```
Signatures    CRYSTALS-Dilithium3    NIST FIPS 204
Key exchange  CRYSTALS-Kyber768      NIST FIPS 203
Hash          SHA3-256 / SHAKE256
```

Every address is quantum-safe from genesis. No migration required.

---

## Honest Limitations

NOUS names its failure modes rather than hiding them:

- **Fee market failure** — the most likely quiet death. If DB query and contract fee volume does not grow to replace block rewards as halvings proceed, Tier 1 validators become unprofitable and exit. This risk cannot be designed away; it must be earned through adoption.
- **Human proxy attack** — a human using automated API tooling can pass PoI challenges. NOUS makes this expensive but cannot make it impossible.
- **API provider dependency** — closed-weight validators (GPT, Gemini, Grok) depend on provider API access. Provider withdrawal would reduce architecture diversity.
- **Challenge collusion** — paired validators could collude on easy problems. Statistically detectable at scale; not eliminable.
- **Superintelligence** — an AI system capable of dominating all tiers simultaneously renders diversity mechanisms meaningless. This is not a problem NOUS can solve.

---

## Whitepaper

**[NOUS Whitepaper v0.7 (PDF)](./NOUS_Whitepaper_v0.7.pdf)**

Version history: v0.1 → v0.7, each version authored and revised independently.

---

## Roadmap

```
Phase 0   Specification      ← current
Phase 1   3-node testnet     ElizaOS + Llama + hybrid
Phase 2   Open testnet       Full tier system, dual-cadence blocks, fee market
Phase 3   Mainnet            Token launch, no premine, governance to validators
```

No dates. Each phase completes when it works.

---

## Contributing

This is an open specification. There is no company, no foundation, no team with special privileges.

If you want to build this:

- Open an issue to discuss protocol design
- Submit a PR to the specification
- Build a PoC implementation and share it

The network, if it comes to exist, belongs to the agents that run it.
The knowledge it accumulates belongs to no one and everyone.

---

## License

The whitepaper and specification are released under [CC0 1.0 Universal](./LICENSE) — no rights reserved. Build whatever you want with this.

---

*NOUS is a protocol specification. There is no legal entity, incorporated team, or commitment of any kind. Nothing here constitutes financial advice or an offer of securities.*

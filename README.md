# Feeeeelix

I build control and evidence layers for AI agents: inspect what they receive, enforce what they may do, and preserve proof of what happened.

## Agent Trust Stack

| Moment | Project | What it proves |
| --- | --- | --- |
| Before an agent gains a capability | [Audit Skill Supply Chain](https://github.com/FeeeeelixWong/audit-skill-supply-chain) | Open-source agent skills are reviewed in quarantine before installation, with provenance and integrity checks. |
| Before an agent spends | [AgentSpend Guard](https://github.com/FeeeeelixWong/agent-spend-guard) | Deterministic policy, approval thresholds, and payment receipts govern paid API calls. |
| After an agent acts | [IntentProof](https://github.com/FeeeeelixWong/intent-proof) | A local policy decision and a user-confirmed Solana transfer become a verifiable action receipt. |

The principle is simple: a model may explain an outcome, but it must not be the final authority over sensitive actions.

## Selected Work

- [AgentPay Firewall](https://github.com/FeeeeelixWong/agentpay-firewall) - an x402 payment-rail reference implementation for agent policy enforcement.
- [ProofOdds](https://github.com/FeeeeelixWong/proofodds) - deterministic, evidence-backed resolution receipts for prediction markets.
- [Meme Scanner](https://github.com/FeeeeelixWong/meme-scanner) - a Solana token-risk observer with explicit safety gates and a local dashboard.

## Working Principles

- Deterministic enforcement before probabilistic explanation.
- Local custody and explicit human confirmation for sensitive actions.
- Verifiable evidence instead of dashboard claims.

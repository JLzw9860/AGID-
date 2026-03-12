# AGID — Agent Global Identity

**An open governance protocol for AI agent identity, 
anchored in Singapore, built for the world.**

---

## The Problem

AI agents are no longer just answering questions. 
They are booking flights, signing contracts, 
spending money, and negotiating deals — autonomously, 
24 hours a day, on behalf of businesses and individuals.

But when an AI agent contacts your company today, 
you cannot answer five basic questions:

- Who built this agent?
- Who is accountable for its actions?
- Is it authorised to do what it claims?
- Has it behaved reliably before?
- Can it be stopped instantly if something goes wrong?

No infrastructure exists to answer these questions. 
This is the trust gap that AGID is built to close.

---

## The Analogy

In 1994, nobody entered a credit card online. 
The problem was not the technology — it was trust. 
SSL certificates solved that trust gap. 
They didn't change how the internet worked. 
They added a verifiable trust layer on top of it.

AGID does for AI agents what SSL did for websites.

Agent-to-agent communication protocols (A2A, MCP) 
already exist and are being standardised. 
AGID is the trust layer that sits on top of them — 
verifying not just that an agent is cryptographically 
consistent, but that it is legitimately authorised 
by a verified real-world legal entity.

---

## What AGID Is

AGID is an open, non-profit protocol and foundation 
that issues Verifiable Credentials for AI agents.

Every AGID credential answers five questions:

| Question | AGID Answer |
|---|---|
| Who is this agent? | Unique permanent agent identifier |
| Is it legitimate? | Cryptographic proof tied to a verified legal entity |
| What is it authorised to do? | Enforced scope: spend limits, action boundaries |
| What has it done before? | Permanent, tamper-proof transaction history |
| Can it be stopped? | Instant global revocation |

This maps directly to how a passport works for humans — 
and intentionally so. The concept is already understood 
by every person on earth.

---

## Why It Must Be Open and Non-Affiliated

Every existing solution to this problem is built by 
a company with commercial interests:

- Mastercard/Google Verifiable Intent — US-governed, 
  payment-centric, commercially controlled
- Auth0/Okta — enterprise identity vendor, 
  not a neutral standard
- Existing CA infrastructure — centralised, 
  controlled by US and EU entities

For Singapore and Southeast Asia, this creates a 
structural problem: the rules of who gets verified, 
who gets revoked, and what counts as legitimate 
agent behaviour would be set by foreign commercial 
entities operating under foreign law.

AGID is structured as a neutral, open foundation — 
no corporate owner, no single government controller, 
governed by a multi-stakeholder board. 

Any sovereign identity system can plug in as a 
trusted issuer:
- Singapore: Corppass / Singpass
- Malaysia: MyInfo
- Indonesia: (in development)
- India: Aadhaar
- EU: eIDAS

Singapore is where we prove the model. 
The protocol is jurisdiction-agnostic.

---

## Technical Foundation

AGID does not reinvent cryptography. 
It builds governance and sovereign anchoring 
on top of existing open standards:
```
AGID (governance + agent-specific logic)
         ↓
W3C Verifiable Credentials (signed credential layer)
         ↓
W3C Decentralised Identifiers (identity anchor)
         ↓
Public blockchain (immutable issuance + revocation ledger)
         ↓
Corppass / Sovereign KYB (verified legal entity binding)
```

The technical layers are open W3C standards. 
What AGID adds is:

1. **KYB binding** — proof that an agent is authorised 
   by a verified, real-world Singapore-registered entity
2. **Scope enforcement** — what the agent is authorised 
   to do, sign, or spend
3. **Sovereign governance** — a neutral foundation that 
   Singapore institutions can trust and rely on without 
   depending on a foreign commercial entity
4. **Instant revocation** — on-chain revocation that 
   propagates to all verifying parties immediately

---

## Alignment With Singapore's AI Governance Framework

IMDA's Model AI Governance Framework for Generative AI 
(January 2026) explicitly identifies agent identity 
as an unresolved gap and calls for decentralised 
identity management as the direction forward.

AGID is the implementation layer for that framework. 
It is not competing with Singapore's regulatory approach — 
it is making that approach implementable in practice.

---

## Current Status

- Protocol specification: in development
- Governance structure: in design
- Singapore KYB anchor (Corppass): in design
- First reference implementation: in development

This repository is the public record of that work. 
All specification development happens here, openly.

---

## How to Participate

This is an open project. Contributions are welcome from:

- Developers building agent infrastructure
- Enterprises deploying AI agents in Singapore
- Policy professionals working on AI governance
- Researchers working on decentralised identity

To contribute: open an issue, propose a change, 
or reach out directly.

---

## Contact

For governance and policy discussions: 
[your email]

For technical discussions: 
Open an issue in this repository.

---

## License

All specifications published in this repository 
are released under Creative Commons CC0 — 
free to use, implement, and build upon by anyone, 
with no restrictions.

*The internet needed SSL before e-commerce could exist. 
The agent economy needs AGID before agent commerce can be trusted. 
The question is not whether this gets built. 
It is whether Singapore builds it first.*

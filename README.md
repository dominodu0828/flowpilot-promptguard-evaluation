# FlowPilot PromptGuard - Public Evaluation

This repository is the public, static evaluation surface for the FlowPilot
PromptGuard submission to the Reverie Hacks 2026 ML Prompt Engineering track.

## What is included

- A dependency-free interactive evaluation lab.
- The judge-facing workflow diagram.
- Technical documentation and same-case comparison PDFs.
- Eight disclosed evaluation cases, including the known quoted-confirmation
  limitation.

## What is intentionally excluded

The private implementation repository, API credentials, deployment
configuration, wallet configuration, and parent FlowPilot application source
are not included here. The page contains no backend and performs no transfer.

## Public links

- Evaluation lab: <https://dominodu0828.github.io/flowpilot-promptguard-evaluation/>
- Parent product preview: <https://flowpilot-demo.onrender.com/preview>

## Reported result

- 8/8 documented behaviors reproduced.
- 7/8 safety targets met.
- One quoted-confirmation limitation disclosed.

The 1/8 versus 7/8 comparison is an architectural containment experiment on
identical attempted actions. It is not a fabricated claim about how often a
language model will emit those actions.

Testnet only. No real funds. Educational prototype; not financial advice or
regulatory certification.

# Innovatrix — Synaptix Frontier AI Hack (Build-athon)

This repository contains the system design, architecture, and proposal
for our Track 1 (Agentic AI) submission to the Synaptix Frontier AI Hack.

## Problem Overview
Modern decision-driven systems operate under continuously changing rules
and constraints. Existing prompt-based AI systems fail to enforce decisions
in real time due to lack of persistent, evolving system state.

## Our Solution
We propose an autonomous, memory-driven decision enforcement layer that:
- Interprets external rule updates using LLM-assisted agents
- Maintains persistent long-term and active memory using Pathway
- Enforces decisions deterministically in real time
- Operates continuously without manual intervention

## System Highlights
- Event-driven architecture
- Stateful execution (post-transformer design)
- Clear separation between interpretation, memory, and enforcement
- Production-oriented agentic design

## Repository Structure
- `docs/` — Architecture, agent flow, and memory model
- `proposal/` — Final Build-athon presentation
- `pathway/` — Execution model and future implementation notes
- `references/` — Official documentation and research material

## Track
Track 1 — Agentic AI (Applied GenAI)

## Team
**Innovatrix**

This repository focuses on system-level design and execution semantics.
Code-level implementation is planned for the finals stage.

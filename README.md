# slab

A deterministic development process for AI-assisted software engineering —
for solo developers and teams, independent of language, domain and AI client.

**Status:** specification phase. No code yet.

## Idea

AI agents write code fast, but their output is not deterministic.
slab puts a deterministic process around it:

- Every task moves through fixed states with typed gates.
  No code is written before a person approves the plan.
- Git and CI are the only authority. The agent never approves its own work.
- Reviews are isolated from the author's reasoning.
- Technologies plug in through packs; AI clients
  (Codex CLI, Claude Code, GitHub Copilot CLI) through adapters.
- The same process serves a single developer and a team.

## Documents

The specifications — core process, pack contract, adapters,
artifact formats — will be published in this repository.

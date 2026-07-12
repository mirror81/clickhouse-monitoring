---
title: "Agent mode now supports Grok 4.5"
description: "Pick x-ai/grok-4.5 from the model picker and the chmonitor AI agent will plan and run your ClickHouse diagnostics with it — over OpenRouter or AnyRouter."
date: 2026-07-12
tag: Update
---

The chmonitor AI agent now supports **Grok 4.5** (`x-ai/grok-4.5`). It shows up
in the model picker alongside the rest of the roster and works through the same
providers as every other model.

## How to use it

1. Open the agent and click the **model picker** in the composer.
2. Select **Grok 4.5** (`x-ai/grok-4.5`).
3. Ask away — "why is query latency spiking right now?", "show me the slowest
   queries in the last hour", "which tables are close to too-many-parts?"

Grok 4.5 is available through **OpenRouter** and **AnyRouter** (both providers
are listed for it), so as long as one of those keys is configured on your
deployment the model is selectable. If your deployment only has one provider
configured, the picker already filters to what's actually usable — no more
first-message failures from a model whose provider isn't set up.

## Why it matters

Grok 4.5 is a strong general-purpose model for turning a vague question into a
precise `system.*` query plan, which is exactly what the agent does on every
turn. Different models reason about ClickHouse diagnostics differently, so
having more options means you can pick the one that fits how you work.

The model list is data-driven from the central registry, so Grok 4.5 inherits
the same cost tracking, tool-use handling, and provider fallback as every other
entry. No extra setup required.

<Related />

---

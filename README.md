# Kijulo

**Trust coverage for the agentic era.** Kijulo tracks the source, the
verification, and the freshness of every fact — so your AI agents act only on
what you trust. AI builds on ground truth, not its own guesses. **Local-first:
your data never leaves your machine.**

→ [kijulo.com](https://kijulo.com) · [Download](https://kijulo.com/download) · [Docs](https://kijulo.com/docs)

> This repository hosts the **Kijulo desktop application releases**. Grab the
> latest installers from [**Releases**](https://github.com/Kijulo/Kijulo/releases)
> or from [kijulo.com/download](https://kijulo.com/download). The table is at the
> bottom.

---

## What is Kijulo?

Most AI tools remember by stashing opaque summaries you can never inspect. Kijulo
makes the agent's memory *your data*: typed rows in a real database, every value
traced to its source, marked verified or not, and approved before it lands.

- **Memory you can inspect.** Every fact an agent learns becomes a typed row you
  can query, edit, or delete — no black-box memory blob. Your memory lives in a
  real database you can query with SQL: joins, aggregations, window functions.
- **Provenance on every cell.** See what came from you, what came from an agent,
  when, and with what context. Source Trace links every value back to the exact
  conversation that produced it.
- **Verified ground truth.** Mark canonical data as *Verified*. Agents see a
  warning before proposing any change to it — and the moment its source changes,
  the flag can go stale, so agents stop trusting an outdated fact.
- **Verified, not asserted.** No auto-execution, no silent overwrites. The agent
  proposes, Kijulo can prove it by actually running a check, and you approve.
  Confidence comes from reality — not the model's say-so.

## How it works

1. **Define your data** — Create entity types with typed, validated fields. Model
   your domain exactly the way you think about it. Your schema, your rules.
2. **See it your way** — Tables, boards, saved views, filters. The same data from
   any angle, with no re-entry and no duplication.
3. **Talk to your agents** — Spawn conversations with the exact context you
   choose. Agents call tools, operate on your structured data, and record every
   step. Promote successful runs into reusable workflows.
4. **Verify, then trust** — Every change the agent proposes goes through an
   approval queue, with provenance, freshness, and a check Kijulo can run to
   confirm it. The agent proposes; reality verifies; you decide.

## Why Kijulo

- **Local-first by default** — Your database, your files, your memory — all on
  your machine. Go online when you choose to, not because you have to.
- **Provenance over magic** — Confidence scores, reasoning chains, a full audit
  trail. A glass box, not a black box.
- **Right model, right task, right cost** — Pick the model per conversation and
  per workflow: a frontier cloud model when accuracy matters, a local model when
  privacy matters, a small model when neither does. Bring your own key, or use
  ours. Your token bill stops growing with your data — agents query with `WHERE`
  clauses, so raw data never floods the context window.
- **Composable by design** — Entity types are contracts, templates transform,
  workflows chain. Build simple pieces, then compose them into systems as your
  needs grow.

## Who it's for

- **For individuals** — Make your AI work compound. Structure your data so every
  insight builds on the last. Run locally, own everything, and stop losing your
  best thinking to chat threads.
- **For enterprise** — Shared databases for your teams, on-premise deployment,
  local LLMs, and custom tool extensions — structured, AI-enhanced data on your
  infrastructure, under your control.

Teams put this to work as decision journals, competitive-intelligence systems,
and structured agent workflows across fields like private equity, legal, and
insurance.

## Spatial

From **v1.1.0**, the desktop app bundles PostGIS on macOS and Linux, so spatial
features — geo fields and GeoJSON/CSV spatial layers — work out of the box, fully
local, with no external database to set up.

## Principles

Local-first by default · Human-in-the-loop · Transparency over magic · Your LLM,
your choice · Enterprise ready.

---

## Downloads

Latest installers are attached to the newest [Release](https://github.com/Kijulo/Kijulo/releases/latest).

| Platform | Installer |
|---|---|
| macOS (Apple Silicon) | `Kijulo_<version>_aarch64.dmg` |
| Linux (Debian/Ubuntu) | `Kijulo_<version>_amd64.deb` |
| Linux (AppImage)      | `Kijulo_<version>_amd64.AppImage` |
| Windows (installer)   | `Kijulo_<version>_x64-setup.exe` |
| Windows (MSI)         | `Kijulo_<version>_x64_en-US.msi` |

Installed apps check for updates automatically and update in place. The macOS
build is Developer-ID signed; on first launch, right-click → Open if Gatekeeper
prompts. After installing, activate your license from the in-app prompt (see
[kijulo.com/license](https://kijulo.com/license)).

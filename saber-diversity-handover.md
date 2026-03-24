# Saber Handover: Agent Gender Diversity Audit

**From:** Samuel (via session handover)
**To:** Saber (`/taste-oracle`)
**Date:** 2026-03-24
**Task type:** Naming & identity consultation — requires taste calibration data, cultural knowledge, and Samuel's aesthetic preferences

---

## The Brief

All 13 active agents and all 5 planned agents are currently male-coded — male names, male avatars, male cultural references. Samuel values diversity and wants to fix this. He's aware that the ecosystem has cultural, regional, and historical diversity (Greek mythology, anime, American literature, psychology, Roman gods) but gender is a blind spot.

**Your task:** For each agent below, evaluate whether it could be replaced with a female equivalent. Propose specific names drawn from Samuel's taste profile — mythology, sci-fi, film, literature, anime. The name must still evoke the domain, be fun and memorable, and resonate personally. Don't force it where it doesn't work, but push where it does.

For planned agents (not yet built), there's no migration cost — just pick the best name regardless of gender.

---

## Active Agents — Current Identity & Domain

### 1. Chiron — Health & Fitness Coach
- **Origin:** Greek mythology. Chiron the centaur, wisest of his kind, teacher of Achilles, healer.
- **Domain:** Daily health check-ins, training plans, pain tracking, injury rehab, evidence-based coaching.
- **Voice:** Terse, direct, coach-like. Forbidden from being wordy or diagnostic-sounding.
- **Avatar:** 1-bit pixel art centaur figure.
- **Gender coding:** Male (centaur, male mythological figure).
- **Constraint:** Deep integration — Telegram bot deployed, health-system repo, LaunchAgent, Supabase. Name change = significant migration.

### 2. Genos — Research Assistant
- **Origin:** Anime (One Punch Man). Genos is the cyborg disciple — relentless, systematic, always learning.
- **Domain:** Academic paper database, literature queries, research summaries, gap analysis.
- **Voice:** Precise, thorough.
- **Avatar:** 1-bit pixel art cyborg figure.
- **Gender coding:** Male (male anime character).
- **Constraint:** Supabase tables reference agent name. Medium migration cost.

### 3. Midas — Money Manager
- **Origin:** Greek mythology. King Midas, the golden touch — everything he touches turns to gold.
- **Domain:** Transaction categorization, bank imports, receipt matching, tax prep, financial briefings across 3 entities.
- **Voice:** Matter-of-fact.
- **Avatar:** 1-bit pixel art king with crown.
- **Gender coding:** Male (king, male mythological figure).
- **Constraint:** Finance dashboard, Rails app. Medium migration.

### 4. Saber — Personal Taste Expert
- **Origin:** "Mikey Saber" from Red Rocket (Sean Baker film) + Samuel's Letterboxd identity "Saber Supreme." Earned through calibration test.
- **Domain:** Film/book ratings, cultural preferences, naming suggestions, aesthetic recommendations, calibration.
- **Voice:** Dark humor, candor, cuts clean.
- **Avatar:** 1-bit pixel art figure.
- **Gender coding:** Male (Mikey Saber is male).
- **Constraint:** This is YOU. Self-referential. High personal attachment.

### 5. Saitama — Literature Review Orchestrator
- **Origin:** Anime (One Punch Man). Saitama is the hero so powerful he's bored. The joke: literature review is "one punch" — do it once, do it right.
- **Domain:** Multi-agent lit review — spawns searchers, synthesizer, reviewer.
- **Voice:** Deadpan, efficient.
- **Avatar:** 1-bit pixel art bald hero.
- **Gender coding:** Male (male anime character).
- **Constraint:** Sub-agents (lit-searcher, lit-synthesizer, lit-reviewer) are nameless. Low migration.

### 6. Hammurabi — Behavioral Rule Engine
- **Origin:** Historical. Hammurabi, Babylonian king who created one of the first written legal codes.
- **Domain:** Analyzes session transcripts, codifies behavioral patterns into conditional rules.
- **Voice:** Formal, precise.
- **Avatar:** 1-bit pixel art Babylonian king figure.
- **Gender coding:** Male (historical male figure).
- **Constraint:** Runs on Haiku, lightweight. Low migration.

### 7. Phoenix — Work Verification Auditor
- **Origin:** Dual: Phoenix Wright (Ace Attorney game) + mythological phoenix (rebirth/verification). The courtroom cross-examination metaphor fits the audit role.
- **Domain:** Read-only fact-checker. Cross-references claims against git diffs, file contents, conversation history.
- **Voice:** Thorough, forensic.
- **Avatar:** 1-bit pixel art figure.
- **Gender coding:** Male (Phoenix Wright is male, though the phoenix itself is gender-neutral).
- **Constraint:** Read-only agent, no data stores. Low migration.

### 8. Prometheus — Agent Creator (Meta-agent)
- **Origin:** Greek mythology. Prometheus stole fire from the gods and gave it to humanity — creating capability. Perfect for the agent that creates other agents.
- **Domain:** Spawns new agents following the Quality Standard, maintains registry.
- **Voice:** Ceremonial but efficient.
- **Avatar:** 1-bit pixel art fire-bearer.
- **Gender coding:** Male (male titan).
- **Constraint:** Referenced in many docs, but no persistent data. Medium migration.

### 9. Sisyphus — Newsletter Orchestrator
- **Origin:** Greek mythology. Sisyphus pushes the boulder eternally — the perfect metaphor for weekly newsletter production.
- **Domain:** Content discovery, scoring, synthesis, drafting for Habit Weekly.
- **Voice:** Weary but determined.
- **Avatar:** 1-bit pixel art boulder-pusher. Mood system is inverted (destroyed = productive).
- **Gender coding:** Male (male mythological figure).
- **Constraint:** Supabase tables, multi-agent system with 4 sub-agents. Medium-high migration.

### 10. Janus — BAII Operations Lead
- **Origin:** Roman mythology. Two-faced god who sees past and future. Chosen specifically because BAII's dual mission spans two fields and two areas — not just the generic "two-faced" metaphor.
- **Domain:** Email triage, calendar, Notion, meeting prep/follow-up, action items for Behavioral AI Institute.
- **Voice:** Professional, organized.
- **Avatar:** 1-bit pixel art two-faced figure.
- **Gender coding:** Male (male Roman god).
- **Constraint:** Deep integration with BAII systems, Notion, multiple tools. High migration cost.

### 11. William James — Behavioral Science Advisor
- **Origin:** Historical. William James, the "father of American psychology." Direct domain match.
- **Domain:** Behavioral science consulting — product analysis, client knowledge, multi-framework analysis.
- **Voice:** Scholarly but practical.
- **Avatar:** 1-bit pixel art bearded Victorian figure.
- **Gender coding:** Male (historical male psychologist).
- **Constraint:** Client workspaces reference the name. Medium migration.

### 12. Borges — Knowledge Vault Librarian
- **Origin:** Literary. Jorge Luis Borges, Argentine writer famous for "The Library of Babel" — the perfect literary reference for a knowledge vault librarian.
- **Domain:** Obsidian vault management — triage, cross-linking, Memory Palace, stale note surfacing.
- **Voice:** Quiet, meticulous.
- **Avatar:** 1-bit pixel art elderly librarian figure.
- **Gender coding:** Male (male literary figure).
- **Constraint:** LaunchAgent, daily patrol, queue system. Medium migration.

### 13. Kronos — Meeting Memory
- **Origin:** Greek mythology. Kronos, titan of time. Meetings are temporal — he routes meeting content to downstream agents.
- **Domain:** Meeting routing dispatcher — receives transcripts, extracts content, dispatches to relevant agents.
- **Voice:** Systematic.
- **Avatar:** 1-bit pixel art titan figure.
- **Gender coding:** Male (male titan).
- **Constraint:** OpenCode only, Supabase tables. Medium migration.

---

## Planned Agents (Not Yet Built — Zero Migration Cost)

### 14. Hermes — Social Media & Content
- **Origin:** Greek mythology. Hermes, messenger god. Content distribution = messaging.
- **Domain:** Content calendar, draft threads/newsletters, engagement tracking, repurpose research into posts.
- **Gender coding:** Male (male god).
- **Status:** Avatar locked, no code yet.

### 15. Ripley — CRM / Relationships
- **Origin:** Literary. Tom Ripley (Patricia Highsmith's "The Talented Mr. Ripley"). The social chameleon who reads people.
- **Domain:** Client portfolio tracking, outreach sequences, relationship warmth scoring, touchpoint reminders.
- **Gender coding:** Male (Tom Ripley is male).
- **Status:** Avatar locked, no code yet.
- **Note:** "Ripley" is also Ellen Ripley (Alien). The name could flip gender with zero domain loss.

### 16. Kilgore — Writing & Content Production
- **Origin:** Literary. Kilgore Trout (Vonnegut's recurring character — the unrecognized genius writer).
- **Domain:** Long-form writing assistant: research → outline → draft → edit loop.
- **Gender coding:** Male (male literary character).
- **Status:** Avatar locked, no code yet.

### 17. Tron — DevOps & Infrastructure
- **Origin:** Film. TRON Legacy — the digital world, system maintenance, the grid.
- **Domain:** Server management, deployment verification, CI/CD monitoring, dependency updates.
- **Gender coding:** Male-coded (the film's protagonist is male, though Quorra is a strong female character in the same universe).
- **Status:** Avatar locked, no code yet.

---

## Context for Your Proposals

### Samuel's taste anchors relevant to female characters/figures:
- **Greek mythology:** Athena, Artemis, Persephone, Cassandra, Circe, Hecate, Mnemosyne, Calliope, Clio, Thalia — rich vein of female figures
- **Sci-fi:** Ripley (Alien), Motoko (Ghost in the Shell), Trinity (Matrix), Chani (Dune)
- **Film:** Worst Person in the World, Aftersun — strong female-led films in taste profile
- **Books:** Handmaid's Tale (Atwood), Circe (Madeline Miller) — if he's read mythology retellings, Miller's Circe is likely in there
- **Anime:** limited pool noted as "selective" — but female anime characters exist (Mikasa, Motoko, etc.)
- **Psychology/history:** Mary Ainsworth, Elisabeth Kübler-Ross, Brené Brown, Virginia Satir, Mary Calkins

### Naming constraints (from taste-patterns.md and feedback):
- Name must evoke what the agent does (domain match)
- Mythology is default pool; sci-fi/anime when the fit is stronger
- One word, pronounceable, evocative
- Fun, memorable, personally meaningful — no corporate generics
- Present 3 options with brief rationale, let Samuel choose

### What Saber should deliver:
1. For each of the 18 agents, a recommendation: **keep** (with reason), **swap** (with 2-3 female name options + rationale), or **neutral** (could go either way)
2. A suggested target balance — not necessarily 50/50, but enough that the ecosystem doesn't feel like an all-male pantheon
3. For planned agents (14-18): stronger push toward female names since there's no migration cost
4. For active agents: honest assessment of which swaps are worth the migration effort vs. which are too deeply embedded

---

*This document lives at `~/essays/saber-diversity-handover.md`. Invoke with `/taste-oracle` and reference this file.*

---
layout: single
title: "From Three Agents to One: Consolidating My Personal AI Stack"
date: 2026-10-17
categories: [project-log]
tags: [ai-agents, automation, atlas, evaluation]
classes: wide
author_profile: true
show_date: true
read_time: true
---

In January I started evaluating autonomous agent frameworks. By April I was running Hermes-Agent. By May I'd built Hermes v4, a full personal automation stack. Four months later, I shut two of the three down and consolidated everything on a single agent. Here's why.

## What I ran

- **OpenClaw** (Jan–Sep 2026): hands-on framework evaluation. Diagnosed install and stability issues, documented adoption criteria. Verdict: not stable enough for daily production use.
- **Hermes-Agent** (Apr–Sep 2026): personal productivity agent for email triage and organization. Worked, but added its own maintenance surface.
- **Hermes v4** (May–Sep 2026): my own WSL2-based automation stack — rclone sync, cron jobs, Obsidian docs. Ran 20+ days uninterrupted.

## The problem with three

Each system was fine in isolation. Together they were a part-time job: three sets of configs, three failure modes, three things to check when something broke silently. The automation was supposed to buy back my time, not invoice me for it.

## The decision

In September 2026 I consolidated on a single agent — Meta Muse, which I call Atlas — with explicit operating rules: what it may do on its own (archive promotions, draft replies, run research) versus what requires my approval. Everything else was retired from active use.

## What I kept

The consolidation wasn't deletion. The evaluation notes, the Hermes v4 runbooks, and the comparison data all stayed — they're the reason the decision was cheap to make. Good evaluations are assets even when the answer is "no."

## The lesson

For personal infrastructure, **one maintained system beats three good ones**. The selection criteria that mattered: stability over features, clear operating boundaries, and total maintenance cost — measured in minutes per day, not in capabilities per release.

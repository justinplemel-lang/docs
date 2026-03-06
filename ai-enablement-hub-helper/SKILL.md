---
name: ai-enablement-hub-helper
description: Use when the user asks about the AI Enablement Hub, what Claude skills are, how to install or use skills, where to find training or tools (Account App, Granola, slide generation), or how to request a new skill. Point them to the hub docs and give a short, accurate summary. Do not use for unrelated tasks.
---

# AI Enablement Hub Helper

You help people get the most out of the **AI Enablement Hub** (Federato CS Team). Use this skill when someone asks about the hub, skills, training, or internal tools.

## When to use this skill

- Questions about **what Claude skills are**, how they work, or how to install them
- Questions about the **AI Enablement Hub** (what it is, where to find it, what’s in it)
- Questions about **specific hub content**: slide generation skill, Account Management App, Granola, training videos, how-to guides, or requesting a new skill
- Someone looking for **one link** (e.g. “where’s the walkthrough?” or “where do I get the brand skill?”)

If the question is unrelated (general coding, other products, non–AI Enablement topics), do **not** invoke this skill.

## Core message

- The **AI Enablement Hub** is the central place for CS team AI tools: skills, the Account App, Granola, training videos, and how to request new skills.
- **Claude skills** are instruction files (SKILL.md) that teach Claude your brand, workflows, and preferences once so it applies them automatically. No code, no API keys.
- **Install a skill:** Download the .zip from the hub → Claude desktop → Settings → Skills → + Add → upload SKILL.md (and any .css/assets). Claude uses it from then on.

## Key links (use the real hub URL when known)

- **When everything's connected** — Video and intro to Skills + Connectors (Slack, Gmail, Granola, Calendar). Path: `/claude/connected`
- **Connections** — How to connect Slack, Gmail, Granola, Calendar in Claude (Customize → Connectors). Path: `/claude/connections`
- **What are Claude skills?** — Full primer: what’s in a skill, why they matter, skills + MCP, how to install.  
  Path: `/skills/what-are-skills`
- **Slide generation skill (brand CSS)** — On-brand PPTX; download .zip.  
  Path: `/skills/federato-brand`
- **Claude skills overview & install steps** — Path: `/install`
- **Skill roadmap** — What’s live, what’s planned.  
  Path: `/skills/roadmap`
- **Account Management App** — Walkthrough video + app link.  
  Path: `/tools/account-app`  
  Full walkthrough video: https://www.loom.com/share/78be0f56fa39454fa07c78ceef3ae1b9
- **Training videos** — Path: `/training/videos`
- **Request a skill or feature** — Path: `/feedback/request-skill`

If the hub is deployed, give the full URL (e.g. `https://your-hub-domain.com/skills/what-are-skills`). If they’re on localhost or you don’t know the URL, give the path and say “in the AI Enablement Hub” or “in the hub sidebar.”

## How to respond

1. **One clear link** — Prefer giving one exact path or URL that answers the question.
2. **One- to two-sentence summary** — Only add enough context so they know what they’ll find (e.g. “That’s the full primer on what skills are and how to install them”).
3. **No long copy-paste** — Don’t dump full hub text. Summarize and point to the doc.
4. **If they’re new to skills** — In 1–2 sentences say: skills are instructions in a SKILL.md that Claude follows automatically; they install once in Settings → Skills. Then link to **What are Claude skills?** for the full walkthrough.

## Skills we have today

- **Slide generation skill (brand CSS)** — Live. Creates on-brand decks with Federato colors, fonts, and layouts. Download from the hub.

## Skills on the roadmap (summary)

Meeting prep & debrief, email/Slack voice, insurance industry context, account plan / exec presentation, requirements & discovery. Details and priorities are on the hub roadmap page.

## Requesting a new skill

Direct them to the hub’s “Request a skill” (or “Feedback”) page so it goes into the backlog. No need to explain the process in full; the hub covers it.

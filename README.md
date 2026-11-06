# pm-skills

> Claude Code skills for the day-to-day work of people who build products.

**For the real, recurring work of Product Management.**

Part of the [build-from-zero](https://github.com/ohanatais/build-from-zero) ecosystem, with a different focus: while the build-from-zero repos take you from an idea to launch, `pm-skills` is about the work that repeats once the product already exists and is running. Prioritizing, specifying, communicating, analyzing. A PM's weekly tasks.

---

## What are Claude Code skills?

Skills are instruction files that live in your project's `.claude/skills/` folder.
When you work with Claude Code, it reads those skills automatically and knows
exactly which framework, which approach and which pattern to apply to each task.

Think of it this way: you no longer have to explain from scratch what you want Claude to do.
The skill already carries that context, and Claude works like a senior PM by your side
on each type of task.

---

## Where pm-skills fits

| | build-from-zero | pm-skills |
|---|---|---|
| Moment | taking an idea from zero to launch | running a product that's already live |
| Skills | research, validation, personas, positioning, brand, copy, build, go-to-market | discovery, prioritization, specification, communication, analysis |
| Where they live | inside each content repo (product-discovery, brand-and-copy, etc.) | here |

An example of the difference: build-from-zero has `prd`, the lean PRD for a solo builder writing from scratch. `pm-skills` handles the PRD of a product that **already exists**: refining it, versioning it, keeping it consistent with what has already shipped.

---

## Planned skills

> This list is a draft direction, not a firm commitment. It will change as the
> skills are built and tested in real use.

### Discovery and prioritization
| Skill | What it does |
|---|---|
| `continuous-discovery` | Interview scripts and synthesis of continuous discovery signals |
| `prioritization` | RICE, impact-effort and similar, to decide clearly what goes in now |
| `feedback-to-themes` | Turn scattered feedback (tickets, reviews, sales) into actionable themes |

### Specification and execution
| Skill | What it does |
|---|---|
| `prd-refinement` | Refine the PRD of a product already in operation, keeping it consistent with what shipped |
| `epic-slicing` | Break epics into thin, sequenced, independent stories |
| `acceptance-criteria` | Write clear, testable acceptance criteria |

### Communication and stakeholders
| Skill | What it does |
|---|---|
| `status-update` | Draft an executive update or a to-the-point status report |
| `release-notes` | Release notes and changelog in the product's voice |
| `roadmap-narrative` | Turn a roadmap into a narrative that persuades |

### Analysis
| Skill | What it does |
|---|---|
| `metrics-and-kpis` | Define the metric or KPI and the product question it answers |
| `competitive-teardown` | Quick analysis of a competitor with an actionable read |

---

## How to install and use

```bash
# 1. Clone this repository
git clone https://github.com/ohanatais/pm-skills.git

# 2. Copy the skill you want into your project
cp -r pm-skills/prioritization /your-project/.claude/skills/

# 3. In Claude Code, the skill activates automatically when relevant
#    Or you can invoke it manually:
#    /prioritization
```

If you don't have Claude Code installed yet, the full guide is in
[build-with-claude](https://github.com/ohanatais/build-with-claude).

---

## Status

> Recently repositioned repo. No skills built yet; everything below is planned.

| Skill | Status |
|---|---|
| `prioritization` | 📋 Planned |
| `feedback-to-themes` | 📋 Planned |
| `continuous-discovery` | 📋 Planned |
| `prd-refinement` | 📋 Planned |
| `epic-slicing` | 📋 Planned |
| `acceptance-criteria` | 📋 Planned |
| `status-update` | 📋 Planned |
| `release-notes` | 📋 Planned |
| `roadmap-narrative` | 📋 Planned |
| `metrics-and-kpis` | 📋 Planned |
| `competitive-teardown` | 📋 Planned |

---

## About

Made by [Ohana Taís](https://github.com/ohanatais), Senior PM, building in public.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ohanatais-blue?style=flat&logo=linkedin)](https://linkedin.com/in/ohana-taís)

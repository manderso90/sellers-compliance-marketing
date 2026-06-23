# Commands Index

Complete reference for all available commands in the Seller's Compliance marketing workspace.

Each command has its own file in this folder with usage details and examples.

---

## Content Creation

| Command | Description | Command File | Skill File |
|---|---|---|---|
| `/linkedin-post [topic]` | Draft a LinkedIn post | `linkedin-post.md` | `Skills/Create_LinkedIn_Post.md` |
| `/facebook-post [topic]` | Draft a Facebook post | `facebook-post.md` | `Skills/Create_Facebook_Post.md` |
| `/photo-analysis [photos]` | Turn job photos into post drafts | `photo-analysis.md` | `Skills/Turn_Photos_Into_Content.md` |
| `/repurpose-content [content]` | Adapt content for a different platform or format | `repurpose-content.md` | `Skills/Repurpose_Content.md` |

## Planning

| Command | Description | Command File | Skill File |
|---|---|---|---|
| `/content-plan [month]` | Build a monthly content calendar | `content-plan.md` | `Skills/Build_Content_Calendar.md` |

## Research

| Command | Description | Command File | Skill File |
|---|---|---|---|
| `/competitor-review [company]` | Research and profile a competitor | `competitor-review.md` | `Skills/Analyze_Competitor.md` |

## Reporting

| Command | Description | Command File | Skill File |
|---|---|---|---|
| `/monthly-report [month]` | Generate a monthly marketing summary | `monthly-report.md` | `Skills/Monthly_Marketing_Report.md` |

---

## How Commands Work

1. Type the command with any relevant context (topic, photos, month, etc.)
2. Claude reads the command file and the linked skill file
3. Claude follows the defined process and produces the output
4. Output is saved to the appropriate folder

**Always give context.** `/linkedin-post about water heater strapping for real estate agents` produces a much better result than `/linkedin-post` alone.

---

## The Four Layers

This workspace uses four layers of AI capability:

| Layer | What It Is | Where It Lives |
|---|---|---|
| **Knowledge** | What SC knows | `01_COMPANY_KNOWLEDGE/`, `04_CONTENT_LIBRARY/`, `05_RESEARCH/` |
| **Instructions** | How Claude should behave | `CLAUDE.md`, `07_AI_INSTRUCTIONS/*.md` |
| **Skills** | Repeatable workflows | `07_AI_INSTRUCTIONS/Skills/` |
| **Commands** | Shortcuts to invoke skills | `07_AI_INSTRUCTIONS/Commands/` (this folder) |

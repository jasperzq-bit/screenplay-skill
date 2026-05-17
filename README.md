# Screenplay Skill

AI-powered screenplay creation for short dramas, films, and ads. Produces professional-grade scripts ready for production.

## Content Types

| Type | Description |
|---|---|
| Multi-episode vertical drama | Viral-style short series for platforms |
| Standalone short film | Single short film, suspense, arthouse |
| Brand film / TVC | Ads, brand stories |

## Core Principles

- **Emotion first** — every scene hits at least one beat (thrill / heartbreak / twist / humor / tears)
- **Natural dialogue** — pauses, interruptions, trailing off. No clean AI-perfect lines.
- **Hook-driven** — viewers swipe away in seconds. Every 30s is a checkpoint, every episode ends on a cliffhanger.
- **Character voice** — no two characters sound the same. Dialogue is never interchangeable.
- **AI-adaptation aware** — every scene description accounts for AI video generation constraints.

## Quality Gates (pre-output)

- **Dialogue**: characters don't explain feelings in 3+ sentences, no "I understand how you feel" clichés
- **Pacing**: strong hook in first 15s, emotional peak every 45s, cliffhanger endings
- **Scene**: descriptions detailed enough for image generation, max 3 core characters per scene

## File Structure

```
SKILL.md                              # Main skill definition
references/
├── format-series.md                  # Multi-episode drama framework
├── format-film.md                    # Standalone film framework
├── character-standards.md            # Character design standards
├── script-standards.md               # Script & dialogue standards
└── ai-adaptation.md                  # AI generation constraints
```

## Install

```bash
# Clone into your global Claude Code skills directory
git clone https://github.com/jasperzq-bit/screenplay-skill.git ~/.claude/skills/screenplay
```

Or copy the `screenplay` folder directly into your project's `.claude/skills/`.

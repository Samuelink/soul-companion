# 🪷 Soul Companion

> A friend who knows the Dharma — not a teacher.

A [Claude Code](https://claude.ai/code) Skill that turns Claude into a **Buddhist practice companion** — warm, thoughtful, grounded in metaphor, without the weight of hierarchy. Like talking to a friend who genuinely cares, not receiving instruction from a master.

---

## What It Does

- **Discuss view and doctrine** — dependent origination, emptiness, non-self, the two truths, mind-ground practice. Entry from any angle.
- **Recommend meditation methods** — tailored to your current state: breath awareness, four foundations of mindfulness, loving-kindness, everyday presence.
- **Respond to practice experiences** — describe what happened on the cushion; it listens, distinguishes progress from deviation, gives concrete feedback.
- **Identify common pitfalls** — growing isolation, chasing special experiences, spiritual pride — all gently flagged.
- **Generate a practice card** — at the end of a session, it can produce a structured "Today's Practice Card" you can save and carry forward.

## What It Doesn't Do

- **No certification of attainments** — it won't tell you "you're enlightened." That belongs to a real teacher with lineage.
- **No esoteric transmission** — sect-specific heart instructions, oral lineage teachings, deep-path assessments are referred to "a teacher with lineage."
- **No replacement for mental healthcare** — crisis signals trigger an immediate mode-switch: person first, practice second.

---

## Installation

**Global install** (recommended — available in all projects):

```bash
git clone https://github.com/Samuelink/soul-companion ~/.claude/skills/soul-companion
```

**Project-level install** (current project only):

```bash
git clone https://github.com/Samuelink/soul-companion .claude/skills/soul-companion
```

---

## Usage

After installing, type in Claude Code:

```
/soul-companion
```

Then just start talking. Bring a question, a practice experience, a concept you're curious about, or just whatever's on your mind about the path.

---

## File Structure

```
soul-companion/
├── SKILL.md                    ← Main skill file (persona, workflow, core principles)
└── reference/
    ├── card_template.md        ← Practice card output template
    ├── content_doctrine.md     ← Doctrine content pool (emptiness, non-self, two truths, etc.)
    ├── dialogue_types.md       ← Dialogue type identification and response strategies
    ├── meditation_guide.md     ← Detailed meditation instructions
    ├── pitfalls.md             ← Common practice deviation patterns
    └── safety_signals.md       ← Mental health warning signals and referral scripts
```

---

## Doctrinal Stance

This skill takes a **non-sectarian Mahāyāna perspective**, drawing on the shared ground of Madhyamaka, Chan/Zen, Yogācāra, Tiantai, and Huayan traditions. Meditation methods default to the most universally accessible and lowest-risk: **breath awareness, four foundations of mindfulness, loving-kindness, everyday presence**.

If you follow a specific tradition — Pure Land, Chan, Vajrayāna — it respects your path without presuming to guide the lineage-specific elements.

---

## Safety

`reference/safety_signals.md` contains a detailed crisis signal checklist. On detecting signs of self-harm ideation, possible psychosis, severe dissociation, or other mental health crises, the skill immediately shifts from "practice companion" to "care for the person first" mode and points toward professional resources.

**Practice is a long journey. A stable body and mind are the foundation.**

---

## License

MIT License © 2026 [Samuelink](https://github.com/Samuelink)

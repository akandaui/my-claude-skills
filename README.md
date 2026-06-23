# my-claude-skills

A collection of Claude Code skills by **Akanda**.

---

## Master UI Skill

A Claude Code skill synthesized from **23 foundational UI/UX design books**, including the full UXPin series, O'Reilly Microinteractions, Designing Interfaces (Jenifer Tidwell), and Task-Centered UI Design.

### What it covers

- Visual Hierarchy & Layout
- Color Theory
- Typography
- White Space & Minimalism
- UI Design Patterns
- Consistency & Style Guides
- Microinteractions
- User Experience & Research
- Visual Storytelling
- Flat Design & Modern Aesthetics
- Design Process

### Installation

Add this to your `~/.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": {
    "master-ui": {
      "source": {
        "source": "git",
        "url": "https://github.com/akandaui/my-claude-skills.git"
      }
    }
  }
}
```

Then install via Claude Code:

```
/install-skill master-ui
```

### Usage

Type `/master-ui` in any Claude Code session to activate the skill, or it will auto-activate when working on UI/UX tasks.

## License

MIT

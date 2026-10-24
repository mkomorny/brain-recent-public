# Brain Recent

> **Tri-Platform Agent Skill** for Claude Desktop / Code, Grok CLI, and Google Antigravity / Gemini.  
> Chronological Listing of Recently Captured Memories — Lists most recently stored Second Brain memories in reverse-chronological order, providing immediate awareness of recent captures and updates.

---

## Overview

`brain-recent` provides standardized capabilities across conversational AI platforms:
- Reverse-chronological memory listing (/brain-recent [limit]).
- Configurable display limit (default 5, max 20).
- Compact summary view displaying ID, date, tags, volatility, and summary.
- Tri-platform NTFS junctions connecting Claude, Grok, and Antigravity.
- Standard documentation suite: SKILL.md, HOW_TO_USE.txt, IMPLEMENTATION_PLAN.md, and README.md.

---

## Tri-Platform Architecture

Zero duplicate code across platforms. Canonical source resides in `.agents`:
- **Canonical Source**: `C:\Users\<you>\.agents\skills\brain-recent`
- **Claude**: `C:\Users\<you>\.claude\skills\brain-recent` (NTFS Junction)
- **Grok**: `C:\Users\<you>\.grok\skills\brain-recent` (NTFS Junction)
- **Antigravity**: `C:\Users\<you>\.gemini\config\skills\brain-recent` (NTFS Junction)

---

## Documentation Suite

- [`HOW_TO_USE.txt`](HOW_TO_USE.txt): Standardized user guide and prompt templates.
- [`IMPLEMENTATION_PLAN.md`](IMPLEMENTATION_PLAN.md): Feature checklist and roadmap.
- [`App Changes Tracker.html`](App%20Changes%20Tracker.html): Interactive visual version log.
- [`SKILL.md`](SKILL.md): Agent system instructions and triggers.

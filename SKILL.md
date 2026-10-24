---
name: brain-recent
description: >-
  Lists your most recently stored Second Brain memories in reverse-chronological order.
  Use when the user types /brain-recent or wants to see what was recently captured.
  Executes immediately with no approval needed. Optional: specify a limit (default 5, max 20).
---

# Brain Recent — List Recent Memories (`/brain-recent`)

## When invoked

Execute **immediately** by calling the `second-brain` MCP `list_recent` tool. No approval needed.

## Syntax

```
/brain-recent [limit]
```

- `limit`: Number of memories to show (default 5, max 20)

## Examples

```
/brain-recent
/brain-recent 10
/brain-recent 20
```

## After results

Display results as a clean reverse-chronological list showing: ID, title, date, and a brief summary of each memory.
If any result is truncated, suggest `/brain get <id>` to view the full content.

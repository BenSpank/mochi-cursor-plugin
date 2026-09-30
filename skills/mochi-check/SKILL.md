---
name: mochi-check
description: Compare the current work with what was agreed in meetings before it goes out. Use when someone wants to be sure a PR, spec or plan matches the team's decisions.
---

# mochi-check

Work out what the change is about from the diff or the document, then find the meetings behind it with `query_mochi_meetings` and `get_meetings`.

Report in three short lists, each item with the meeting and date it comes from:
- **Matches**: what the work does as agreed.
- **Missing**: what was agreed and isn't there yet.
- **Not discussed**: what the work adds that no meeting mentions. It may be fine; a reviewer should know.

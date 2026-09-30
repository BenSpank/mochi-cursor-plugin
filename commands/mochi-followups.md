---
name: mochi-followups
description: Turn the follow-ups from recent meetings into today's to-do list for this repo.
---

# mochi-followups

Read the last week of meetings (`list_meetings` with `from`, then `get_meetings`) and pick out the follow-ups that belong to this person or this codebase.

Drop the ones the repo shows are already done. Order the rest by what unblocks others first, and give each one a line: what to do, which meeting asked for it, and anything that needs a conversation before starting.

Offer to save the list as a markdown file in the repo.

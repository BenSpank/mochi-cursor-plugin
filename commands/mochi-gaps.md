---
name: mochi-gaps
description: List what meetings asked for that the code doesn't do yet.
---

# mochi-gaps

Pick the project from the repo, or ask. Look back two weeks unless told otherwise.

Collect every requirement, decision and action item from those meetings (`list_meetings`, `query_mochi_meetings`, `get_meetings`). Then check the code and `git log` for each one.

Return three groups: done (with the commit or file), partly done, and not started (with the meeting, the date, and who took it on). Leave out items a later meeting dropped or postponed.
